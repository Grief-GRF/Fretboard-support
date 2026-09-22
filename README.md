# Fretboard 支持网站

此目录是无需构建步骤的 GitHub Pages 静态网站，并包含 GitHub Actions 发布工作流。

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库，例如 `fretboard-support`。
2. 将**本目录中的全部内容**上传到新仓库根目录；请保留隐藏的 `.github/workflows/deploy-pages.yml` 和 `.nojekyll` 文件。
3. 在仓库的 **Settings → Pages** 中，将 **Source** 设为 **GitHub Actions**。
4. 推送到 `main` 分支后，工作流会自动发布。完成后，GitHub Pages 设置或 Actions 的部署记录会显示公开网址。
5. 将该公开网址（末尾带 `/`）填入 App Store Connect 的“技术支持网址”，并将该网址加上 `privacy.html` 填入“隐私政策网址”。

联系邮箱目前为 `1074948869@qq.com`。如需改用专用支持邮箱，请同时更新 `index.html` 和 `privacy.html` 中的 `mailto:` 链接及可见邮箱文字。
