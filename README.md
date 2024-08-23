# @willin/biome-config

A most commonly used Biome configuration.

[![github](https://img.shields.io/github/followers/willin.svg?style=social&label=Followers)](https://github.com/willin) [![npm](https://img.shields.io/npm/v/@willin/biome-config.svg)](https://npmjs.org/package/@willin/biome-config) [![npm](https://img.shields.io/npm/dm/@willin/biome-config.svg)](https://npmjs.org/package/@willin/biome-config) [![npm](https://img.shields.io/npm/dt/@willin/biome-config.svg)](https://npmjs.org/package/@willin/biome-config)  

## 使用说明 Useage

Run:

```bash
bun add -D @biomejs/biome @willin/biome-config
```

Add this line to your `biome.jsonc`:

```json
{
  "$schema": "https://biomejs.dev/schemas/1.8.3/schema.json",
  "extends": ["@willin/biome-config"],
}
```

Then add this line to your `package.json`:

```json
{
  "scripts": {
    "check": "biome check --write --no-errors-on-unmatched --unsafe ."
  }
}
```


## 赞助 Sponsor

如果您对本项目感兴趣，可以通过以下方式支持我：

- 关注我的 Github 账号：[@willin](https://github.com/willin) [![github](https://img.shields.io/github/followers/willin.svg?style=social&label=Followers)](https://github.com/willin)
- 参与 [爱发电](https://afdian.com/@willin) 计划
- 支付宝或微信[扫码打赏](https://user-images.githubusercontent.com/1890238/89126156-0f3eeb80-d516-11ea-9046-5a3a5d59b86b.png)

Donation ways:

- Github: <https://github.com/sponsors/willin>
- Paypal: <https://paypal.me/willinwang>
- Alipay or Wechat Pay: [QRCode](https://user-images.githubusercontent.com/1890238/89126156-0f3eeb80-d516-11ea-9046-5a3a5d59b86b.png)

## 许可证 License

MIT