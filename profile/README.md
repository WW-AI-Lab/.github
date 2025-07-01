# 👋 Welcome to **WW-AI-Lab**

> *AI-accelerated experiments for real-world impact.*

---

## 🌟 Who We Are
**WW-AI-Lab = 旺哥聊AI**.  
我是把 **生成式 AI** 当成拍档，以交付业务成果为目标的AI布道师。  
用 LLM、Agentic Workflow 与自动化技术，帮助企业完成 **智能化升级、降本增效**。

这里不是产品发布中心，而是 **实验车间**：  
每个仓库都是一次探索——可能是快速 Demo、学习笔记，或灵光一现的原型。  
**所有项目均由 AI（含 Cursor IDE、Copilot、RAG、Agent）辅助完成**。

---

## 🛠️ 你将在这里看到

| 主题 | 示例仓库 | 说明 |
|------|---------|------|
| 📄 **Document Processing** | [`any2markdown`](https://github.com/WW-AI-Lab/any2markdown), [`azure-gpt-image`](https://github.com/WW-AI-Lab/azure-gpt-image) | 文档转换服务、AI图像生成MCP服务 |
| 🚀 **Development Tools** | [`Awesome-MCP-Scaffold`](https://github.com/WW-AI-Lab/Awesome-MCP-Scaffold) | MCP服务器开发脚手架，5分钟启动生产级MCP服务 |
| 🔄 **Enterprise Automation** | [`browser-use-playwright`](https://github.com/WW-AI-Lab/browser-use-playwright), [`Dify-Batch`](https://github.com/WW-AI-Lab/Dify-Batch) | 浏览器自动化 + AI 自愈、Dify Workflow 批量执行系统 |
| 🤖 **Agentic Workflow** | [`jinja2-mcp-server`](https://github.com/WW-AI-Lab/jinja2-mcp-server) | Jinja2模板转换的MCP服务，AI工作流模板自动化 |
| 🖼️ **Gen-AI & Vision** | [`shape-mask-demo`](https://github.com/WW-AI-Lab/shape-mask-demo) | JavaScript前端图片编辑 |

> **Disclaimer:** 这里的仓库默认开源，仅用于学习与验证思路；**不保证生产可用**。欢迎 Fork / Issue / PR，一起把想法变成现实。

---

## ✨ 精选项目亮点

### 🔥 [any2markdown](https://github.com/WW-AI-Lab/any2markdown) ⭐ 18
> 高性能文档转换服务器，同时支持 Model Context Protocol (MCP) 和 RESTful API 接口

- **核心特性**：PDF/Word/Excel → Markdown转换、图片提取、页眉页脚移除、批量处理
- **适用场景**：文档数字化、知识库构建、AI训练数据准备
- **技术栈**：Python + MCP Protocol + REST API
- **亮点**：双协议支持，既可作为MCP服务集成到AI工作流，也可独立部署为REST服务

### 🚀 [Awesome-MCP-Scaffold](https://github.com/WW-AI-Lab/Awesome-MCP-Scaffold) ⭐ 14
> 开箱即用的 MCP 服务器开发脚手架，5分钟启动完整 MCP 服务器

- **核心特性**：快速启动、内置开发提示词、生产级架构、最佳实践内置
- **适用场景**：MCP服务快速开发、AI工具集成、企业级MCP部署
- **技术栈**：Python + MCP SDK v1.10.1 + FastAPI
- **亮点**：基于Cursor IDE优化，一句话完成MCP Server tools开发

### 🖼️ [azure-gpt-image](https://github.com/WW-AI-Lab/azure-gpt-image) ⭐ 1
> 基于Azure OpenAI gpt-image-1模型的MCP服务器，为AI助手提供图像生成和编辑能力

- **核心特性**：图像生成、图像编辑、MCP协议支持、Streamable HTTP Transport
- **适用场景**：AI助手图像功能、自动化图像处理、企业级图像生成
- **技术栈**：Python + Azure OpenAI + MCP SDK
- **亮点**：官方MCP SDK实现，企业级Azure服务集成

### 🎯 [browser-use-playwright](https://github.com/WW-AI-Lab/browser-use-playwright) ⭐ 2
> 一站式自动化方案：Browser-Use 低代码录制 → Playwright 稳定执行 → Browser-Use 智能自愈

- **核心特性**：AI 录制 + 稳定执行 + 智能自愈
- **适用场景**：电商数据采集、自动化测试、表单批量填写
- **技术栈**：Browser-Use + Playwright + FastAPI

### 🚀 [Dify-Batch](https://github.com/WW-AI-Lab/Dify-Batch) ⭐ 4
> Dify Workflow 批量执行系统，让 AI 工作流处理大规模任务

- **核心特性**：批量任务调度、进度监控、结果导出
- **适用场景**：内容批量生成、数据批量处理、AI 工作流自动化
- **技术栈**：Dify API + 任务调度 + Web UI

### 🤖 [jinja2-mcp-server](https://github.com/WW-AI-Lab/jinja2-mcp-server) ⭐ 1
> Jinja2 3.1.*版本的模板转换功能的MCP服务，便于在AI工作流或Agent中接入

- **核心特性**：模板转换、MCP协议支持、AI工作流集成
- **适用场景**：AI Agent模板处理、自动化文档生成、工作流模板转换
- **技术栈**：Python + Jinja2 + MCP Protocol

---

## ✨ Cursor 规则文件 & 开发过程文档

- **每个项目都会附带：**  
  - `.cursor/rules` —— 精简、专业的 **Cursor Rules**，方便你在 Cursor IDE 直接复现我们的上下文、提示词与代码风格。  
  - `docs/` —— 记录从想法 → 原型 → 迭代的关键决策、踩坑与最佳实践。  

这样你可以 **快速理解并深度探索**，将原型迁移到自己的生产环境。

---

## 🏢 Production Tracks

当某个原型在实践中证明有效，我们会将其 **升级为生产级方案** 并迁移到企业级组织：  
👉 **https://github.com/YFGaia** 

- 原型仓库仍保留在 **WW-AI-Lab**，方便社区复盘演进历程；  
- 正式版本会提供更严谨的测试、文档与长期维护，适合直接商用。  

---

## 🚀 Why We Do This

1. **实践出真知** – 行业对 AI 期待高，但落地案例少。我们用 Demo 证明「可行」并记录踩坑。  
2. **社区共建** – 分享代码、流程与文档，降低他人复现门槛，反过来获得更多反馈与灵感。  
3. **商业闭环** – 成熟方案迁移到企业组织，与客户一起 **降本增效**，反哺更多开源实验。

---

## 🤝 Get in Touch

| 渠道 | 地址 | 用途 |
|------|------|------|
| 📧 **Email** | toxingwang@gmail.com | 合作 / 业务咨询 |
| 🐦 **X (Twitter)** | [@WW_AI_Lab](https://x.com/WW_AI_Lab) | 最新动态、技术碎片 |
| 💬 **微信** | `toxingwang` | 深度交流、社群邀请，添加请注明来源 |

---

## 📜 License & Usage

- 代码默认 MIT（若仓库内有特殊 License 以各自 README 为准）。  
- **请勿**直接用于生产环境；若要商用，欢迎邮件或微信洽谈获得专业支持。  
- 使用本组织任何代码即视为接受相应 License 条款。
