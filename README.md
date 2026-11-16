# 初二上册·考点通（PWA）

## 文件
- index.html：学习首页与七科课程
- manifest.webmanifest：PWA 安装配置
- sw.js：缓存 App 外壳（不缓存/下载 B 站视频）
- icon.svg：桌面图标

## 使用
1. 将整个文件夹部署到支持 HTTPS 的静态网站托管服务（如 GitHub Pages、Cloudflare Pages 或 Netlify）。
2. 用 iPad Safari 打开部署后的 HTTPS 地址。
3. 点 Safari 分享按钮，选择“添加到主屏幕”。
4. 桌面图标“考点通”即可打开。

注意：直接双击 index.html 可预览页面，但不能完整安装 PWA。视频链接跳转 B 站，播放需要网络及相应平台权限。学习完成状态保存在当前浏览器本地。
