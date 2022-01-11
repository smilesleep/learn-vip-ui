# 快速开速

#### 安装组件库

```bash
npm i learvn-vip-ui
```

#### 引用组件库
> 在 main.js 中引用组件库

```javascript
// 全部引入
import 'learn-vip-ui/dist/css/index.css';
import MUI from 'learn-vip-ui';
Vue.use(MUI);

// 按需引入
import 'learn-vip-ui/dist/css/demo.css';
import { Demo } from 'learn-vip-ui';
Vue.use(Demo);
```