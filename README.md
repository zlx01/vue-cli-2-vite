# Migrate from Vue CLI to Vite

Reference: [blog](https://vueschool.io/articles/vuejs-tutorials/how-to-migrate-from-vue-cli-to-vite/)

## 实测注意

* 依赖项 "vue-template-compiler": "^2.6.11" 不能删除。
* eslint的配置如果写在 `package.json`， 要移至 `.eslintrc`

---

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
