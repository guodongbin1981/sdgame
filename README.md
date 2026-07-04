# Sudoku

一个纯静态的数独网页，单文件实现，主文件是 `index.html`。

## 功能

- 4x4、6x6、9x9、16x16
- 初级、中级、高级
- 唯一候选开关
- 已知数显示与自定义
- 保存进度
- 打印与打印历史
- 移动端自适应

## 本地使用

直接用浏览器打开 `index.html` 即可。

## 部署到 Cloudflare Pages

这是静态站点，推荐使用 GitHub + Cloudflare Pages 自动部署。

推荐配置：

- Framework preset: `None`
- Production branch: `main`
- Build command: `exit 0`
- Build output directory: `.`
- Root directory: 留空

## 文件结构

- `index.html`: 页面、样式、脚本全部在这里
- `.gitignore`: 本地调试产物忽略规则
