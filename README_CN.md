# UI UX Pro Max

<p align="center">
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/releases"><img src="https://img.shields.io/github/v/release/nextlevelbuilder/ui-ux-pro-max-skill?style=for-the-badge&color=blue" alt="GitHub Release"></a>
  <img src="https://img.shields.io/badge/reasoning_rules-100-green?style=for-the-badge" alt="100 Reasoning Rules">
  <img src="https://img.shields.io/badge/UI_styles-57-purple?style=for-the-badge" alt="57 UI Styles">
  <img src="https://img.shields.io/badge/python-3.x-yellow?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.x">
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/blob/main/LICENSE"><img src="https://img.shields.io/github/license/nextlevelbuilder/ui-ux-pro-max-skill?style=for-the-badge&color=green" alt="License"></a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/uipro-cli"><img src="https://img.shields.io/npm/v/uipro-cli?style=flat-square&logo=npm&label=CLI" alt="npm"></a>
  <a href="https://www.npmjs.com/package/uipro-cli"><img src="https://img.shields.io/npm/dm/uipro-cli?style=flat-square&label=downloads" alt="npm downloads"></a>
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/stargazers"><img src="https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat-square&logo=github" alt="GitHub stars"></a>
  <a href="https://paypal.me/uiuxpromax"><img src="https://img.shields.io/badge/PayPal-Support%20Development-00457C?style=flat-square&logo=paypal&logoColor=white" alt="PayPal"></a>
</p>

一个 AI 技能，为多个平台和框架构建专业 UI/UX 提供设计智能。

<p align="center">
  <img src="screenshots/website.png" alt="UI UX Pro Max" width="800">
</p>

<p align="center">
  <b>如果你觉得这个项目有用，请考虑支持我们：</b><br><br>
  <a href="https://paypal.me/uiuxpromax"><img src="https://img.shields.io/badge/PayPal-Donate-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal Donate"></a>
</p>

## v2.0 新特性

### 智能设计系统生成

v2.0 的旗舰功能是**设计系统生成器** - 一个 AI 驱动的推理引擎，能够分析你的项目需求并在几秒钟内生成完整的、定制化的设计系统。

```
+----------------------------------------------------------------------------------------+
|  目标：Serenity Spa - 推荐设计系统                                                      |
+----------------------------------------------------------------------------------------+
|                                                                                        |
|  模式：Hero-Centric + 社会证明                                                         |
|     转化：情感驱动 + 信任元素                                                          |
|     CTA：首屏上方，在客户评价后重复                                                     |
|     板块：                                                                            |
|       1. 主视觉区 (Hero)                                                               |
|       2. 服务介绍                                                                     |
|       3. 客户评价                                                                     |
|       4. 预约预订                                                                     |
|       5. 联系方式                                                                     |
|                                                                                        |
|  风格：Soft UI Evolution                                                              |
|     关键词：柔和阴影、微妙深度、平静、高级感、有机形状                                  |
|     最佳适用：健康、美容、生活方式品牌、高端服务                                       |
|     性能：优秀 | 无障碍：WCAG AA                                                       |
|                                                                                        |
|  配色方案：                                                                            |
|     主色：    #E8B4B8 (柔和粉色)                                                      |
|     辅色：    #A8D5BA (鼠尾草绿)                                                      |
|     CTA：      #D4AF37 (金色)                                                         |
|     背景：    #FFF5F5 (暖白色)                                                       |
|     文字：    #2D3436 (炭灰色)                                                       |
|     备注：平静的配色方案，金色点缀营造奢华感                                           |
|                                                                                        |
|  字体：Cormorant Garamond / Montserrat                                                |
|     氛围：优雅、平静、精致                                                            |
|     最佳适用：奢侈品牌、健康、美容、编辑设计                                           |
|     Google Fonts：https://fonts.google.com/share?selection.family=...                 |
|                                                                                        |
|  关键效果：                                                                            |
|     柔和阴影 + 平滑过渡 (200-300ms) + 温和的悬停状态                                    |
|                                                                                        |
|  避免使用（反模式）：                                                                  |
|     明亮的霓虹色 + 刺眼的动画 + 深色模式 + AI 紫色/粉色渐变                            |
|                                                                                        |
|  交付前检查清单：                                                                      |
|     [ ] 不使用表情符号作为图标（使用 SVG：Heroicons/Lucide）                           |
|     [ ] 所有可点击元素添加 cursor-pointer                                              |
|     [ ] 悬停状态使用平滑过渡 (150-300ms)                                              |
|     [ ] 浅色模式：文字对比度至少 4.5:1                                                 |
|     [ ] 键盘导航时焦点状态可见                                                        |
|     [ ] 尊重 prefers-reduced-motion 设置                                              |
|     [ ] 响应式：375px、768px、1024px、1440px                                           |
|                                                                                        |
+----------------------------------------------------------------------------------------+
```

