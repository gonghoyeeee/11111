# CycleLearn（GitHub Pages）

这个仓库已经配置好 GitHub Pages 自动部署：

- 当 `main` 分支有新提交时，会自动发布站点。
- 首次使用时，请在仓库设置中启用 **Pages + GitHub Actions**。

## 一次性设置步骤

1. 把代码推送到 GitHub 仓库。
2. 打开仓库 **Settings → Pages**。
3. 在 **Build and deployment** 里选择 **Source: GitHub Actions**。
4. 提交到 `main` 后，等待 `Deploy static site to GitHub Pages` 工作流完成。

完成后，你的网站地址通常是：

- `https://<你的GitHub用户名>.github.io/<仓库名>/`

如果仓库名不是根路径（例如 `mahjong-luck`），访问时要带上仓库名路径。
