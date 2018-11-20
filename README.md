# test-app

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

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Run your unit tests
```
npm run test:unit
```

### Build using Docker
docker build -t nginx-vue/dockerize-vuejs-app .

### Run using docker
docker run -it -p 8088:80 --rm --name dockerize-vuejs-app-1 nginx-vue/dockerize-vuejs-app