### 设计系统生成工作原理

```
┌─────────────────────────────────────────────────────────────────┐
│  1. 用户请求                                                    │
│     "为我的美容水疗中心构建一个着陆页"                          │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  2. 多领域搜索（5 个并行搜索）                                   │
│     • 产品类型匹配（100 个类别）                                │
│     • 风格推荐（57 种风格）                                     │
│     • 配色方案选择（95 个调色板）                               │
│     • 着陆页模式（24 种模式）                                   │
│     • 字体搭配（56 种字体组合）                                 │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  3. 推理引擎                                                    │
│     • 匹配产品 → UI 类别规则                                    │
│     • 应用风格优先级（BM25 排名）                               │
│     • 过滤行业反模式                                            │
│     • 处理决策规则（JSON 条件）                                 │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  4. 完整设计系统输出                                            │
│     模式 + 风格 + 配色 + 字体 + 效果                            │
│     + 避免使用的反模式 + 交付前检查清单                         │
└─────────────────────────────────────────────────────────────────┘
```

### 100 条行业特定推理规则

推理引擎包含针对以下领域的专业规则：

| 类别 | 示例 |
|----------|----------|
| **科技与 SaaS** | SaaS、微型 SaaS、B2B 企业、开发者工具、AI/聊天机器人平台 |
| **金融** | 金融科技、银行、加密货币、保险、交易仪表板 |
| **医疗健康** | 医疗诊所、药房、牙科、兽医、心理健康 |
| **电子商务** | 通用、奢侈品、市场平台、订阅盒 |
| **服务** | 美容/水疗、餐厅、酒店、法律、咨询 |
| **创意** | 作品集、代理公司、摄影、游戏、音乐流媒体 |
| **新兴技术** | Web3/NFT、空间计算、量子计算、自动驾驶系统 |

每条规则包括：
- **推荐模式** - 着陆页结构
- **风格优先级** - 最佳匹配的 UI 风格
- **配色情绪** - 行业适用的调色板
- **字体情绪** - 字体个性匹配
- **关键效果** - 动画和交互
- **反模式** - 避免使用的内容（例如，银行业避免"AI 紫色/粉色渐变"）

## 功能特性

- **57 种 UI 风格** - 玻璃拟态、粘土拟态、极简主义、野兽派、新拟态、Bento 网格、深色模式、AI 原生 UI 等
- **95 个配色方案** - 针对 SaaS、电子商务、医疗健康、金融科技、美容等行业的特定调色板
- **56 种字体搭配** - 精心策划的字体组合，包含 Google Fonts 导入
- **24 种图表类型** - 仪表板和分析的推荐图表
- **11 种技术栈** - React、Next.js、Vue、Nuxt.js、Nuxt UI、Svelte、SwiftUI、React Native、Flutter、HTML+Tailwind、shadcn/ui
- **98 条 UX 指南** - 最佳实践、反模式和无障碍规则
- **100 条推理规则** - 行业特定的设计系统生成（v2.0 新增）

## 安装

### 使用 Claude Marketplace（Claude Code）

在 Claude Code 中使用两个命令直接安装：

```
/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```

### 使用 CLI（推荐）

```bash
# 全局安装 CLI
npm install -g uipro-cli

# 进入你的项目
cd /path/to/your/project

# 为你的 AI 助手安装
uipro init --ai claude      # Claude Code
uipro init --ai cursor      # Cursor
uipro init --ai windsurf    # Windsurf
uipro init --ai antigravity # Antigravity (.agent + .shared)
uipro init --ai copilot     # GitHub Copilot
uipro init --ai kiro        # Kiro
uipro init --ai codex       # Codex CLI
uipro init --ai qoder       # Qoder
uipro init --ai roocode     # Roo Code
uipro init --ai gemini      # Gemini CLI
uipro init --ai trae        # Trae
uipro init --ai all         # 所有助手
```

### 其他 CLI 命令

