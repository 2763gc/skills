# Skills Catalog

AI 助手在使用 skills 前，先读此文件了解可用技能列表。
根据用户需求匹配最合适的 skill，然后加载对应路径下的 SKILL.md。

## 使用流程

1. 读取本文件，了解所有可用 skill
2. 根据用户意图匹配 skill（关键词、描述）
3. 加载匹配的 `<skill-name>/SKILL.md`
4. 按 SKILL.md 中的指令执行

---

## 可用 Skills

### superdesign

- **路径:** `superdesign/SKILL.md`
- **描述:** 前端页面设计辅助。提供结构化设计流程：ASCII 线框图布局 → 主题设计（配色/字体/间距）→ 动画设计 → 代码实现。内置多种主题模式（暗黑、新粗野、毛玻璃），遵循 Tailwind + Flowbite + Lucide 技术栈，强调响应式和无障碍设计。
- **适用场景:** Landing page、仪表盘、UI 组件、原型设计、前端页面快速搭建
- **关键词:** frontend, design, UI, landing page, 组件, 布局, Tailwind, 响应式, 暗黑模式, 动画

---

### ui-ux-pro-max

- **路径:** `ui-ux-pro-max/SKILL.md`
- **描述:** 专业的 UI/UX 设计辅助。生成设计系统、组件代码、配色方案、排版规范、响应式布局。支持多种技术栈（React、Vue、Next.js、Nuxt、Flutter、SwiftUI、Jetpack Compose 等）。
- **适用场景:** 前端界面设计、设计系统搭建、组件开发、landing page 设计、移动端 UI
- **关键词:** UI, UX, 设计, 前端, 组件, 布局, 配色, 排版, 响应式, design system, React, Vue, Tailwind

---

## 添加新 Skill

1. 在仓库根目录创建 `<skill-name>/SKILL.md`
2. 在本文件中添加条目，填写描述、适用场景、关键词
3. 提交并推送
