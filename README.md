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

2. **🌐 [Google Agent SDK](https://cloud.google.com/vertex-ai/agents)**  
   *简介：谷歌多模态智能体开发套件，集成Vertex AI与Gemini模型。*

3. **⚙️ [Microsoft AutoGen](https://microsoft.github.io/autogen/)**  
   *简介：微软多代理对话框架，支持复杂工作流编排与自定义角色协作。*

4. **☁️ [AWS Agent SDK](https://aws.amazon.com/machine-learning/agents/)**  
   *简介：亚马逊云服务的智能体开发工具集（含Nova Act等组件）。*

5. **🧩 [LangGraph](https://langchain-ai.github.io/langgraph/)**  
   *简介：LangChain生态的有状态多代理系统，基于图结构构建循环工作流。*

6. **🐉 [Qwen Agent](https://github.com/QwenLM/Qwen-Agent)**  
   *简介：基于通义千问的LLM应用框架，支持指令遵循、工具调用与记忆管理。*

7. **👥 [CrewAI](https://github.com/joaomdmoura/crewai)**  
   *简介：面向角色扮演型Agent的编排框架，支持任务委派与团队协作。*


## ai-agents 项目集合
**awesome-ai-agents**  <br>
https://github.com/e2b-dev/awesome-ai-agents

**awesome-foundation-agents**   <br>
a curated collection of papers exploring the path towards Foundation Agents, with a focus on formulating the core concepts and navigating the research landscape.  <br>
https://github.com/FoundationAgents/awesome-foundation-agents

**awesome-llm-apps**  <br>
A curated collection of awesome LLM apps built with RAG and AI agents. This repository features LLM apps that use models from OpenAI, Anthropic, Google, and open-source models like DeepSeek, Qwen or Llama that you can run locally on your computer.  <br>
https://github.com/Shubhamsaboo/awesome-llm-apps

## 推荐开源工程
### LangManus
前端工程主要采用了 TS、PNPM、Next.JS、TailWindCSS、Zustand 技术栈，后端基于 Python、LangChain/LangGraph、FastAPI、构建的 AI 服务，集成了多种 LLM 模型，具有 Web API 功能。
前后端项目结构清晰，代码质量非常高，支持 Docker部署，入门学习首选。 <br>
**GitHub**:（原工程链接闭源了，这里是 fork 后的）
- [langmanus/langmanus](https://github.com/skyming/langmanus)  
- [langmanus/langmanus-web](https://github.com/skyming/langmanus-web)  

### Suna 
前后端采用了和 LangManus 几乎完全一致的技术栈，产品功能实现更为完整，支持数据库相应的能力  <br>
**GitHub**: https://github.com/kortix-ai/suna


## 重点关注框架

### 5.1.1 LangChain/LangGraph  
**GitHub**:  
- [langchain-ai/langchain](https://github.com/langchain-ai/langchain)  
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)  

**使用场景**：构建 LLM 驱动的应用（如 RAG 系统、聊天机器人）[[7]]。  
**技术亮点**：  
- 模块化架构，解决上下文保留与多步骤协调[[3]]；  
- 图结构设计支持复杂工作流（循环、并行）[[3]][[9]]。  
**源码解读**：  
- **链式组件设计**：研究 `Chain` 类与外部工具（`Tool`）的集成逻辑[[3]]；  
- **内存管理**：分析 `Memory` 模块对长对话的支持（如对话历史缓存）[[8]]。  

---
### 5.1.2 Deer-Flow
**GitHub**:  https://github.com/bytedance/deer-flow  <br>
**使用场景**：DeerFlow（Deep Exploration and Efficient Research Flow）是一个社区驱动的深度研究框架，它建立在开源社区的杰出工作基础之上。我们的目标是将语言模型与专业工具（如网络搜索、爬虫和Python代码执行）相结合，同时回馈使这一切成为可能的社区。  


### 5.1.3 AgentGPT  
**GitHub**: [reworkd/AgentGPT](https://github.com/reworkd/AgentGPT)  
**使用场景**：无需编程的 AI 代理部署（如非技术用户定制客服机器人）[[16]]。  
**技术亮点**：浏览器端部署、可视化界面支持，基于 LangChain 实现[[16]]。  
**源码解读**：  
- **前端与后端交互**：分析代理配置与任务执行流程（如 WebSocket 通信）；  
- **上下文记忆管理**：研究对话历史存储与检索机制（如本地存储或数据库集成）。  

---


## 5.2 近期高热度开源框架

### 5.2.1 OpenManus  
**GitHub**:  
- [mannaandpoem/OpenManus](https://github.com/mannaandpoem/OpenManus)  
- [OpenManus/OpenManus-RL](https://github.com/OpenManus/OpenManus-RL)  

**使用场景**：快速复刻 Manus 核心功能，支持本地化多智能体协作实验。  
**技术亮点**：  
- 模块化协作与实时反馈机制；  
- 工具链支持（如虚拟机控制、API 调用）。  
**源码解读**：  
- **分层架构设计**：需求理解层、规划层、执行层的分离[[3]]；  
- **ReAct 执行流程**：通过“思考-行动-观察”循环实现任务分解[[9]]；  
- **RL 版本**：结合奖励函数引导智能体学习高效策略（需分析 `AgentRL` 类）。  

---

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

## 5.3 多智能体协作框架

### 5.3.1 Swarm  
**GitHub**: [kyegomez/swarms](https://github.com/kyegomez/swarms)  
**使用场景**：创建和管理多个 AI Agent，支持复杂任务编排。  

### 5.3.2 CrewAI  
**GitHub**: [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)  
**使用场景**：角色扮演型协作（如虚拟团队完成设计项目）[[16]]。  
**技术亮点**：支持角色职责分配与动态任务调整[[16]]。  

### 5.3.3 AutoGen  
**GitHub**: [microsoft/autogen](https://github.com/microsoft/autogen)  
**使用场景**：企业级协作（如客服系统、数据分析流水线）[[12]]。  
**技术亮点**：微软背书，支持多 Agent 动态协商[[12]]。  

---
### 5.3.3 AutoGPT  
**GitHub**: [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)  
**使用场景**：端到端任务自动化（如代码生成、数据分析）[[3]]。  
**技术亮点**：基于“思维链”（CoT）实现多步推理[[3]]。  
**源码解读**：  
- **CoT 实现逻辑**：研究子任务拆分与依赖关系管理（如 `TaskManager` 类）；  
- **自我修正机制**：分析错误检测与重试策略（如异常捕获与回退逻辑）。  

### 5.3.4 Giselle  
**GitHub**: [giselles-ai/giselle](https://github.com/giselles-ai/giselle)  
**使用场景**：通过连接多个 LLM 和数据源，使用直观的节点式界面创建强大的 AI Agents。  

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

## 其他开源

- **AutoGLM**: [xiao9905/AutoGLM](https://github.com/xiao9905/AutoGLM)  
  基于 LLM 的自主研究代理，支持结构化研究报告生成。  
- **Llama Index**: [run-llama/llama_index](https://github.com/run-llama/llama_index)  
  使用场景：基于私有数据构建智能代理（如企业知识库问答）[[9]]。  
- **NVIDIA AgentIQ**: [NVIDIA/AgentIQ](https://github.com/NVIDIA/AgentIQ)  
  优化企业级多智能体系统协作效率。  