```bash
uipro versions              # 列出可用版本
uipro update                # 更新到最新版本
uipro init --offline        # 跳过 GitHub 下载，使用捆绑的资源
```

### 手动安装

将相应的文件夹复制到你的项目：

| AI 助手   | 需要复制的文件夹                                                      |
| -------------- | -------------------------------------------------------------------- |
| Claude Code    | `.claude/skills/ui-ux-pro-max/`                                      |
| Cursor         | `.cursor/commands/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`       |
| Windsurf       | `.windsurf/workflows/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`    |
| Antigravity    | `.agent/workflows/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`       |
| GitHub Copilot | `.github/prompts/ui-ux-pro-max.prompt.md` + `.shared/ui-ux-pro-max/` |
| Kiro           | `.kiro/steering/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`         |
| Codex CLI      | `.codex/skills/ui-ux-pro-max/`                                       |
| Qoder          | `.qoder/skills/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`          |
| Roo Code       | `.roo/rules/ui-ux-pro-max.md` + `.shared/ui-ux-pro-max/`             |
| Gemini CLI     | `.gemini/skills/ui-ux-pro-max/` + `.shared/ui-ux-pro-max/`           |
| Trae           | `.trae/skills/ui-ux-pro-max/` + `.shared/ui-ux-pro-max/`             |

## 前置要求

需要 Python 3.x 来运行搜索脚本。

```bash
# 检查是否已安装 Python
python3 --version

# macOS
brew install python3

# Ubuntu/Debian
sudo apt update && sudo apt install python3

# Windows
winget install Python.Python.3.12
```

## 使用方法

### Claude Code

当你请求 UI/UX 工作时，技能会自动激活。只需自然地聊天：

```
为我的 SaaS 产品构建一个着陆页
```

### Cursor / Windsurf / Antigravity

使用斜杠命令来调用技能：

```
/ui-ux-pro-max 为我的 SaaS 产品构建一个着陆页
```

### Kiro

在聊天中输入 `/` 查看可用命令，然后选择 `ui-ux-pro-max`：

```
/ui-ux-pro-max 为我的 SaaS 产品构建一个着陆页
```

### GitHub Copilot

在 VS Code 中使用 Copilot，在聊天中输入 `/` 查看可用提示，然后选择 `ui-ux-pro-max`：

```
/ui-ux-pro-max 为我的 SaaS 产品构建一个着陆页
```

### Codex CLI

技能会自动激活 UI/UX 请求。你也可以显式调用它：

```
$ui-ux-pro-max 为我的 SaaS 产品构建一个着陆页
```

### Qoder

当你请求 UI/UX 工作时，技能会自动激活：

```
为我的 SaaS 产品构建一个着陆页
```

### Roo Code

当你请求 UI/UX 工作时，技能会自动激活：

```
为我的 SaaS 产品构建一个着陆页
```

### Gemini CLI

当你请求 UI/UX 工作时，技能会自动激活：

```
为我的 SaaS 产品构建一个着陆页
```

### Trae

_免责声明：Trae 技能处于测试阶段。请报告任何问题或反馈。_

要使用 Trae 技能，你需要切换到 **SOLO** 模式。如果你的请求与技能相关，将会使用技能：

```
为我的 SaaS 产品构建一个着陆页（仅前端）。
```

### 示例提示

```
为我的 SaaS 产品构建一个着陆页

为医疗健康分析创建一个仪表板

设计一个带有深色模式的作品集网站

制作一个电子商务的移动应用 UI

构建一个带有深色主题的金融科技银行应用
```

### 工作原理

1. **你提出请求** - 请求任何 UI/UX 任务（构建、设计、创建、实现、审查、修复、改进）
2. **设计系统生成** - AI 使用推理引擎自动生成完整的设计系统
3. **智能推荐** - 根据你的产品类型和需求，找到最佳匹配的风格、颜色和字体
4. **代码生成** - 使用正确的颜色、字体、间距和最佳实践实现 UI
5. **交付前检查** - 根据常见的 UI/UX 反模式进行验证

### 支持的技术栈

该技能为以下技术栈提供特定指南：

- **HTML + Tailwind**（默认）
- **React** / **Next.js** / **shadcn/ui**
- **Vue** / **Nuxt.js** / **Nuxt UI** / **Svelte**
- **SwiftUI** / **React Native** / **Flutter**

只需在提示中提及你偏好的技术栈，或者让它默认使用 HTML + Tailwind。

## 设计系统命令（高级）

要直接访问设计系统生成器：

