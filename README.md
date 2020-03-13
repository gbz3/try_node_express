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
```

