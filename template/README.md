# vue-multiple-pages

**A modern Vue.js multiple pages cli which uses Vue 2, Webpack3, and Element-UI**

## Features

1. [Vue2](https://github.com/vuejs/vue)
2. [Webpack3](https://github.com/webpack/webpack)
3. [Postcss](https://github.com/postcss/postcss)([autoprefixer](https://github.com/postcss/autoprefixer) default)
4. [Less](http://lesscss.org/)
5. [Sass](https://github.com/webpack-contrib/sass-loader)

## Get Started

### [vue-cli](https://github.com/vuejs/vue-cli)

#### Init Project

``` bash
$ npm install -g vue-cli
$ vue init kebichishaobing/vue-multiplepages-webpack new-project
$ cd new-project
$ npm install
```

## change to multiple pages main commit
https://github.com/kebichishaobing/vue-multiplepages-webpack/commit/9a2abd8306b0114d4f5e7a07a6de53fb354fc7db

#### Dev

```bash
# serve with hot reload at localhost:8080
$ npm run dev
```

visit [http://localhost:8080/index.html](http://localhost:8080/index.html)

visit [http://localhost:8080/chat/index.html](http://localhost:8080/chat/index.html)

visit [http://localhost:8080/chat/index2.html](http://localhost:8080/chat/index2.html)

visit [http://localhost:8080/goodbye/subfolder/index.html](http://localhost:8080/goodbye/subfolder/index.html)

#### Build

```bash
$ npm run build

find bundles in dist/
```



## Root Folder Structure

```bash
├── src  # main folder
│   ├── assets  # common assets folder
│   │   └── logo.png 
│   ├── components # common components folder
│   │   └── Hello.vue
│   └── pages 
│       ├── index 
│       │   ├── App.vue
│       │   └── main.js
│       ├── chat  
│       │   ├── index 
│       │   │   ├── App.vue
│       │   │   ├── main.js  
│       │   └── index2 
│       │       ├── App.vue
│       │       ├── main.js  
│       ├── goodbye  
│       │   └── subfolder 
│       │       └── index
│       │             ├── App.vue
│       │             └── main.js
├── LICENSE
├── .babelrc          # babel config (es2015 default)
├── .eslintrc.js      # eslint config (eslint-config-vue default)
├── server.js         # port 2333
├── package.json
├── webpack.config.js
└── README.md
```

## License

MIT