```bash
# 生成带有 ASCII 输出的设计系统
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "beauty spa wellness" --design-system -p "Serenity Spa"

# 生成带有 Markdown 输出的设计系统
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fintech banking" --design-system -f markdown

# 特定领域搜索
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "glassmorphism" --domain style
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "elegant serif" --domain typography
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "dashboard" --domain chart

# 特定技术栈指南
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "form validation" --stack react
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "responsive layout" --stack html-tailwind
```

### 持久化设计系统（主控 + 覆盖模式）

将你的设计系统保存到文件中，以便**跨会话进行分层检索**：

```bash
# 生成并持久化到 design-system/MASTER.md
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp"

# 同时创建一个页面特定的覆盖文件
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp" --page "dashboard"
```

这将创建一个 `design-system/` 文件夹结构：

```
design-system/
├── MASTER.md           # 全局单一事实来源（颜色、字体、间距、组件）
└── pages/
    └── dashboard.md    # 页面特定的覆盖（仅与主控的偏差）
```

**分层检索如何工作：**
1. 当构建特定页面（例如，"Checkout"）时，首先检查 `design-system/pages/checkout.md`
2. 如果页面文件存在，其规则**覆盖**主控文件
3. 如果不存在，则仅使用 `design-system/MASTER.md`

**上下文感知检索提示：**
```
我正在构建 [页面名称] 页面。请阅读 design-system/MASTER.md。
同时检查 design-system/pages/[page-name].md 是否存在。
如果页面文件存在，优先使用其规则。
如果不存在，则仅使用主控规则。
现在，生成代码...
```

## 项目结构

