# YOWO Interactive Book

这是可直接部署到 GitHub Pages 的静态网页包，无需 Node.js、npm 或构建命令。

## 文件结构

- `index.html`：网页结构与导航内容
- `app.js`：3D 翻书、视差和页面交互逻辑
- `styles.css`：页面样式与响应式规则
- `.nojekyll`：避免 GitHub Pages 使用 Jekyll 处理静态资源
- `assets/images/`：PNG、WebP 等图片资源
- `assets/svg/`：独立 SVG 资源
- `assets/fonts/`：本地字体
- `assets/models/`：3D GLB 模型

## 部署到 GitHub Pages

1. 新建一个 GitHub 仓库。
2. 将本目录中的所有文件和文件夹上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 选择 `main` 分支和 `/ (root)` 目录，然后保存。
6. 等待 GitHub Pages 完成部署后打开生成的网址。

所有站内资源均使用相对路径，可部署在 GitHub Pages 的项目子目录中。
