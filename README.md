# uni-app-test

## issue

<https://github.com/uni-helper/uni-deploy/issues/2>

## 环境

- node: 18.12.0
- npm: 9.1.2

## 复现步骤

- `npm install`
- `npm run validate`

期望行为：输出 `INFO [yyyy-mm-dd HH:MM:ss.l o]: 没有配置微信小程序，跳过微信小程序操作。`

实际行为：卡住，超过 1 分钟无输出
