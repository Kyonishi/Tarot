# 素材来源记录

当前牌面图片使用公开的 Rider–Waite–Smith 牌图镜像：

- 仓库：https://github.com/sixseeds/tarot-api
- 图片目录：https://github.com/sixseeds/tarot-api/tree/main/cards
- 命名：`ar00`–`ar21` 为大阿卡那；`wa`、`cu`、`sw`、`pe` 分别为权杖、圣杯、宝剑、星币。
- 牌背：`back.jpg`

网页运行时使用 `cards-webp/` 中的 WebP 图片，不依赖第三方 CDN。图片由原始 `cards/` JPG 转换，最大宽度 640px、WebP quality 80；79 张资源合计约 14 MB，相比原 JPG 约 70 MB 减少 80%。原始 JPG 保留为素材源。

原始 Rider–Waite–Smith 插画由 Pamela Colman Smith 绘制，最初于 1909 年出版。不同地区的公版规则可能不同，正式公开发布前应按目标地区复核。
