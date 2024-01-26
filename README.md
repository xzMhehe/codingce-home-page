[![Website](https://img.shields.io/website-up-down-green-red/http/i.dmego.me.svg)](http://i.dmego.me/)
[![License](https://img.shields.io/github/license/dmego/home.github.io.svg)](/LICENSE)
[![Say Thanks](https://img.shields.io/badge/Say-Thanks!-1EAEDB.svg)](https://saythanks.io/to/dmego)

### 个人主页

>这是我的个人主页

>衍生自 [Vno](https://github.com/onevcat/vno-jekyll) Jekyll 主题

>页面部分加载效果借鉴于 [Mno](https://github.com/mcc108/mno) Ghost 主题

>借鉴了[北岛向南的小屋](https://javef.github.io/)的头像样式

### 效果图

>静态图

![主页PNG](https://raw.githubusercontent.com/xzMhehe/StaticFile_CDN/main/static/img/mo/20240126114805.png)

### 注

- 访问地址：[个人主页](https://z.codingce.com.cn/)
- 使用了 [一言](http://hitokoto.cn/) 的 API 服务
- ~~使用了 [Bing 壁纸 API](https://github.com/xCss/bing/) 服务~~
- ~~使用了 [Yahoo Query Language (YQL)](https://developer.yahoo.com/yql/) 来解决获取 Bing 壁纸跨域问题~~
- ~~原先 YQL 服务将被淘汰，现改用 [JsonBird](https://bird.ioliu.cn/)~~
- 使用 GitHub Action 来获取 Bing 壁纸，使用 JSONP 获取 Bing 壁纸 URL 文件

### GitHub Action 补充说明

- 利用 `Github Action` 提交代码需要一个 `GitHub API` 令牌, 可以在 [Create Tokens](https://github.com/settings/tokens) 这个地址，点击 `Generate new token` 按钮来创建
    - `Expiration` 过期时间设置为 `not expiration`
    - `Select scopes` 勾选 `repo`
    - 点击 `Generate Token` 生成
- 在仓库的 `Settings` ——>`Secrets` 功能栏中，点击 `new repository secrets` 按钮
    -  在 `Name` 框中填写 `GH_TOKEN`
    - 在 `Value` 栏中填写第一步生成的 `token` 值

### 更新时间

>2024-01-26
