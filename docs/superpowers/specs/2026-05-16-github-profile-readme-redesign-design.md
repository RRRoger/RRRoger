# RRRoger GitHub Profile README Redesign

## 目标
将 GitHub 个人主页 README 重新设计为「科技未来感」风格，展示个人品牌、技术栈和动态元素。

## 配色方案
暗色底 + 青蓝(#00d4ff) → 紫(#7b2ff7) → 品红(#ff2d95) 渐变贯穿全页。

## 页面结构

从上到下的布局：

1. **自我介绍区**
   - `readme-typing-svg` 打字机效果轮播 tagline
   - 手写随性有趣的个人介绍文案
   - 文案内容：「一只在全栈和 AI 之间反复横跳的开发者。写 Python 调模型，用 Java 写后端，拿 Node.js 搓工具。偶尔在 GitHub 上留下一些能跑的代码。沉迷于让机器变聪明的路上 🚀」

2. **渐变动画分割线** — 纯 SVG inline，青蓝→紫→品红渐变

3. **GitHub 统计卡片** — `github-readme-stats` (暗色主题)
   - Stats 卡片
   - Top Languages 卡片
   - Streak Stats 卡片

4. **渐变动画分割线**

5. **Tech Stack** — `skill-icons` (dark theme)
   - Python, Java, Node.js, React/前端, AI/ML, Docker 等

6. **渐变动画分割线**

7. **GitHub Trophies** — `github-profile-trophy` (dark 主题)

8. **渐变动画分割线**

9. **底部信息**
   - 位置：Shanghai
   - 爱好：📷 🏊 🎬 🎵
   - Visitor Counter Badge

## 使用的服务/工具

| 元素 | 工具 |
|------|------|
| 打字机 tagline | readme-typing-svg |
| GitHub Stats | github-readme-stats (theme: radical 或自定义暗色) |
| Top Languages | github-readme-stats |
| Streak Stats | github-readme-streak-stats |
| Tech Stack 图标 | skill-icons (dark theme) |
| GitHub Trophies | github-profile-trophy (dark 主题) |
| 分割线 | 纯 SVG inline |
| Visitor Counter | visitor-badge |

## 约束
- 动效只能通过 SVG/SVG-animation 或外部服务生成，GitHub 不支持 CSS animation/JS
- 避免过多 GIF 导致页面加载卡顿
- 保持 README 在合理长度，避免过于冗长
