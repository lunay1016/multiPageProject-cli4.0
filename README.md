# project-cli4.0

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



##  多页面多系统应用
##  
##  1、思路
##  
##  使用Vue搭建多页应用。所有系统都在同一目录下。配置多入口多出口。每个系统之间可以链接。每个系统内依然采用Vue单页应用开发。
##  
##  2、组件复用性
##  
##  可以将所有的系统公共组件放到系统目录最外面，以达到组件复用。在系统内部依然将自己独立的组件封装，复用。这样可以最大限度的提高组件的复用性。
##  
##  3、路由
##  
##  每个系统单独进行路由配置
##  
##  4、数据管理
##  
##  每个系统数据仓库单独处理