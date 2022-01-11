# learn-vip-ui 组件库

### 快速开始

#### 1.安装组件库

```bash
npm i learn-vip-ui
```

#### 2.引用组件库
```javascript
// 全部引入
import 'learn-vip-ui/dist/css/index.css';
import MUI from 'learn-vip-ui';
Vue.use(MUI);

// 按需引用
import 'learn-vip-ui/dist/css/demo/css';
import { Demo } from 'learn-vip-ui';
Vue.use(Demo);
```