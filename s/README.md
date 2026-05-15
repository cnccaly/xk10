# 网站部署说明

本目录包含你的 HTML 页面和本地轮播图：
- `login.html`
- `profile.html`
- `photo1.jpg`
- `photo2.jpg`
- `photo3.jpg`

## 部署到 GitHub Pages 的步骤

1. 准备工作
   - 确保已经设计并完成网页文件。
   - 注册 GitHub 账号并创建一个新仓库。

2. 文件上传
   - 使用 Git 客户端将所有文件提交到仓库，或者直接在 GitHub 网页界面上传。
   - 提交文件应该包括 HTML、CSS、JavaScript、图片等所有相关资源。

3. 设置托管服务
   - 进入仓库的 `Settings` > `Pages`。
   - 选择发布来源，例如 `main` 分支下的 `/root` 或 `gh-pages` 分支。
   - 如果需要自定义域名，可在该页面设置 `Custom domain`。

4. 等待构建和部署
   - GitHub Pages 会自动构建并发布网站，这通常需要几分钟。
   - 构建过程完成后，会显示网站的访问链接。

5. 访问你的网站
   - 默认链接类似 `https://username.github.io/repository-name/`。
   - 如果仓库名是 `username.github.io`，则访问根域名 `https://username.github.io/`。

6. 进行测试
   - 在不同浏览器和设备上访问网站。
   - 检查页面是否正常显示，验证所有链接、图片和交互元素是否可用。

## 本地快速测试

你也可以直接在本地打开 `login.html` 和 `profile.html` 进行预览。确保 `photo1.jpg`、`photo2.jpg`、`photo3.jpg` 与 `profile.html` 在同一目录下。
