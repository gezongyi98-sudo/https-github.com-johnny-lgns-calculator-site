# LGNS 复投测算器

这是一个纯静态网站，入口文件是 `index.html`。

## 分享方式

### 直接发送

把整个 `lgns-calculator-site` 文件夹发给别人，对方双击 `index.html` 即可打开。

### 发布成在线网站

可以把这个文件夹上传到任意静态网站托管平台：

- Netlify
- Vercel
- GitHub Pages
- Cloudflare Pages

上传后，平台会自动把 `index.html` 作为首页。

## 说明

- DAI 按美元稳定币处理：`1 DAI = 1 USD`
- LGNS 枚数 = `DAI 金额 ÷ LGNS 币价`
- USD/CNY 汇率按钮会尝试联网获取实时汇率；如果获取失败，可以手动输入汇率。

