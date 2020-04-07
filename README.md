# babel-plugin-tnt

## 安装
```
npm install babel-plugin-tnt --save-dev
```
### 使用说明
```
// .babelrc
"plugins": [
    [
      "babel-plugin-tnt",
      {
        "library": "yournpm" // 支持数组["yournpm", "yournpm2"]
      }
    ],
  ]
  
// index.js
import { helloworld } from 'yournpm';

      ↓ ↓ ↓ ↓ ↓ ↓

var _helloworld = require('yournpm/lib/helloworld');
```


