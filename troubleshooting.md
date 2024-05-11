# 环境部署问题

## 开发环境

1. 使用 `node16`，更高的版本会出现问题。
2. `npm i` 时提示下面的报错，改成 `npm i --legacy-peer-deps`

```
npm ERR! While resolving: yudao-ui-admin@2.1.0-snapshot
npm ERR! Found: eslint@7.32.0
npm ERR! node_modules/eslint
npm ERR!   dev eslint@"^7.15.0" from the root project
```