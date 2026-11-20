# 提瓦特全息闪卡馆 · Teyvat SAR Collection

收录 69 位原神五星角色手绘涂鸦典藏卡的交互式 3D 全息闪卡展示站，包含：

- 首页大厅（按 7 大元素 / 8 大地区筛选或进入全部 69 张典藏馆）
- 网格画廊 / 舞台展示双模式切换
- 低眩光 Cosmos 珠光虹彩全息 Shader、8 层金属卡边、星象罗盘全息卡背与 3D 聚光灯详情弹窗

## 目录结构

- `index.html`：面向 GitHub Pages 部署的主页面（引用 `assets/cards/` 高清原图）
- `standalone.html`：单文件离线版（已内联压缩 WebP 图资，双击即可离线打开）
- `assets/cards/`：全部 69 张角色高清涂鸦原图（`01_skirk.jpg` ~ `69_mitya.jpg`）及星象罗盘卡背（`card_back.jpg`）

## 推送到 GitHub 仓库

解压后在目录中执行：

```bash
git init
git add .
git commit -m "Initial commit: Teyvat SAR holographic card gallery (69 cards)"
git branch -M main
git remote add origin https://github.com/839194950/Genshin-website.git
git push -u origin main
```

推送完成后，在仓库的 **Settings -> Pages** 中选择 `main` 分支根目录即可直接生成在线访问地址。
