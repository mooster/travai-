# Travel AI 白底版

这是 Travai 的白色背景版本，适合作为旅行规划 AI 产品的前端原型或视觉交付包。

本仓库只包含白底版。蓝灰底版会单独整理、单独发布，不与本版本混用。

## 快速使用

### 直接打开

双击 `白2.html` 即可在浏览器中查看当前白底版页面。

- `白2.html`：当前唯一保留的白底版，包含最新布局、字体、交互、资源和动画。

### 启动本地服务

如果需要更稳定地加载本地资源，可以在项目目录执行：

```bash
python3 -m http.server 8080
```

然后打开：<http://localhost:8080>

项目不需要安装 npm、Node.js 或其他构建依赖。

## 项目结构

- `白2.html`：统一调整后的白底版页面
- `design-score-system/`：固定七维设计评分系统和白2评分记录
- `design-score-system/排版系统.md`：白底版字体、字号、行高、字距和混排基准
- `assets/`：页面图片、插画和本地字体资源
- `logo/`：Travai logo 版本
- `好看的图标-透明/`：透明黑线图标原稿
- `好看的图标-粗线条/`：粗线条插画资源
- `好看的图标-细线条/`：细线条插画资源
- `design-notes/`：视觉和图标设计说明

## 当前页面功能

- Travai 白底版主页面
- 左侧历史对话、我的行程、旅行收藏夹导航
- 搜索框聚焦状态和绿色发送按钮
- 响应式布局，支持桌面和移动端
- 本地透明黑线导航图标
- 白底视觉系统与 logo 绿色交互状态
- 右下角 100% 不透明横向铅笔视觉元素
- 标题上方卷尺线持续播放动画

## 维护说明

页面是单文件静态实现。当前唯一工作文件是 `白2.html`。

当前页面英文使用本地 `Travai Sans` 和标题用的人文无衬线字体，中文使用系统中文字体回退；Logo 图片保留原始品牌颜色。

白2当前使用：

- `logo/travai-logo-standard-980x770.png`：当前白底版使用的标准 Logo 矢量 PNG
- `logo/travai-logo-standard-display.png`：白底侧栏使用的去除画布留白显示版
- `logo/travai-logo-reversed-980x770.png`：蓝灰底版使用的反白 Logo 矢量 PNG
- `assets/pencil-horizontal-display.png`：右下角横向铅笔
- `assets/tape-line-delicate-soft-gray.png`：标题上方卷尺动画

## 版本状态

这是 2026-07-17 约 01:00 的 Travai 白底版最终归档快照。网页内的 Chiang Mai 历史对话记录已保留。
