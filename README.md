# 利佛摩尔交易理论网站

一个静态中文网站，介绍杰西·利佛摩尔的生平、交易事迹与核心交易策略。

## 本地运行

```bash
python3 -m http.server 8000
```

访问：`http://127.0.0.1:8000/index.html`

## 一键部署

### 1) GitHub Pages
仓库已包含工作流：`.github/workflows/deploy-pages.yml`。

- 推送到 `main` 分支后会自动部署。
- 站点文件位于仓库根目录（`index.html`、`styles.css`）。

### 2) Vercel
仓库已包含 `vercel.json`，可直接导入仓库部署。

- Framework Preset 选 `Other`（或保持自动识别）。
- Build Command 留空。
- Output Directory 留空。

## 免责声明
仅供教育研究，不构成投资建议。
