# webpack
in terminal:
1. npm init -y
2. npm install webpack webpack-cli --save-dev
3. create file webpack.config.js, in file:
4. const path = require('path');
    module.exports = {
        mode: 'development/production' 
        entry: './src./index.js',
        output: {
            filename: 'index.js',
            path: path.resolve(__dirname, 'build'),
    }
    } 
5. "scripts": {
    "dev": "webpack --mode=development",
    "prod": "webpack --mode=production"
  },

for dev server:
6. npm install webpack-dev-server --save-dev
7. "scripts": {
    "dev": "webpack-dev-server --mode=development",
  },

8. npm install --save-dev @babel/core @babel/cli @babel/node @babel/preset-env
9. npm i handlebars --save-dev
10. npm i style-loader --save-dev


 при копіюванні сборщика: «Находясь в папке проекта удалить папку .git связанную с репозиторием сборки выполнив следующую команду npx rimraf .git.»
11. npm install --save-dev css-loader
