## 目录结构

```shell
├── build # 构建相关脚本
├── mock # 模拟数据
├── public # 静态资源
├── src # 项目代码
│   ├── api #请求相关
│   ├── assets # 静态资源
│   ├── components # 组件
│   ├── design  # 样式
│   ├── enums # 常量，枚举
│   ├── hooks # hooks
│   ├── logics # 逻辑相关
│   ├── layouts # 布局
│   ├── main.ts # 入口文件
│   ├── router #路由，菜单等
│   ├── locale #多语言文件
│   ├── settings # 配置文件
│   ├── plugins # 插件
│   ├── store # vuex
│   ├── utils # 工具类
│   └── views # 页面
└── types # 类型定义
```

### 默认基础路由

- `/` 会重定向至 `BASE_HOME` (默认值为： /dashboard)
- `/login` 登录页
- `/main-out` 主页之外的页 `(无用)`
- `/redirect/:path(.*)` 用于重定向 `(暂未看到用处)`
