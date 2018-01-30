# udacity-catalog-clone

##Credits
https://github.com/maxdow/minimal-webpack-boilerplate

##How

This project set a minimal structure 

    src/       --> your app sources + index.html template
    conf/      --> webpack configuration
    .babelrc   --> es2015 babel preset
    .eslintrc  --> recommended + es6 env


Webpack takes your sources as input and make a build WITH developpement additions. So **Don't use it direcly for production**

The html plugin let you specify your index.html template ( in src folder ) . By this way, you don't have to worry about your dependencies and you can have fun without waiting

```
npm i *whatever*
```

```
//In a .js file
import {something} from "whatever"
```


It uses webpack-dev-server with live-reload enabled by default.

To run the dev server : 
### `npm run dev`

##Use It
It can be easily added in your project with git
```
mkdir myproject && cd myproject
git init .
git remote add boilerplate https://github.com/maxdow/minimal-webpack-boilerplate.git
git fetch boilerplate
git merge boilerplate/master
npm install
npm run dev
```

Then open your browser at localhost:3000 and edit files in src foler.