```
ui-ux-pro-max-skill/
├── README.md                          # 英文版项目说明
├── README_CN.md                       # 中文版项目说明
├── LICENSE                            # MIT 许可证
├── CLAUDE.md                          # Claude 特定配置
├── .gitignore                         # Git 忽略文件
│
├── .claude-plugin/                    # Claude Marketplace 插件配置
│   └── marketplace.json               # 插件元数据和版本信息
│
├── .agent/                            # Antigravity AI 助手配置
│   └── workflows/
│       └── ui-ux-pro-max.md          # Antigravity 工作流定义
│
├── .cursor/                           # Cursor 编辑器配置
│   └── commands/
│       └── ui-ux-pro-max.md          # Cursor 斜杠命令
│
├── .windsurf/                         # Windsurf 编辑器配置
│   └── workflows/
│       └── ui-ux-pro-max.md          # Windsurf 工作流定义
│
├── .github/                           # GitHub Copilot 配置
│   └── prompts/
│       └── ui-ux-pro-max.prompt.md   # Copilot 提示词
│
├── .kiro/                             # Kiro AI 助手配置
│   └── steering/
│       └── ui-ux-pro-max.md          # Kiro 转向规则
│
├── .codex/                            # Codex CLI 配置
│   └── skills/
│       └── ui-ux-pro-max/            # Codex 技能目录
│           ├── SKILL.md              # Codex 技能定义
│           ├── data/                 # 数据文件
│           └── scripts/              # Python 脚本
│
├── .qoder/                            # Qoder AI 助手配置
│   ├── rules/
│   │   ├── ui-ux-pro-max.md         # Qoder 规则文件
│   │   ├── charts.md                # 图表指南
│   │   ├── color.md                # 配色指南
│   │   ├── flutter.md              # Flutter 框架指南
│   │   ├── html-tailwind.md        # HTML+Tailwind 框架指南
│   │   ├── icons.md                # 图标指南
│   │   ├── loading.md              # 加载状态指南
│   │   ├── nextjs.md               # Next.js 框架指南
│   │   ├── nuxt-ui.md              # Nuxt UI 框架指南
│   │   ├── nuxtjs.md               # Nuxt.js 框架指南
│   │   ├── products.md             # 产品类型指南
│   │   ├── prompts.md              # 提示词指南
│   │   ├── react-native.md         # React Native 框架指南
│   │   ├── react.md                # React 框架指南
│   │   ├── shadcn.md               # shadcn/ui 框架指南
│   │   ├── styles.md               # UI 风格指南
│   │   ├── svelte.md               # Svelte 框架指南
│   │   ├── swiftui.md              # SwiftUI 框架指南
│   │   ├── typography.md           # 字体指南
│   │   ├── ux-guideline.md         # UX 指南
│   │   └── vue.md                  # Vue 框架指南
│   └── skills/
│       └── ui-ux-pro-max.md        # Qoder 技能定义
│
├── .roo/                              # Roo Code 配置
│   ├── commands/
│   │   └── ui-ux-pro-max.md        # Roo Code 命令定义
│   └── rules/
│       └── ui-ux-pro-max.md        # Roo Code 规则
│
├── .gemini/                           # Gemini CLI 配置
│   └── skills/
│       └── ui-ux-pro-max/            # Gemini 技能目录
│           ├── SKILL.md              # Gemini 技能定义
│           ├── data/                 # 数据文件
│           └── scripts/              # Python 脚本
│
├── .trae/                             # Trae AI 助手配置
│   └── skills/
│       └── ui-ux-pro-max/            # Trae 技能目录
│           ├── SKILL.md              # Trae 技能定义
│           ├── data/                 # 数据文件
│           └── scripts/              # Python 脚本
│
├── .opencode/                         # OpenCode 配置
│   └── skills/
│       └── ui-ux-pro-max/
│           └── SKILL.md              # OpenCode 技能定义
│
├── .shared/                           # 共享资源和数据（核心）
│   └── ui-ux-pro-max/
│       ├── data/                     # 设计数据文件
│       │   ├── stacks/              # 技术栈配置（11 个框架）
│       │   │   ├── flutter.csv      # Flutter 框架指南
│       │   │   ├── html-tailwind.csv # HTML+Tailwind 框架指南
│       │   │   ├── jetpack-compose.csv # Jetpack Compose 框架指南
│       │   │   ├── nextjs.csv       # Next.js 框架指南
│       │   │   ├── nuxt-ui.csv      # Nuxt UI 框架指南
│       │   │   ├── nuxtjs.csv       # Nuxt.js 框架指南
│       │   │   ├── react-native.csv # React Native 框架指南
│       │   │   ├── react.csv        # React 框架指南
│       │   │   ├── shadcn.csv       # shadcn/ui 框架指南
│       │   │   ├── svelte.csv       # Svelte 框架指南
│       │   │   ├── swiftui.csv      # SwiftUI 框架指南
│       │   │   └── vue.csv          # Vue 框架指南
│       │   ├── charts.csv           # 24 种图表类型推荐
│       │   ├── colors.csv           # 95 个配色方案
│       │   ├── icons.csv            # 图标库指南
│       │   ├── landing.csv          # 24 种着陆页模式
│       │   ├── products.csv         # 100 个产品类型规则
│       │   ├── prompts.csv          # AI 提示词模板
│       │   ├── react-performance.csv # React 性能优化指南
│       │   ├── styles.csv           # 57 种 UI 风格
│       │   ├── typography.csv       # 56 种字体搭配
│       │   ├── ui-reasoning.csv     # 100 条 UI 推理规则
│       │   ├── ux-guidelines.csv    # 98 条 UX 指南
│       │   └── web-interface.csv    # Web 界面指南
│       └── scripts/                  # Python 脚本工具
│           ├── core.py              # BM25 搜索引擎核心
│           ├── design_system.py     # 设计系统生成器
│           └── search.py            # 命令行搜索工具
│
├── cli/                               # CLI 工具源代码
│   ├── package.json                  # npm 包配置
│   ├── tsconfig.json                 # TypeScript 配置
│   ├── README.md                     # CLI 工具说明
│   ├── src/
│   │   ├── index.ts                 # CLI 入口文件
│   │   ├── commands/
│   │   │   ├── init.ts              # 初始化命令
│   │   │   ├── update.ts            # 更新命令
│   │   │   └── versions.ts          # 版本列表命令
│   │   ├── types/
│   │   │   └── index.ts             # TypeScript 类型定义
│   │   └── utils/
│   │       ├── detect.ts            # AI 助手检测
│   │       ├── extract.ts           # 资源提取
│   │       ├── github.ts            # GitHub API 集成
│   │       └── logger.ts            # 日志工具
│   └── assets/                      # 捆绑的资源文件
│       └── [AI 助手配置目录]
│
├── skills/                            # 技能目录（用于其他平台）
│   └── ui-ux-pro-max/
│       ├── SKILL.md                  # 通用技能定义
│       ├── data/                     # 数据文件
│       └── scripts/                  # Python 脚本
│
└── screenshots/                       # 项目截图
    └── website.png                   # 网站截图
```

## 核心数据文件说明

### 数据文件 (`.shared/ui-ux-pro-max/data/`)

