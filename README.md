# eslint test project
``` bash
# 添加生成一个package.json，方便使用eslint的standard校验规则
npm init

# 安装依赖包
npm install eslint eslint-plugin-standard eslint-plugin-promise eslint-config-standard --save-dev

# 生成eslint配置文件.eslintrc.js (前提是全局安装了eslint `npm i eslint -g`)
eslint --init
```