# desk-app

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

### electron搭建
1、 配置npm文件
```
npm config edit
# 将以下内容添加到文件末尾
ELECTRON_BUILDER_BINARIES_MIRROR=http://npm.taobao.org/mirrors/electron-builder-binaries/
electron_mirror=http://npm.taobao.org/mirrors/electron/
```

2、 创建项目
```
# 安装vue-cli
npm install -g @vue/cli
# 创建项目
vue create projectName
# 添加electron-builder
vue add electron-builder
# 安装依赖
npm i
```