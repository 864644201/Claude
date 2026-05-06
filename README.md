# Claude Code Skills Collection

[![Gstack](https://img.shields.io/badge/Gstack-v1.1.0-blue)](https://gstack.dev)
[![Planning with Files](https://img.shields.io/badge/Planning%20with%20Files-v2.37.0-green)](https://github.com/OthmanAdi/planning-with-files)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> 一套完整的 Claude Code 技能集合，涵盖浏览器测试、代码审查、安全审计、设计系统、部署发布、任务规划等开发全流程。

---

## 技能目录

### 浏览器与测试

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack](#gstack) | `/gstack` | 快速无头浏览器，QA 测试与站点体验 |
| [gstack-browse](#gstack-browse) | `/browse` | 无头浏览器核心，页面导航、截图、交互 |
| [gstack-qa](#gstack-qa) | `/qa` | 系统化 QA 测试并自动修复 bug |
| [gstack-qa-only](#gstack-qa-only) | `/qa-only` | 仅生成 QA 报告，不修改代码 |
| [gstack-scrape](#gstack-scrape) | `/scrape` | 从网页提取数据（只读） |
| [gstack-open-gstack-browser](#gstack-open-gstack-browser) | `/open-gstack-browser` | 启动 AI 控制的真实浏览器窗口 |
| [gstack-setup-browser-cookies](#gstack-setup-browser-cookies) | `/setup-browser-cookies` | 从真实浏览器导入 Cookie |
| [gstack-pair-agent](#gstack-pair-agent) | `/pair-agent` | 将远程 AI Agent 连接到你的浏览器 |

### 性能与基准

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-benchmark](#gstack-benchmark) | `/benchmark` | 性能回归检测，Core Web Vitals 基线 |
| [gstack-benchmark-models](#gstack-benchmark-models) | `/benchmark-models` | 跨模型对比：Claude vs GPT vs Gemini |

### 代码审查与质量

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-review](#gstack-review) | `/review` | PR 合并前代码审查 |
| [gstack-health](#gstack-health) | `/health` | 代码质量仪表盘（0-10 评分） |
| [gstack-retro](#gstack-retro) | `/retro` | 每周工程回顾 |
| [gstack-learn](#gstack-learn) | `/learn` | 管理跨会话的项目经验 |

### 安全

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-cso](#gstack-cso) | `/cso` | 首席安全官模式，全面安全审计 |
| [gstack-careful](#gstack-careful) | `/careful` | 危险命令警告（rm -rf、DROP TABLE 等） |
| [gstack-freeze](#gstack-freeze) | `/freeze` | 限制文件编辑范围 |
| [gstack-guard](#gstack-guard) | `/guard` | 全面安全模式（careful + freeze） |
| [gstack-unfreeze](#gstack-unfreeze) | `/unfreeze` | 解除编辑限制 |

### 设计

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-design-consultation](#gstack-design-consultation) | `/design-consult` | 设计系统咨询，创建 DESIGN.md |
| [gstack-design-html](#gstack-design-html) | `/design-html` | 将设计稿转化为生产级 HTML/CSS |
| [gstack-design-review](#gstack-design-review) | `/design-review` | 设计师视角的视觉 QA |
| [gstack-design-shotgun](#gstack-design-shotgun) | `/design-shotgun` | 生成多个设计变体并对比 |

### 规划与审查

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-autoplan](#gstack-autoplan) | `/autoplan` | 自动审查流水线，一键运行所有审查 |
| [gstack-plan-ceo-review](#gstack-plan-ceo-review) | `/plan-ceo-review` | CEO 创始人模式，挑战前提、扩大格局 |
| [gstack-plan-design-review](#gstack-plan-design-review) | `/plan-design-review` | 设计方案交互式审查 |
| [gstack-plan-devex-review](#gstack-plan-devex-review) | `/plan-devex-review` | 开发者体验方案审查 |
| [gstack-plan-eng-review](#gstack-plan-eng-review) | `/plan-eng-review` | 工程经理模式，锁定执行方案 |
| [gstack-plan-tune](#gstack-plan-tune) | `/plan-tune` | 调整问题敏感度与开发者画像 |
| [gstack-office-hours](#gstack-office-hours) | `/office-hours` | YC 风格头脑风暴 |

### 调查与调试

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-investigate](#gstack-investigate) | `/investigate` | 系统化调试，四阶段根因分析 |
| [gstack-devex-review](#gstack-devex-review) | `/devex-review` | 开发者体验实时测试审计 |

### 部署与发布

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-ship](#gstack-ship) | `/ship` | 发布流程：测试、审查、版本、PR |
| [gstack-land-and-deploy](#gstack-land-and-deploy) | `/land-and-deploy` | 合并 PR、等待 CI、验证生产 |
| [gstack-canary](#gstack-canary) | `/canary` | 发布后金丝雀监控 |
| [gstack-landing-report](#gstack-landing-report) | `/landing-report` | 版本队列只读看板 |
| [gstack-document-release](#gstack-document-release) | `/document-release` | 发布后文档同步更新 |
| [gstack-setup-deploy](#gstack-setup-deploy) | `/setup-deploy` | 配置部署平台 |

### 上下文与配置

| 技能 | 命令 | 说明 |
|------|------|------|
| [gstack-context-save](#gstack-context-save) | `/context-save` | 保存当前工作上下文 |
| [gstack-context-restore](#gstack-context-restore) | `/context-restore` | 恢复之前保存的上下文 |
| [gstack-setup-gbrain](#gstack-setup-gbrain) | `/setup-gbrain` | 设置 Gbrain 知识库 |
| [gstack-sync-gbrain](#gstack-sync-gbrain) | `/sync-gbrain` | 同步 Gbrain 与仓库代码 |
| [gstack-codex](#gstack-codex) | `/codex` | OpenAI Codex 集成 |
| [gstack-skillify](#gstack-skillify) | `/skillify` | 将成功流程固化为永久脚本 |
| [gstack-upgrade](#gstack-upgrade) | `/gstack-upgrade` | 升级 Gstack 到最新版 |
| [gstack-make-pdf](#gstack-make-pdf) | `/make-pdf` | Markdown 转出版级 PDF |

### 任务规划

| 技能 | 命令 | 说明 |
|------|------|------|
| [planning-with-files-zh](#planning-with-files-zh) | `/planning-with-files-zh` | Manus 风格文件规划系统（中文） |

### Claude Code 配置

| 技能 | 命令 | 说明 |
|------|------|------|
| [update-config](#update-config) | `/update-config` | 配置 Claude Code 设置 |
| [keybindings-help](#keybindings-help) | `/keybindings-help` | 自定义键盘快捷键 |
| [simplify](#simplify) | `/simplify` | 审查代码质量与效率 |
| [fewer-permission-prompts](#fewer-permission-prompts) | `/fewer-permission-prompts` | 减少权限确认弹窗 |
| [loop](#loop) | `/loop` | 按间隔重复运行命令 |
| [schedule](#schedule) | `/schedule` | 调度远程 Agent 定时任务 |
| [claude-api](#claude-api) | `/claude-api` | 构建与优化 Claude API 应用 |
| [init](#init) | `/init` | 初始化项目 |
| [review](#review) | `/review` | 审查 Pull Request |
| [security-review](#security-review) | `/security-review` | 安全审查 |

---

## 快速安装

```bash
# 安装 Gstack
npm install -g gstack

# 安装 Planning with Files（中文版）
npx skills add OthmanAdi/planning-with-files --skill planning-with-files-zh -g
```

---

## 技能详细说明

### 浏览器与测试

#### gstack

快速无头浏览器，用于 QA 测试和站点体验。

**命令：** `/gstack`
**语音触发：** browse, screenshot, navigate

```bash
# 使用示例
/gstack
# 然后描述你想做的操作
```

**功能：**
- 页面导航和交互
- 元素状态验证
- 截图和对比
- 响应式布局测试
- 表单和上传测试
- 弹窗处理

---

#### gstack-browse

无头浏览器核心引擎，每条命令约 100ms。

**命令：** `/browse`

```bash
# 截图
/browse https://example.com --screenshot

# 交互测试
/browse https://example.com --interact
```

**功能：**
- URL 导航和页面状态检查
- 元素交互（点击、填写、选择）
- 前后对比截图
- 响应式布局检查
- 断言元素状态

---

#### gstack-qa

系统化 QA 测试并自动修复发现的 bug。

**命令：** `/qa`
**语音触发：** quality check, test the app, run QA

```bash
# 测试并修复
/qa https://your-app.com
```

**三档模式：**
| 模式 | 说明 |
|------|------|
| Quick | 仅 critical/high 问题 |
| Standard | + medium 问题 |
| Exhaustive | + cosmetic 问题 |

**产出：** 前后健康分数、修复证据、发布就绪摘要

---

#### gstack-qa-only

仅生成 QA 报告，不修改任何代码。

**命令：** `/qa-only`
**语音触发：** bug report, just check for bugs

```bash
# 纯报告模式
/qa-only https://your-app.com
```

---

#### gstack-scrape

从网页提取数据（只读操作）。

**命令：** `/scrape`

```bash
# 提取数据
/scrape https://example.com/products
```

**注意：** 对于需要填写表单、点击等操作，请使用 `/browse`。

---

#### gstack-open-gstack-browser

启动 AI 控制的真实 Chromium 浏览器窗口。

**命令：** `/open-gstack-browser`
**语音触发：** show me the browser

```bash
/open-gstack-browser
```

**功能：**
- 实时观看 AI 操作浏览器
- 侧边栏显示活动日志和聊天
- 内置反机器人检测绕过

---

#### gstack-setup-browser-cookies

从真实浏览器导入 Cookie，用于测试需要登录的页面。

**命令：** `/setup-browser-cookies`

```bash
/setup-browser-cookies
# 打开交互式选择器，选择要导入的 Cookie 域名
```

---

#### gstack-pair-agent

将远程 AI Agent 连接到你的浏览器。

**命令：** `/pair-agent`
**语音触发：** pair agent, connect agent, share my browser

```bash
/pair-agent
# 生成密钥和连接说明
```

**支持的 Agent：** OpenClaw、Hermes、Codex、Cursor 等

---

### 性能与基准

#### gstack-benchmark

性能回归检测，建立 Core Web Vitals 基线。

**命令：** `/benchmark`
**语音触发：** speed test, check performance

```bash
# 建立基线
/benchmark https://your-app.com --baseline

# 对比检测
/benchmark https://your-app.com --compare
```

**功能：**
- 页面加载时间
- Core Web Vitals（LCP、FID、CLS）
- 资源大小
- 趋势追踪

---

#### gstack-benchmark-models

跨模型对比：Claude vs GPT vs Gemini。

**命令：** `/benchmark-models`
**语音触发：** compare models, model shootout, which model is best

```bash
# 对比模型
/benchmark-models "你的提示词"
```

**对比维度：**
- 延迟（Latency）
- Token 用量
- 成本
- 质量（通过 LLM 评判）

---

### 代码审查与质量

#### gstack-review

PR 合并前代码审查。

**命令：** `/review`

```bash
/review
# 自动分析当前分支的 diff
```

**审查内容：**
- SQL 安全性
- LLM 信任边界
- 条件副作用
- 结构性问题

---

#### gstack-health

代码质量仪表盘。

**命令：** `/health`

```bash
/health
```

**检测项：**
- 类型检查
- Lint 检查
- 测试覆盖率
- 死代码检测
- Shell 脚本检查
- 综合评分 0-10

---

#### gstack-retro

每周工程回顾。

**命令：** `/retro`
**语音触发：** weekly retro, what did we ship

```bash
/retro
```

**分析内容：**
- 提交历史分析
- 工作模式识别
- 代码质量指标
- 团队贡献分解
- 趋势追踪

---

#### gstack-learn

管理跨会话的项目经验。

**命令：** `/learn`

```bash
/learn
# 查看、搜索、清理和导出经验
```

---

### 安全

#### gstack-cso

首席安全官模式，全面安全审计。

**命令：** `/cso`
**语音触发：** see-so, security review, vulnerability scan

```bash
# 日常审计（零噪音，8/10 置信度门控）
/cso daily

# 全面审计（月度深度扫描，2/10 门槛）
/cso comprehensive
```

**审计范围：**
- 秘钥考古
- 依赖供应链
- CI/CD 管道安全
- LLM/AI 安全
- 技能供应链扫描
- OWASP Top 10
- STRIDE 威胁建模

---

#### gstack-careful

危险命令警告。

**命令：** `/careful`
**语音触发：** be careful, safety mode, prod mode

```bash
/careful
# 激活后，每个 bash 命令都会被检查
```

**拦截范围：**
- `rm -rf`
- `DROP TABLE`
- `git push --force`
- `git reset --hard`
- `kubectl delete`
- 等等

---

#### gstack-freeze

限制文件编辑范围到指定目录。

**命令：** `/freeze`

```bash
/freeze ./src
# 只允许编辑 ./src 目录下的文件
```

---

#### gstack-guard

全面安全模式（careful + freeze 组合）。

**命令：** `/guard`
**语音触发：** full safety, maximum safety, lock it down

```bash
/guard ./src
# 同时启用危险命令警告和编辑范围限制
```

---

#### gstack-unfreeze

解除编辑限制。

**命令：** `/unfreeze`

```bash
/unfreeze
# 移除 /freeze 设置的编辑边界
```

---

### 设计

#### gstack-design-consultation

设计系统咨询，创建项目的 DESIGN.md。

**命令：** `/design-consult`

```bash
/design-consult
```

**流程：**
1. 了解你的产品
2. 研究行业场景
3. 提出完整设计方案（美学、字体、颜色、布局、间距、动效）
4. 生成字体 + 颜色预览页
5. 创建 DESIGN.md

---

#### gstack-design-html

将设计稿转化为生产级 HTML/CSS。

**命令：** `/design-html`
**语音触发：** build the design, code the mockup, make it real

```bash
/design-html
```

**特点：**
- 文字真正重排
- 高度动态计算
- 30KB 开销，零依赖
- 智能 API 路由

---

#### gstack-design-review

设计师视角的视觉 QA。

**命令：** `/design-review`

```bash
/design-review
```

**检查项：**
- 视觉一致性
- 间距问题
- 层级关系
- AI 痕迹模式
- 交互速度

**工作方式：** 逐个修复问题，每次修复原子提交，并用前后截图验证

---

#### gstack-design-shotgun

生成多个设计变体并对比。

**命令：** `/design-shotgun`
**语音触发：** explore designs, show me options, design variants

```bash
/design-shotgun
# 生成多个变体 → 打开对比板 → 收集反馈 → 迭代
```

---

### 规划与审查

#### gstack-autoplan

自动审查流水线，一键运行所有审查。

**命令：** `/autoplan`
**语音触发：** auto plan, automatic review

```bash
/autoplan
# 依次运行 CEO、设计、工程、DX 审查，自动决策
```

**审查顺序：** CEO 审查 → 设计审查 → 工程审查 → DX 审查 → 最终门控

---

#### gstack-plan-ceo-review

CEO 创始人模式，挑战前提、扩大格局。

**命令：** `/plan-ceo-review`
**语音触发：** think bigger, expand scope, strategy review

```bash
/plan-ceo-review
```

**四种模式：**
| 模式 | 说明 |
|------|------|
| SCOPE EXPANSION | 大胆扩展 |
| SELECTIVE EXPANSION | 保持范围 + 精选扩展 |
| HOLD SCOPE | 最大化严谨度 |
| SCOPE REDUCTION | 精简到核心 |

---

#### gstack-plan-design-review

设计方案交互式审查。

**命令：** `/plan-design-review`
**语音触发：** design plan review, review ux plan

```bash
/plan-design-review
# 评分每个设计维度 0-10，解释如何达到 10 分
```

---

#### gstack-plan-devex-review

开发者体验方案审查。

**命令：** `/plan-devex-review`
**语音触发：** dx review, developer experience review

```bash
/plan-devex-review
```

**三种模式：**
| 模式 | 说明 |
|------|------|
| DX EXPANSION | 竞争优势 |
| DX POLISH | 全面打磨 |
| DX TRIAGE | 仅关键差距 |

---

#### gstack-plan-eng-review

工程经理模式，锁定执行方案。

**命令：** `/plan-eng-review`
**语音触发：** tech review, technical review

```bash
/plan-eng-review
# 架构、数据流、图表、边界情况、测试覆盖、性能
```

---

#### gstack-plan-tune

调整问题敏感度与开发者画像。

**命令：** `/plan-tune`

```bash
/plan-tune
# 查看被问过的问题、设置偏好（never-ask/always-ask）
```

---

#### gstack-office-hours

YC 风格头脑风暴。

**命令：** `/office-hours`
**语音触发：** brainstorm this, is this worth building, help me think through

```bash
/office-hours
```

**两种模式：**
| 模式 | 说明 |
|------|------|
| Startup | 六个强制性问题，暴露需求现实 |
| Builder | 设计思维头脑风暴，适合副项目、黑客松 |

---

### 调查与调试

#### gstack-investigate

系统化调试，四阶段根因分析。

**命令：** `/investigate`
**语音触发：** debug this, fix this bug, why is this broken

```bash
/investigate
```

**四阶段：**
1. **Investigate** — 收集信息
2. **Analyze** — 分析数据
3. **Hypothesize** — 提出假设
4. **Implement** — 实施修复

**铁律：** 没有根因就不修复

---

#### gstack-devex-review

开发者体验实时测试审计。

**命令：** `/devex-review`
**语音触发：** dx audit, test the developer experience

```bash
/devex-review
# 实际测试：导航文档、尝试入门流程、测量 TTHW
```

---

### 部署与发布

#### gstack-ship

发布流程。

**命令：** `/ship`

```bash
/ship
# 检测并合并基线分支 → 运行测试 → 审查 diff → 版本号 → CHANGELOG → 提交 → 推送 → 创建 PR
```

---

#### gstack-land-and-deploy

合并 PR 并验证生产环境。

**命令：** `/land-and-deploy`
**语音触发：** merge, land, deploy, merge and verify

```bash
/land-and-deploy
# 合并 PR → 等待 CI → 验证生产健康
```

---

#### gstack-canary

发布后金丝雀监控。

**命令：** `/canary`

```bash
/canary
# 监控控制台错误、性能回归、页面故障
# 定期截图，与发布前基线对比
```

---

#### gstack-landing-report

版本队列只读看板。

**命令：** `/landing-report`

```bash
/landing-report
# 显示哪些 VERSION 被 PR 占用、下一个可用版本
```

---

#### gstack-document-release

发布后文档同步更新。

**命令：** `/document-release`

```bash
/document-release
# 更新 README、ARCHITECTURE、CONTRIBUTING、CLAUDE.md
# 精炼 CHANGELOG、清理 TODO、可选升级 VERSION
```

---

#### gstack-setup-deploy

配置部署平台。

**命令：** `/setup-deploy`

```bash
/setup-deploy
# 自动检测部署平台（Fly.io、Render、Vercel、Netlify 等）
# 配置生产 URL、健康检查端点
```

---

### 上下文与配置

#### gstack-context-save

保存当前工作上下文。

**命令：** `/context-save`

```bash
/context-save
# 保存 git 状态、决策、剩余工作
```

---

#### gstack-context-restore

恢复之前保存的上下文。

**命令：** `/context-restore`
**语音触发：** resume, restore context, where was I

```bash
/context-restore
# 加载最近的保存状态，继续之前的工作
```

---

#### gstack-setup-gbrain

设置 Gbrain 知识库。

**命令：** `/setup-gbrain`

```bash
/setup-gbrain
# 安装 CLI → 初始化本地数据库 → 注册 MCP → 配置信任策略
```

---

#### gstack-sync-gbrain

同步 Gbrain 与仓库代码。

**命令：** `/sync-gbrain`

```bash
/sync-gbrain
# 探测状态 → 注册代码表面 → 能力检查 → 同步
```

---

#### gstack-codex

OpenAI Codex CLI 集成。

**命令：** `/codex`
**语音触发：** code x, get another opinion

```bash
# 代码审查
/codex review

# 对抗模式
/codex challenge

# 咨询
/codex consult
```

**三种模式：**
| 模式 | 说明 |
|------|------|
| Review | 独立 diff 审查，pass/fail 门控 |
| Challenge | 对抗模式，尝试破坏你的代码 |
| Consult | 咨询模式，支持连续对话 |

---

#### gstack-skillify

将成功流程固化为永久脚本。

**命令：** `/skillify`

```bash
/skillify
# 回顾最近的 /scrape 流程 → 合成 script.ts + 测试 → 验证 → 提交
```

---

#### gstack-upgrade

升级 Gstack 到最新版本。

**命令：** `/gstack-upgrade`
**语音触发：** upgrade the tools, update the tools

```bash
/gstack-upgrade
```

---

#### gstack-make-pdf

Markdown 转出版级 PDF。

**命令：** `/make-pdf`
**语音触发：** make this a pdf, export to pdf

```bash
/make-pdf document.md
```

**PDF 特性：**
- 1 英寸标准边距
- 智能分页
- 页码和页眉
- 封面页
- 弯引号和长破折号
- 可点击目录
- 对角 DRAFT 水印

---

### 任务规划

#### planning-with-files-zh

Manus 风格文件规划系统（中文版）。

**命令：** `/planning-with-files-zh`
**触发词：** 任务规划、项目计划、制定计划、分解任务、多步骤规划

```bash
/planning-with-files-zh
```

**核心模式：三文件系统**

| 文件 | 用途 | 更新时机 |
|------|------|---------|
| `task_plan.md` | 阶段、进度、决策 | 每个阶段完成后 |
| `findings.md` | 研究、发现 | 任何发现之后 |
| `progress.md` | 会话日志、测试结果 | 整个会话过程中 |

**关键规则：**
1. 先创建计划再执行
2. 每 2 次查看操作后保存发现
3. 决策前重新读取计划
4. 行动后更新状态
5. 记录所有错误
6. 不重复失败的操作
7. 三次失败后向用户求助

**会话恢复：** 运行 `/clear` 后自动恢复上一个会话的规划进度

---

### Claude Code 配置

#### update-config

配置 Claude Code 设置。

**命令：** `/update-config`

```bash
/update-config
# 配置 hooks、权限、环境变量、settings.json
```

---

#### keybindings-help

自定义键盘快捷键。

**命令：** `/keybindings-help`

```bash
/keybindings-help
# 自定义快捷键、添加和弦绑定、修改提交键
```

---

#### simplify

审查代码质量与效率。

**命令：** `/simplify`

```bash
/simplify
# 审查变更的代码，修复质量问题
```

---

#### fewer-permission-prompts

减少权限确认弹窗。

**命令：** `/fewer-permission-prompts`

```bash
/fewer-permission-prompts
# 扫描常用命令，添加到允许列表
```

---

#### loop

按间隔重复运行命令。

**命令：** `/loop`

```bash
# 每 5 分钟检查部署状态
/loop 5m /check-deploy

# 自定节奏
/loop /my-task
```

---

#### schedule

调度远程 Agent 定时任务。

**命令：** `/schedule`

```bash
# 每天上午 9 点运行检查
/schedule "0 9 * * *" "run health check"

# 一次性提醒
/schedule "15:00 today" "check the deploy"
```

---

#### claude-api

构建与优化 Claude API 应用。

**命令：** `/claude-api`

```bash
/claude-api
# 构建、调试和优化 Claude API / Anthropic SDK 应用
# 支持 prompt caching、model migration
```

---

#### init

初始化项目。

**命令：** `/init`

```bash
/init
```

---

#### review

审查 Pull Request。

**命令：** `/review`

```bash
/review
```

---

#### security-review

安全审查。

**命令：** `/security-review`

```bash
/security-review
```

---

## 系统要求

- **Node.js** >= 18
- **Claude Code** 最新版
- **Python** 3.x（用于 planning-with-files-zh 会话恢复）
- **PowerShell** 5.1+（Windows 用户）

## 许可证

MIT License