| 文件 | 内容 | 用途 |
|------|------|------|
| **styles.csv** | 57 种 UI 风格 | 包含玻璃拟态、粘土拟态、极简主义、野兽派、新拟态、Bento 网格、深色模式等风格的详细定义，包括颜色、效果、最佳适用场景、性能和无障碍评级 |
| **colors.csv** | 95 个配色方案 | 针对不同产品类型（SaaS、电子商务、医疗健康、金融科技等）的配色方案，包含主色、辅色、CTA、背景、文字和边框颜色 |
| **typography.csv** | 56 种字体搭配 | 精心策划的字体组合，包含标题和正文字体、Google Fonts URL、CSS 导入代码和 Tailwind 配置 |
| **products.csv** | 100 个产品类型 | 针对不同产品（SaaS、电子商务、金融科技、医疗健康等）的风格推荐、着陆页模式和关键考虑因素 |
| **landing.csv** | 24 种着陆页模式 | 着陆页结构模式（Hero+Features、Hero+Testimonials、产品演示等），包含板块顺序、CTA 位置和转化优化策略 |
| **charts.csv** | 24 种图表类型 | 针对不同数据类型的图表推荐（折线图、柱状图、饼图、散点图、热力图等），包含颜色指导、无障碍说明和库推荐 |
| **icons.csv** | 图标库指南 | 推荐的图标库（Heroicons、Lucide、Simple Icons 等）和使用指南 |
| **prompts.csv** | AI 提示词模板 | 针对不同 UI 风格的 AI 提示词和 CSS 技术关键词 |
| **ux-guidelines.csv** | 98 条 UX 指南 | UX 最佳实践、反模式和无障碍规则，涵盖交互、布局、动画、可访问性等方面 |
| **ui-reasoning.csv** | 100 条 UI 推理规则 | 行业特定的设计系统生成规则，用于智能推荐风格、颜色、字体和效果 |
| **web-interface.csv** | Web 界面指南 | Web 界面设计的最佳实践，包括 ARIA、焦点、键盘导航、语义化等 |
| **react-performance.csv** | React 性能指南 | React 性能优化指南，包括瀑布流、打包、Suspense、Memo、重新渲染、缓存等 |

### 技术栈配置 (`stacks/`)

| 文件 | 内容 |
|------|------|
| **react.csv** | React 框架指南（状态管理、Hooks、性能优化、模式） |
| **nextjs.csv** | Next.js 框架指南（SSR、路由、图片、API 路由） |
| **vue.csv** | Vue 框架指南（Composition API、Pinia、Vue Router） |
| **nuxtjs.csv** | Nuxt.js 框架指南 |
| **nuxt-ui.csv** | Nuxt UI 框架指南 |
| **svelte.csv** | Svelte 框架指南（Runes、Stores、SvelteKit） |
| **swiftui.csv** | SwiftUI 框架指南（Views、State、Navigation、Animation） |
| **react-native.csv** | React Native 框架指南（Components、Navigation、Lists） |
| **flutter.csv** | Flutter 框架指南（Widgets、State、Layout、Theming） |
| **html-tailwind.csv** | HTML + Tailwind 框架指南（Tailwind 工具类、响应式、无障碍） |
| **shadcn.csv** | shadcn/ui 框架指南（组件、主题、表单、模式） |

### Python 脚本 (`scripts/`)

| 文件 | 功能 |
|------|------|
| **core.py** | BM25 搜索引擎核心，用于搜索和排序设计数据 |
| **design_system.py** | 设计系统生成器，聚合搜索结果并应用推理规则 |
| **search.py** | 命令行搜索工具，提供设计系统生成和领域搜索功能 |

## CLI 工具说明

CLI 工具 (`cli/`) 是一个 npm 包，用于简化 UI/UX Pro Max 技能的安装和管理。

### 主要功能

- **自动检测 AI 助手** - 检测当前项目使用的 AI 助手
- **GitHub 集成** - 从 GitHub 下载最新版本
- **离线模式** - 使用捆绑的资源文件
- **多平台支持** - 支持 11 种 AI 助手

### 命令

```bash
uipro init --ai <assistant>  # 初始化技能
uipro versions               # 列出可用版本
uipro update                 # 更新到最新版本
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=nextlevelbuilder/ui-ux-pro-max-skill&type=Date)](https://star-history.com/#nextlevelbuilder/ui-ux-pro-max-skill&Date)

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
