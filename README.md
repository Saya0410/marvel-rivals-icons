# 图标资源说明

## 目录结构

```
icons/
├── logo.png              ← MARVEL RIVALS 游戏 logo
├── black-cat.png         ← 英雄头像（文件名用英文小写，空格用-连接）
├── white-fox.png
├── luna-snow.png
└── ...
```

通用话题（整体环境、阵容、平衡等）使用 emoji 图标，不需要图片文件。

## 图片规格建议

- **logo.png**：宽度 120-160px，透明背景 PNG
- **英雄头像**：正方形，建议 96x96px 或 128x128px，PNG 格式

## HTML 引用方式

```html
<!-- 英雄头像 -->
<img src="icons/black-cat.png" />

<!-- logo -->
<img src="icons/logo.png" />

<!-- 通用话题直接用 emoji -->
<div class="card-icon">🌐</div>
```