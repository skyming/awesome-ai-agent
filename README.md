# awesome-ai-agent

## 基础概念 

- **🔍 [技术人的大模型应用初学指南](https://mp.weixin.qq.com/s/NeR1yPdmK6Z1hZVLRSgxrQ)**  
  *简介：大淘宝技术团队撰写的实践指南，帮助开发者快速掌握大模型应用落地的核心方法论。*  
- **🤖 [AI Agent：7大认知框架全解析与代码实现](https://zhuanlan.zhihu.com/p/703716036)**  
  *简介：系统拆解AI Agent核心框架设计，结合可复现代码演示工程实现路径。*  
- **📊 [【译文】A Visual Guide to LLM Agents](https://mp.weixin.qq.com/s/y-JyvYaI3IQKE1ZM4RhiqA)**  
  *简介：可视化解读LLM Agents技术架构，通过图形化演示降低理解门槛。*  
- **🎓 [微软-AI Agents for Beginners - A Course](https://github.com/microsoft/ai-agents-for-beginners)**  
  *简介：微软官方开源入门课程，包含12课时实践项目及行业应用案例解析。*  


## 入门实操

- **🤖 [OpenManus](https://github.com/mannaandpoem/OpenManus)**  
  *简介：MetaGPT团队开源多智能体协作框架，支持快速复刻Manus核心功能，提供模块化协作机制与完整工具链支持（含强化学习版本）。*  


## 评测基准

- **[AI Agent评测基准大揭秘：智能体的「体检标准」](https://mp.weixin.qq.com/s/9GCY-ufxNVnc-yCdFGnOeQ)**  
  *简介：深度解析主流Agent评估体系，揭示工业界与学术界对智能体能力的差异化验证逻辑。*  

1. **🌐 [GAIA Leaderboard](https://huggingface.co/spaces/gaia-benchmark/leaderboard)**  
   *简介：Meta与HuggingFace共建的多模态评测平台，聚焦复杂任务拆解与工具链协作能力验证，覆盖跨模态推理与工具调用场景*  

2. **📚 [PaperBench](https://github.com/openai/preparedness/)**  **[技术解析](https://mp.weixin.qq.com/s/zIS2JQf3-o7GQ-EWriTjkQ)**  
   *简介：OpenAI开源的科学复现评测框架, 2025年4月3日发布，通过8,316项子任务量化Agent复现论文的完整能力。*  

3. **🧠 [AgentBench](https://github.com/THUDM/AgentBench)**  
   *简介：清华大学主导的多环境实战基准，覆盖操作系统、数据库、知识图谱等8类真实场景，量化Agent动态决策能力。*
   
4. **📊 XBench**  
  红杉中国推出的**双轨测评体系**：  
  - *AGI Tracking*：测试技术上限  
  - *Profession-Aligned*：量化商业场景效用价值（如招聘/营销）。  

## Agent SDK 

1. **🤖 [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)**  
   *简介：轻量级开发套件，支持快速构建生产级Agentic AI应用（Swarm项目升级版）。*

2. **🧩 [LangGraph](https://langchain-ai.github.io/langgraph/)**  
   *简介：LangChain生态的有状态多代理系统，基于图结构构建循环工作流。*

3. **🌐 [Google Agent SDK](https://cloud.google.com/vertex-ai/agents)**  
   *简介：谷歌多模态智能体开发套件，集成Vertex AI与Gemini模型。*

4. **⚙️ [Microsoft AutoGen](https://github.com/microsoft/autogen)**  
   *简介：微软多代理对话框架，支持复杂工作流编排与自定义角色协作。*

5. **🤖 [Claude Code SDK (Python)](https://github.com/anthropic/claude-code-sdk-python)**  
   *简介：Anthropic官方提供的Claude代码生成SDK（Python版），用于生成和编辑代码。*
   
6. **☁️ [AWS Agent SDK](https://github.com/strands-agents/sdk-python)**  
   *简介：亚马逊云服务的智能体开发工具集（含Nova Act等组件）。*

7. **🐉 [Qwen Agent](https://github.com/QwenLM/Qwen-Agent)**  
   *简介：基于通义千问的LLM应用框架，支持指令遵循、工具调用与记忆管理。*

8. **👥 [CrewAI](https://github.com/joaomdmoura/crewai)**  
   *简介：面向角色扮演型Agent的编排框架，支持任务委派与团队协作。*

9. **📈 [TradingAgents](https://github.com/TauricResearch/TradingAgents)**  
   *简介：开源金融交易 Agent 框架，支持量化策略开发与回测系统集成。*

## 开源项目

### 🦌 **1. [DeerFlow](https://github.com/bytedance/deer-flow)**  
*字节跳动推出的深度研究框架，集成多智能体协作与端到端研究自动化。*  
- **核心特点**：  
  - **多智能体分工**：基于 LangGraph 实现模块化架构（协调器、规划器、研究员、报告员），支持动态任务迭代与重规划（Re-planning）。  
  - **工具深度集成**：支持 Tavily/DuckDuckGo 搜索、Python 代码执行、学术资源（Arxiv）抓取，扩展性强。  
  - **人机协同创作**：提供类 Notion 的交互式编辑界面，支持自然语言修改研究计划，并生成报告、PPT、播客脚本等多模态内容。  
  - **MCP 无缝扩展**：可接入私有域知识库或第三方服务（如高德地图），实现定制化研究场景。  

### 🌐 **2. [Suna](https://github.com/kortix-ai/suna)**  
*Kortix AI 推出的通用型智能体，专注于跨平台任务自动化执行。*  
- **核心特点**：  
  - **浏览器自动化引擎**：基于 Playwright 实现网页导航、数据抓取及表单操作（如 LinkedIn 简历采集、竞品价格监控）。  
  - **安全沙箱环境**：通过 Docker 容器隔离任务执行，支持敏感数据（API 密钥）动态注入，保障宿主系统安全。  
  - **多工具链协同**：整合 Python 解释器、命令行工具和 API 服务，支持复杂指令解析（例：“分析医疗市场规模并生成 PDF 报告”）。  
  - **企业级部署**：提供云端 SaaS 服务（免费版至企业版）及自托管方案，适配商业分析、销售自动化等场景。  

### 🤖 **3. [AgentGPT](https://github.com/reworkd/AgentGPT)**  
*自主智能体部署平台，支持浏览器端配置目标驱动的 AI 智能体。*  
- **核心特点**：  
  - **零代码智能体编排**：用户通过自然语言设定目标，系统自动分解任务并调用工具链执行。  
  - **Web 优先架构**：基于 Next.js 实现可视化控制面板，实时展示任务状态与执行日志。  
  - **开源社区驱动**：支持集成 OpenAI、Anthropic 等模型，工具插件生态持续扩展。  

### 🌐 **4. [Gemini CLI](https://github.com/google-gemini/gemini-cli)**  
*Google官方推出的Gemini命令行工具，支持多模态交互与本地文件处理。*  
- **核心特点**：  
  - **多模态交互**：支持文本/图像混合输入，可解析图片内容并生成描述  
  - **本地文件处理**：支持上传PDF、图像等本地文件进行内容分析（`--file`参数）  
  - **流式响应**：实时显示API响应过程，支持对话式交互模式  
  - **多语言支持**：内置国际化配置，支持非英语内容生成  
  - **开发者工具**：提供API调用统计、响应时间测量等调试功能  
---


**awesome-ai-agents**  <br>
https://github.com/e2b-dev/awesome-ai-agents

**awesome-foundation-agents**   <br>
a curated collection of papers exploring the path towards Foundation Agents, with a focus on formulating the core concepts and navigating the research landscape.  <br>
https://github.com/FoundationAgents/awesome-foundation-agents

**awesome-llm-apps**  <br>
A curated collection of awesome LLM apps built with RAG and AI agents. This repository features LLM apps that use models from OpenAI, Anthropic, Google, and open-source models like DeepSeek, Qwen or Llama that you can run locally on your computer.  <br>
https://github.com/Shubhamsaboo/awesome-llm-apps


## 其他开源

### 5.2.2 Camel-Owl  
**GitHub**:  
- [camel-ai/owl](https://github.com/camel-ai/owl)  
- [camel-ai/camel](https://github.com/camel-ai/camel)  

**使用场景**：全自动多 Agent 协作（如自动化办公、复杂任务分解）。  
**技术亮点**：复刻 Manus 并优化，支持多 Agent 协作与工具调用。  
**源码解读**：  
- **角色分工与协作**：模拟人类团队协作流程（如 `PlannerAgent` 与 `ExecutorAgent`）；  
- **工具链集成**：分析外部 API 调用与错误处理逻辑（如 `ToolExecutor` 类）。  


---
### 5.3.3 AutoGPT  
**GitHub**: [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)  
**使用场景**：端到端任务自动化（如代码生成、数据分析）[[3]]。  
**技术亮点**：基于“思维链”（CoT）实现多步推理[[3]]。  
**源码解读**：  
- **CoT 实现逻辑**：研究子任务拆分与依赖关系管理（如 `TaskManager` 类）；  
- **自我修正机制**：分析错误检测与重试策略（如异常捕获与回退逻辑）。  

---



## 5.4 代码编程方向


### 5.4.1 MetaGPT  
**GitHub**: [geekan/MetaGPT](https://github.com/geekan/MetaGPT)  
**使用场景**：软件开发全流程自动化（需求分析→代码生成）。  
**技术亮点**：SOP（标准操作流程）驱动的角色分工[[3]]。  

### 5.4.2 OpenHands  
**GitHub**: [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands)  
**使用场景**：企业级软件开发自动化（如代码修改、Web 浏览）[[7]]。  
**技术亮点**：动态任务执行与角色自适应机制[[4]]。  

### 5.4.3 gpt-engineer  
**GitHub**: [AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer)  
**使用场景**：自然语言生成完整代码库的 CLI 工具。  
**技术亮点**：端到端代码生成与模块化架构。  

### 5.4.4 微软 RD-Agent  
**GitHub**: [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent)  
**使用场景**：LLM 驱动的研究与开发（R&D）闭环流程。  
**技术亮点**：整合实验设计与代码实现的自动化迭代[[6]]。  

---


- **AutoGLM**: [xiao9905/AutoGLM](https://github.com/xiao9905/AutoGLM)  
  基于 LLM 的自主研究代理，支持结构化研究报告生成。  
- **Llama Index**: [run-llama/llama_index](https://github.com/run-llama/llama_index)  
  使用场景：基于私有数据构建智能代理（如企业知识库问答）[[9]]。  
- **NVIDIA AgentIQ**: [NVIDIA/AgentIQ](https://github.com/NVIDIA/AgentIQ)  
  优化企业级多智能体系统协作效率。  
- **Giselle**: [giselles-ai/giselle](https://github.com/giselles-ai/giselle)  
  通过连接多个 LLM 和数据源，使用直观的节点式界面创建强大的 AI Agents。  
