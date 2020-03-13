# try_node_express

## express アプリ開発環境構築
```
$ npm install express-generator -g
$ nodenv rehash
$ express --view=pug --git try_node_express

   create : try_node_express/
   create : try_node_express/public/
   create : try_node_express/public/javascripts/
   create : try_node_express/public/images/
   create : try_node_express/public/stylesheets/
   create : try_node_express/public/stylesheets/style.css
   create : try_node_express/routes/
   create : try_node_express/routes/index.js
   create : try_node_express/routes/users.js
   create : try_node_express/views/
   create : try_node_express/views/error.pug
   create : try_node_express/views/index.pug
   create : try_node_express/views/layout.pug
   create : try_node_express/.gitignore
   create : try_node_express/app.js
   create : try_node_express/package.json
   create : try_node_express/bin/
   create : try_node_express/bin/www

   change directory:
     $ cd try_node_express

   install dependencies:
     $ npm install

   run the app:
     $ DEBUG=try-node-express:* npm start

$ cd try_node_express/
$ echo "# try_node_express" >>README.md
$ git init
$ git add .
$ git commit -m "first commit"
$ git remote add origin git@github.com:gbz3/try_node_express.git
$ git push -u origin master
$ cd try_node_express/
$ npm install
～省略～
npm notice created a lockfile as package-lock.json. You should commit this file.
added 118 packages from 174 contributors and audited 247 packages in 7.239s
found 1 low severity vulnerability
  run `npm audit fix` to fix them, or `npm audit` for details
$ npm audit
～省略～
found 1 low severity vulnerability in 247 scanned packages
  run `npm audit fix` to fix 1 of them.
$ npm audit fix
npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
+ pug@2.0.4
removed 3 packages and updated 8 packages in 4.604s
fixed 1 of 1 vulnerability in 247 scanned packages
$ npm start

> try-node-express@0.0.0 start $HOME/git_repos/try_node_express
> node ./bin/www
```
→localhost:3000 をブラウザで開く

## nodemon 導入
```
$ npm install -g nodemon
$ nodenv rehash
$ npm start

> try-node-express@0.0.0 start $HOME/git_repos/try_node_express
> nodemon -e js,pug,css ./bin/www

[nodemon] 2.0.2
[nodemon] to restart at any time, enter `rs`
[nodemon] watching dir(s): *.*
[nodemon] watching extensions: js,pug,css
[nodemon] starting `node ./bin/www`
```

