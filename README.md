# 刘洋宾 · 交互式个人简历

智能车辆工程 2026 级本科生的个人简历 / 作品集网页。

## ✨ 特性

- 🎨 深色科技风（Slate-950 + 青蓝/靛蓝光斑 + 毛玻璃卡片）
- 🧩 Tailwind CSS + Lucide Icons + Plus Jakarta Sans
- ✈️ 内嵌可玩「飞机大战」（Canvas，键盘 / 鼠标 / 触屏）
- 🐍 内嵌可玩「贪吃蛇」（吃食物加速，实时计分）
- 📊 亮点指标看板 + 成长时间线 + 技能进度条 + 证书灯箱
- 🚙 内嵌可旋转「电动概念车」3D 模型（model-viewer，拖动旋转 / 滚轮缩放）
- 📋 复制邮箱剪贴板 + 底部毛玻璃 Toast 提示
- 📱 响应式布局，支持一键导出 PDF
- 🚀 滚动视差、入场动画等交互细节

## 🛠️ 技术栈

Tailwind CSS (Play CDN) + Lucide Icons + Vanilla-Tilt.js + Google model-viewer + 原生 JavaScript，单文件实现。

## 📂 目录结构

```
├── index.html              # 简历主文件（含全部样式与脚本）
├── car_model.glb          # 电动概念车 3D 模型（GLB，约 52MB）
├── car_model_preview.png  # 3D 模型预览图
├── cert-ai-trainer.png    # 人工智能训练师（初级）证书
├── cert-prompt-engineer.jpg  # Prompt 工程师认证
├── cert-fine-tuning-engineer.jpg  # 微调工程师认证
└── tank-battle.html       # 坦克大战小游戏（iframe 嵌入）
```

> 说明：3D 模型由 AI 文生 3D 生成（Blue 金属电动概念跑车），用于展示建模/三维方向兴趣，非工程渲染成品。
> 注意：本地双击 `index.html`（`file://`）时浏览器禁止跨域加载 `.glb`，3D 模型需通过 HTTP 访问（如部署到 GitHub Pages，或用本地服务器 `python -m http.server` 打开）。

## 📄 License

MIT
