# 葛嘉嘉 · 个人简历

这是一个纯静态个人简历网页，可直接使用 GitHub Pages 发布。

## 文件结构

- `index.html`：网页主页
- `logo.jpg`：个人头像
- `初.jpg`：AI训练师初级证书
- `高.jpg`：AI训练师高级证书
- `.nojekyll`：GitHub Pages 静态部署标记

## 发布到 GitHub Pages

1. 新建一个 GitHub Repository。
2. 将以上文件全部上传到仓库根目录。
3. 打开 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，保存。
6. 等待 GitHub Actions 完成部署，即可通过 GitHub Pages 地址访问。

注意：`index.html` 已经引用 `logo.jpg`、`初.jpg`、`高.jpg`，文件名和大小写不要改，否则图片可能无法显示。
