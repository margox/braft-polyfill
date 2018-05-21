## Braft Editor 兼容包
### 如果要在旧版浏览器中使用Braft Editor，请安装此依赖，目前可以兼容至IE10，欢迎MR

#### 兼容特性列表：
- HTML5 dataset属性

#### 安装
```bash
yarn add braft-polyfill
# 或者
npm i braft-polyfill --save
```

#### 使用
```javascript
// 在引入BraftEditor之前引入此依赖
import 'braft-polyfill'
import BraftEditor from 'braft-editor'
// ...
```

#### 目前参与者
- [nanjixiong218](https://github.com/nanjixiong218)
