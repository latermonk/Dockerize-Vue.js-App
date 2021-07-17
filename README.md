# dockerize-vuejs-app

https://vuejs.org/v2/cookbook/dockerize-vuejs-app.html


##  镜像编译 &  运行

打包

```
docker build -t vuejs-cookbook/dockerize-vuejs-app .
```

运行

```
docker run -it -p 8080:8080 --rm --name dockerize-vuejs-app-1 vuejs-cookbook/dockerize-vuejs-app

```







---
## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
