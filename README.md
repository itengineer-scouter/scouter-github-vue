# sample_vue_project

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

### docker build
docker build -t scouter_github_vue_base:latest --build-arg repository=`echo $REPO_NAME_GITHUB_VUE` .
