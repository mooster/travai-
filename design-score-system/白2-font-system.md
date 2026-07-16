# 白2 字体系统

## 字体角色

### 1. Display 大标题

- 字体：`Avenir Next`
- 回退：`Trebuchet MS` -> `Travai Sans`
- 字号：`48px - 64px`
- 字重：`500`
- 行高：`1.08`
- 用途：`Serious and intelligent`

### 2. Brand 品牌副标题

- 字体：`Travai Sans`
- 字号：`16px`
- 字重：`700`
- 行高：`1.25`
- 用途：`认真规划 · 尽兴旅游`

### 3. Body 正文

- 字体：`Travai Sans`
- 中文回退：`Noto Sans SC` -> `PingFang SC`
- 字号：`15px`
- 行高：`1.62`

### 4. UI 界面文字

- 字号：`13px`
- 字重：`600 - 700`
- 行高：`1.35`
- 用途：按钮、提示标签、状态文字

### 5. Sidebar 侧栏

- 中文导航：约 `14.5px`
- 英文辅助文字：`15px`
- 历史对话：`14.5px`
- 当前选中：Logo 主绿色

## 字距规则

- 全站 `letter-spacing: 0`
- 使用正常字体 kerning
- 不额外拉开英文字母

## 本地字体文件

- `Travai Sans`：`assets/fonts/Inter-Variable.ttf`
- `Travai Display`：`assets/fonts/DMSerifDisplay-Regular.ttf`

## 设计逻辑

```text
Logo：有情绪
Avenir Next 大标题：温和、现代、有品牌感
Travai Sans 正文：清晰、可靠、工具化
13px UI：紧凑、易扫描
```

大标题当前使用：

```css
font-family: "Avenir Next", "Trebuchet MS", var(--sans);
```

## Logo 与品牌副标题尺寸

### Logo

- 实际显示宽度：`246px`
- 图片比例：`980 × 770`
- 按比例显示高度：约 `193px`
- Logo 容器：`250px × 205px`
- 水平居中
- 顶部位置：`0`

### 品牌副标题

文案：`认真规划 · 尽兴旅游`

- 字号：`16px`
- 字重：`700`
- 行高：`1.25`
- 实际行高：约 `20px`
- 容器宽度：`250px`
- 居中对齐
- 字距：`0`
