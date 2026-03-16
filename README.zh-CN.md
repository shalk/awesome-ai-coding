# Awesome AI Coding [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 精选的 AI 驱动编程工具、库和资源列表，助力开发者提升效率

本集合专注于增强软件开发工作流程的 AI 工具——从代码补全和生成到测试、审查和部署。

[English](README.md) | 简体中文

## 目录

- [🤖 AI 代码助手与编辑器](#-ai-代码助手与编辑器)
- [⚡ 代码补全工具](#-代码补全工具)
- [🦾 编码智能体](#-编码智能体)
- [🔍 代码审查与质量](#-代码审查与质量)
- [🧭 代码搜索与导航](#-代码搜索与导航)
- [🧪 测试与质量保证](#-测试与质量保证)
- [🧠 AI 代码模型](#-ai-代码模型)
- [🏗️ 应用构建器与生成器](#%EF%B8%8F-应用构建器与生成器)
- [🎨 UI 生成器](#-ui-生成器)
- [⌨️ Shell 与 CLI 助手](#%EF%B8%8F-shell-与-cli-助手)
- [📚 文档工具](#-文档工具)
- [☁️ DevOps 与基础设施](#%EF%B8%8F-devops-与基础设施)
- [🛡️ 安全与漏洞检测](#%EF%B8%8F-安全与漏洞检测)
- [🗄️ 数据库与 API 工具](#%EF%B8%8F-数据库与-api-工具)
- [🔌 编辑器集成](#-编辑器集成)
- [🔗 相关列表](#-相关列表)

## 如何选择

浏览下面的分类，或使用这些快速筛选：

### 按 AI 提供商
- **GitHub/OpenAI**: GitHub Copilot, OpenAI Codex, GPT Engineer, AutoGPT
- **Anthropic/Claude**: Claude Code
- **多模型支持**（可配置）: Continue, Cursor, Codeium, Windsurf
- **开源模型**: Code Llama, StarCoder, DeepSeek Coder
- **专有模型**: Devin AI, Cursor, 大多数商业服务

### 按界面类型
- **完整 IDE**: Cursor, Windsurf
- **IDE 扩展**: Continue, CodeGPT, Codeium（参见[编辑器集成](#编辑器集成)）
- **CLI 工具**: Claude Code, Aider, Plandex, GitHub Copilot CLI
- **Web 服务**: 大多数审查、测试和应用构建工具
- **自托管**: FauxPilot, TabbyML, OpenDevin

### 按部署模式
- **云端**: 大多数商业工具（GitHub Copilot, Cursor 等）
- **自托管**: FauxPilot, TabbyML, OpenDevin
- **混合**（本地+云端）: Tabnine, Codeium
- **纯本地**: 某些支持本地模型的自托管选项

## 🤖 AI 代码助手与编辑器

功能完整的 AI 驱动开发环境和智能代码助手。

- [GitHub Copilot](https://github.com/features/copilot) - 实时建议代码和完整函数的 AI 结对编程工具。
- [Cursor](https://cursor.sh/) - 基于 VSCode 构建的 AI 优先代码编辑器，具有原生聊天和编辑功能。
- [Windsurf](https://codeium.com/windsurf) - Codeium 推出的智能体 IDE，支持多文件编辑工作流。
- [Claude Code](https://claude.ai/code) - Anthropic 官方 CLI 工具，由 Claude 驱动，用于自主编码任务。
- [Sourcegraph Amp](https://sourcegraph.com/amp) - Sourcegraph 推出的 AI 编码助手，具有代码库上下文感知能力。
- [Continue](https://continue.dev/) - VS Code 和 JetBrains 的开源自动驾驶工具，支持可自定义的 LLM。
- [Pieces for Developers](https://pieces.app/) - AI 驱动的代码片段管理器，具有上下文感知建议。
- [OpenAI Codex](https://openai.com/index/openai-codex/) - 驱动 GitHub Copilot，将自然语言转换为代码。
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google 开源的终端 AI 编码智能体，由 Gemini 模型驱动，支持文件系统访问和 MCP。
- [Antigravity](https://antigravity.google/) - Google 的 AI 驱动编码助手，用于开发环境。
- [Kiro](https://kiro.dev/) - AWS 推出的智能体 AI IDE，由 Claude 驱动，通过规格驱动开发将需求自动转换为代码。
- [Kiro CLI](https://kiro.dev/cli/) - AWS 推出的终端 AI 编码智能体，支持对话式编码、智能钩子、自定义智能体和 MCP 集成。

## ⚡ 代码补全工具

实时 AI 驱动的代码补全和建议引擎。

- [Codeium](https://codeium.com/) - 免费的 AI 代码补全，支持 70+ 种编程语言。
- [Tabnine](https://www.tabnine.com/) - 基于开源代码训练的 AI 代码补全，提供本地和云端选项。
- [FauxPilot](https://github.com/fauxpilot/fauxpilot) - 自托管的 GitHub Copilot 替代方案。
- [TabbyML](https://tabby.tabbyml.com/) - 自托管的 AI 编码助手，支持 RAG。
- [Safurai](https://www.safurai.com/) - Visual Studio Code 的 AI 代码助手。
- [Supermaven](https://supermaven.com/) - 具有大上下文窗口的快速 AI 代码补全。
- [CodeGPT](https://codegpt.co/) - 支持可自定义 AI 模型的代码补全。

## 🦾 编码智能体

能够独立编写、调试和部署代码的自主 AI 智能体。

- [Devin AI](https://devin.ai/) - 首个能够自主开发的 AI 软件工程师。
- [Devon](https://github.com/entropy-research/Devon) - 开源的结对编程智能体。
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - AI 软件开发者的开放平台。
- [Aider](https://aider.chat/) - 在本地 git 仓库中编辑代码的 AI 结对程序员。
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) - 从自然语言提示构建完整代码库。
- [Smol Developer](https://github.com/smol-ai/developer) - 个人初级开发者 AI 智能体。
- [MetaGPT](https://github.com/geekan/MetaGPT) - 用于软件开发的多智能体框架。
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - 用于开发任务的自主 GPT-4 智能体.
- [Plandex](https://plandex.ai/) - 基于终端的 AI 编码智能体，用于复杂任务。
- [Air](https://air.dev/) - 支持多任务开发工作流的 AI 智能体平台，提供人机协作控制。

## 🔍 代码审查与质量

自动化代码审查、质量分析和重构工具。

- [CodeRabbit](https://coderabbit.ai/) - AI 驱动的代码审查机器人，提供上下文反馈。
- [Qodo（原 Codium）](https://www.qodo.ai/) - 自动化代码审查和测试生成。
- [Sourcery](https://sourcery.ai/) - Python 的 AI 驱动代码审查和重构。
- [CodeReviewBot](https://github.com/anc95/ChatGPT-CodeReview) - 使用 GPT-4 进行自动化代码审查。
- [Sweep](https://sweep.dev/) - 用于拉取请求和错误修复的 AI 初级开发者。
- [What The Diff](https://whatthediff.ai/) - 用于拉取请求的 AI 驱动代码审查助手。
- [JetBrains Qodana](https://www.jetbrains.com/qodana/) - 具有 AI 洞察的智能代码质量平台。

## 🧭 代码搜索与导航

用于智能代码搜索、理解和跨代码库导航的工具。

- [Cosine](https://cosine.sh/) - AI 驱动的代码库索引和搜索。
- [Phind](https://www.phind.com/) - 为开发者打造的 AI 搜索引擎。
- [Bloop](https://bloop.ai/) - 由 GPT-4 驱动的代码搜索和导航。

## 🧪 测试与质量保证

AI 驱动的测试、测试生成和质量保证工具。

- [Meticulous](https://meticulous.ai/) - 无需编写测试的自动化前端测试。
- [TestRigor](https://testrigor.com/) - 使用 AI 的纯英文测试自动化。
- [Applitools](https://applitools.com/) - 使用 AI 的可视化测试和监控。
- [Functionize](https://www.functionize.com/) - AI 驱动的测试自动化平台。
- [Testim](https://www.testim.io/) - 基于 AI 的测试自动化，具有自我修复测试功能。
- [Diffblue Cover](https://www.diffblue.com/) - 为 Java 提供的 AI 驱动单元测试生成。

## 🧠 AI 代码模型

专门为代码生成和理解训练的大型语言模型。

- [Code Llama](https://github.com/facebookresearch/codellama) - Meta 的开源代码生成模型。
- [StarCoder](https://huggingface.co/bigcode/starcoder) - BigCode 推出的开源代码 LLM。
- [WizardCoder](https://github.com/nlpxucan/WizardLM) - 基于 StarCoder 的增强代码生成模型。
- [Phi-3](https://azure.microsoft.com/en-us/products/phi-3) - Microsoft 的小型语言模型，具有代码能力。
- [CodeGen](https://github.com/salesforce/CodeGen) - Salesforce 的代码生成模型系列。
- [Replit Code V1.5](https://huggingface.co/replit/replit-code-v1_5-3b) - Replit 的代码补全模型。
- [DeepSeek Coder](https://github.com/deepseek-ai/DeepSeek-Coder) - 在 2T tokens 上训练的开源代码模型。

## 🏗️ 应用构建器与生成器

AI 驱动的低代码/无代码平台和快速应用生成器。

- [Bolt.new](https://bolt.new/) - StackBlitz 的提示到全栈应用，在浏览器中运行。
- [Lovable（原 GPT Engineer）](https://lovable.dev/) - 从提示构建完整应用。
- [Pythagora](https://pythagora.ai/) - 使用 GPT-4 从零构建生产就绪应用。
- [Replit](https://replit.com/) - 基于浏览器的 IDE，具有 AI 驱动的应用生成功能。
- [FlutterFlow](https://flutterflow.io/) - 可视化应用构建器，具有 AI 代码生成功能。
- [Glide](https://www.glideapps.com/) - 使用 AI 从电子表格构建应用。
- [Softr](https://www.softr.io/) - 将 Airtable 转换为具有 AI 辅助的 Web 应用。
- [Durable](https://durable.co/) - AI 网站和应用构建器。
- [Capacity](https://capacity.com/) - AI 驱动的商业应用构建器。

## 🎨 UI 生成器

AI 驱动的设计转代码和 UI 生成工具。

- [v0.dev](https://v0.dev/) - Vercel 的 AI UI 生成器，从文本提示生成界面。
- [Magic Patterns](https://www.magicpatterns.com/) - 从提示生成 React 组件。
- [Kombai](https://kombai.com/) - 将 Figma 设计转换为 React/HTML 代码。
- [Galileo AI](https://www.usegalileo.ai/) - 文本到 UI 设计工具。
- [Uizard](https://uizard.io/) - AI 驱动的 UI 设计和原型制作。
- [Figma AI](https://www.figma.com/ai/) - Figma 中的原生 AI 功能，用于设计生成。
- [Locofy](https://www.locofy.ai/) - 将 Figma/Adobe XD 转换为生产就绪代码。

## ⌨️ Shell 与 CLI 助手

为开发者打造的 AI 驱动命令行和 Shell 助手。

- [GitHub Copilot CLI](https://githubnext.com/projects/copilot-cli/) - GitHub 的 AI 命令行助手。
- [Warp](https://www.warp.dev/) - 具有自然语言命令的 AI 驱动终端。
- [ShellGPT](https://github.com/TheR1D/shell_gpt) - 使用 ChatGPT 的命令行 AI 助手。
- [AI Shell](https://github.com/BuilderIO/ai-shell) - 自然语言到 Shell 命令的转换。
- [Fig](https://fig.io/) - 终端自动补全和 AI 助手（现为 AWS 的一部分）。
- [RTK](https://github.com/rtk-ai/rtk) - 命令行代理，将开发工具输出压缩后再传给 LLM，可减少 60-90% 的 token 消耗。
- [CodexBar](https://github.com/steipete/CodexBar) - macOS 菜单栏应用，实时监控 15+ AI 编程助手的 token 用量与速率限制。

## 📚 文档工具

使用 AI 自动生成和维护文档。

- [Mintlify](https://mintlify.com/) - AI 驱动的文档构建器。
- [Trelent](https://trelent.ai/) - 为代码自动生成文档字符串。
- [README-AI](https://github.com/eli64s/readme-ai) - 使用 AI 生成 README 文件。
- [DocuWriter.ai](https://www.docuwriter.ai/) - AI 驱动的代码文档生成。
- [Stenography](https://stenography.dev/) - 自动代码文档生成器。
- [Swimm](https://swimm.io/) - AI 驱动的代码文档平台。

## ☁️ DevOps 与基础设施

用于部署自动化、基础设施管理和 DevOps 的 AI 工具。

- [K8sGPT](https://k8sgpt.ai/) - AI 驱动的 Kubernetes 诊断工具。
- [Kubiya](https://www.kubiya.ai/) - DevOps 工作流的 AI 助手。
- [AutoCloud](https://www.autocloud.io/) - 自动化云基础设施图表和文档。
- [Pulumi AI](https://www.pulumi.com/ai/) - 自然语言到基础设施即代码的转换。
- [Firefly](https://www.firefly.ai/) - 具有 AI 洞察的云资产管理。

## 🛡️ 安全与漏洞检测

AI 驱动的安全分析、漏洞检测和合规工具。

- [Snyk](https://snyk.io/) - 具有 AI 驱动修复的开发者安全工具。
- [Snyk Code](https://snyk.io/product/snyk-code/) - AI 驱动的安全代码审查。
- [GitGuardian](https://www.gitguardian.com/) - 秘密检测和修复。
- [Semgrep](https://semgrep.dev/) - 具有 AI 辅助规则创建的静态分析。
- [Socket](https://socket.dev/) - AI 驱动的供应链安全。
- [Pixee](https://pixee.ai/) - 自动化安全和代码质量改进。
- [CodeQL](https://codeql.github.com/) - GitHub 的语义代码分析引擎。

## 🗄️ 数据库与 API 工具

AI 驱动的数据库查询生成、API 开发和数据工具。

- [Text2SQL.AI](https://text2sql.ai/) - 从自然语言生成 SQL 查询。
- [AI2sql](https://www.ai2sql.io/) - 使用 AI 的 SQL 查询构建器。
- [Airbook](https://www.airbook.io/) - AI 驱动的数据分析和 SQL 生成。
- [Patterns](https://www.patterns.app/) - 具有 AI 辅助的数据管道构建。
- [Supabase AI](https://supabase.com/ai) - AI SQL 编辑器和数据库助手。

## 🔌 编辑器集成

用于各种编辑器和 IDE 的 ChatGPT 和 LLM 集成。

- [ChatGPT.nvim](https://github.com/jackMort/ChatGPT.nvim) - Neovim 的 ChatGPT 插件。
- [gptel](https://github.com/karthink/gptel) - Emacs 的 ChatGPT 集成。

## 🔗 相关列表

与 AI 编程和开发相关的其他精选列表。

- [awesome-code-ai](https://github.com/sourcegraph/awesome-code-ai) - Sourcegraph 的 AI 编程工具精选列表。
- [awesome-ai-coding-tools](https://github.com/ai-for-developers/awesome-ai-coding-tools) - aifordevelopers.org 组织的综合列表。
- [awesome-chatgpt](https://github.com/humanloop/awesome-chatgpt) - ChatGPT 和 GPT-4 资源。
- [awesome-llm](https://github.com/Hannibal046/Awesome-LLM) - 大型语言模型和应用。
- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - 自主 AI 智能体。

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
