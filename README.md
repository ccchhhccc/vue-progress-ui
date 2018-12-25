# 简单的进度条ui插件，第一次尝试发布npm包

# install
```js
npm i vue-progress-ui
```

# start
main.js
```js
import myProgress from 'vue-progress-ui'

Vue.use(myProgress)
```

# use
vue components
```vue
<myProgress precent="50"/>
```

# change height
vue components
```vue
<myProgress precent="50" style="height:20px;"/>
```