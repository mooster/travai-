# Travai Design Score System

这是 Travai 白底版的设计评估系统。它把今天讨论过的 Skills 转成一套可以重复使用的审美、字体、交互和实现评分标准。

## 评分对象

- `白1.html`：原始白底版
- `白2.html`：持续迭代中的白底版

评分系统只评估页面表现，不自动修改页面，也不会删除页面内容。

## 固定七维评分

以后每次说“打分”，固定按下面 7 项分别评分，满分均为 10 分：

1. **视觉方向与品牌识别**：页面有没有清晰、独特、适合 Travai 的视觉主题。
2. **字体与排版**：字体性格、字号阶梯、字重、行高、字距和中英文混排。
3. **布局与空间节奏**：主次关系、留白、对齐、密度和响应式布局。
4. **颜色与组件一致性**：品牌色、对比度、按钮、圆角、边框和状态是否统一。
5. **UI 友好度与交互状态**：用户是否知道下一步做什么，以及 hover、focus、active、loading、success 是否完整。
6. **可访问性与跨设备体验**：键盘、焦点、对比度、语义、移动端和不同屏幕尺寸。
7. **工程完成度与可信度**：代码结构、性能、资源加载、错误反馈、AI 透明度和可维护性。

总分公式：

```text
总分 = (1 + 2 + 3 + 4 + 5 + 6 + 7) / 7
```

## 核心参考 Skills

本系统采用三个最高相关度的核心 Skill 作为总评审基准：

1. `anthropics/skills` 的 `frontend-design`：负责审美方向、字体、色彩、空间和反模板化设计。
2. `nextlevelbuilder/ui-ux-pro-max-skill`：负责设计系统、行业适配、字体配对、颜色、组件状态和响应式检查。
3. `microsoft/skills` 的 `frontend-design-review`：负责任务完成路径、设计系统合规、可访问性、响应式和可信交互。

这三者分别覆盖“好看”“好用”“能稳定交付”。Anthropic 的 Skill 强调独特且生产级的前端视觉，UI UX Pro Max 提供设计系统生成和预交付检查，Microsoft 的 Review Skill 则用 Frictionless、Quality Craft、Trustworthy 三个支柱审查页面。citeturn8search1turn8search0turn8search2

## 维度与 Skills 对照

| 维度 | 主要参考 | 辅助参考 |
|---|---|---|
| 1. 视觉方向与品牌识别 | Anthropic frontend-design | UI UX Pro Max、Microsoft review |
| 2. 字体与排版 | UI UX Pro Max typography | Anthropic frontend-design、web-typography |
| 3. 布局与空间节奏 | Anthropic frontend-design | UI UX Pro Max、Microsoft review |
| 4. 颜色与组件一致性 | UI UX Pro Max design system | Anthropic frontend-design、Microsoft review |
| 5. UI 友好度与交互状态 | Microsoft frontend-design-review | UI UX Pro Max、Agency Frontend |
| 6. 可访问性与跨设备体验 | Microsoft frontend-design-review | UI UX Pro Max、ECC verification |
| 7. 工程完成度与可信度 | ECC frontend patterns / verification | Agency Frontend、Microsoft review |

### 1. 视觉方向

- `design-taste-frontend`
- `frontend-design`
- `high-end-visual-design`

关注页面是否有明确设计方向、品牌识别、视觉克制、空间节奏和独特记忆点。

### 2. 字体与排版

- `web-typography`
- `frontend-design` typography principles
- `ui-ux-pro-max-skill` typography system

关注字体性格、字体配对、字号阶梯、行高、字距、中英文混排和响应式阅读。

### 3. 产品与工程质量

- `ECC` frontend patterns / verification
- `agency-agents` Frontend Developer / UI Designer
- `microsoft/skills` frontend design review principles

关注交互反馈、可访问性、响应式、状态完整性、性能和后续维护成本。

## 通过线

- `8.0 - 10.0`：可作为对外展示版本
- `7.0 - 7.9`：方向成立，需要细节打磨
- `6.0 - 6.9`：可用，但仍有明显设计债务
- `低于 6.0`：需要重新梳理结构和设计系统

## 评分原则

1. 内容不因为评分被删除；只评估层次、表达和使用方式。
2. 视觉装饰不能抵消任务路径上的问题。
3. 颜色、字体和圆角必须作为系统整体评分，不能只看单个组件。
4. 交互评分必须看 hover、focus、active、empty 和提交后的状态。
5. 每次评分都记录日期、版本、证据和下一步动作。
