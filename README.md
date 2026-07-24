# GitHub Pages 发布

本目录已经是可直接发布的静态网站，不需要安装依赖或执行构建。

## 推荐方式

1. 在 GitHub 新建一个公开仓库。
2. 把本目录中的 `index.html` 和 `.nojekyll` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，保存。
6. 等待 GitHub 显示公开访问地址。

`index.html` 已经内嵌样式、脚本、Aivigate Logo 和咨询二维码，发布后不依赖其他文件。
