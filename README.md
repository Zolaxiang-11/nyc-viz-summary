# 可视化汇总页（独立部署版）

这个文件夹已经是可独立部署的静态站点，包含：

- 汇总入口：`index.html`
- 4 个子图资源：`apps/` 下各子目录

## 本地预览

在当前文件夹启动静态服务后，打开：

- `http://localhost:8770/viz-summary-github-pages/index.html`（如果服务根目录是项目根目录）

## GitHub Pages 发布

1. 把 `viz-summary-github-pages` 整个文件夹提交到仓库（建议放在仓库根目录）。
2. 在 GitHub 仓库设置中开启 Pages：
   - Source: `Deploy from a branch`
   - Branch: 选择你的分支（如 `main`）和目录（`/root` 或 `/docs`）
3. 若选择 `/root`，访问链接通常是：
   - `https://<你的用户名>.github.io/<仓库名>/viz-summary-github-pages/`
4. 若你把该文件夹改名为 `docs` 并选择 `/docs`，访问链接通常是：
   - `https://<你的用户名>.github.io/<仓库名>/`

