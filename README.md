# awesome-ai-agent

## 基础概念 

- **🔍 [技术人的大模型应用初学指南](https://mp.weixin.qq.com/s/NeR1yPdmK6Z1hZVLRSgxrQ)**  
  *简介：大淘宝技术团队撰写的实践指南，帮助开发者快速掌握大模型应用落地的核心方法论。*  
- **🤖 [AI Agent：7大认知框架全解析与代码实现](https://zhuanlan.zhihu.com/p/703716036)**  
  *简介：系统拆解AI Agent核心框架设计，结合可复现代码演示工程实现路径。*  
- **📊 [【译文】A Visual Guide to LLM Agents](https://mp.weixin.qq.com/s/y-JyvYaI3IQKE1ZM4RhiqA)**  
  *简介：可视化解读LLM Agents技术架构，通过图形化演示降低理解门槛。*  


## 教程资源
- **🎓 [微软-AI Agents for Beginners - A Course](https://github.com/microsoft/ai-agents-for-beginners)**  
  *简介：微软官方开源入门课程，包含12课时实践项目及行业应用案例解析。*

- **📚 [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)**  
  *简介：微软官方21课时入门课程，覆盖提示工程到应用开发全流程。*

- **🔍 [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai-guide)**  
  *简介：全面的生成式AI资源中心，整合研究论文、面试题库、免费课程与开发笔记。*


## 入门实操

- **🛠️ [Trae-Agent](https://github.com/bytedance/trae-agent)**  
  *简介：字节跳动开源的智能开发工具核心组件，集成于AI原生IDE Trae（The Real AI Engineer），支持自然语言驱动的编程任务自动化，显著提升开发效率。提供多模型支持、工具链集成与操作日志追溯能力，助力开发者构建智能协作工作流。*  

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

## Agent 论文

### 1. **📚 [awesome-foundation-agents](https://github.com/FoundationAgents/awesome-foundation-agents)**  
*简介：系统性整理基础智能体（Foundation Agents）研究路径的论文精选集，聚焦核心概念定义与技术演进脉络，提供领域研究全景导航。*  

### 2. **🎓 [Awesome-Agent-Papers](https://github.com/luo-junyu/Awesome-Agent-Papers)**  
*简介：智能体领域前沿论文聚合仓库，覆盖大语言模型智能体、多智能体协作、人-智能体交互三大方向，持续追踪学术界突破性成果。*  


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

### 📊 **3. [Gemini CLI](https://github.com/google-gemini/gemini-cli)**  
*Google官方推出的Gemini命令行工具，支持多模态交互与本地文件处理。*  
- **核心特点**：  
  - **多模态交互**：支持文本/图像混合输入，可解析图片内容并生成描述  
  - **本地文件处理**：支持上传PDF、图像等本地文件进行内容分析（`--file`参数）  
  - **流式响应**：实时显示API响应过程，支持对话式交互模式  
  - **多语言支持**：内置国际化配置，支持非英语内容生成  
  - **开发者工具**：提供API调用统计、响应时间测量等调试功能
 
### 🤖 **4. [OpenAI Codex](https://github.com/openai/codex)**  
* OpenAI 出品，专精于理解自然语言并生成对应代码。*  
- **核心特点**：  
  - **自然语言转代码**：可将人类语言描述直接转化为多种编程语言的函数或脚本。  
  - **多语言支持**：精通 Python、JavaScript、Go 等主流语言，适配广泛开发场景。  
  - **GitHub Copilot 核心**：作为底层引擎驱动智能编程助手，实现代码补全与生成功能。  

### 🖥️ **5. [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)**  
*字节跳动开源的桌面端UI自动化测试框架，支持跨平台界面元素识别与操作。*  
- **核心特点**：  
  - **视觉定位引擎**：基于CV算法实现精准控件识别，适应动态界面变化。  
  - **无侵入式测试**：无需修改应用源码即可执行自动化操作与断言验证。  
  - **多语言脚本支持**：兼容Python/Java等主流测试脚本，提供录制回放功能。  

### 👥 **6. [MetaGPT](https://github.com/geekan/MetaGPT)**  
*多智能体协作框架，通过角色分工与SOP流程实现复杂任务分解执行。*  
- **核心特点**：  
  - **角色扮演机制**：智能体可担任产品经理/工程师等专业角色，模拟真实工作流程。  
  - **标准化操作协议**：内置SOP引擎将复杂任务拆解为可执行原子操作链。  
  - **全流程自动化**：支持从需求分析到代码生成、测试评审的完整开发生命周期。  
  - **多模态输出**：同步生成需求文档/流程图/接口定义等标准化交付物。  

## 其他开源

### 1. **🤖 [AgentGPT](https://github.com/reworkd/AgentGPT)**  
*简介：浏览器端部署目标驱动智能体，支持零代码编排（自然语言设定目标→自动分解任务）、Next.js可视化面板、开源扩展（OpenAI/Anthropic模型集成）。*  

### 2. **🦉 [Camel-Owl](https://github.com/camel-ai/owl)**  
*简介：全自动多Agent协作框架（关联[camel-ai/camel](https://github.com/camel-ai/camel)），实现复杂任务分解/多角色分工（如Planner-Executor协作）、优化Manus架构、深度工具链集成（含API调用错误处理）。*  

### 3. **⚡ [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)**  
*简介：端到端任务自动化引擎（代码生成/数据分析），内置思维链（CoT）多步推理引擎（子任务依赖管理）、自我修正机制（动态错误检测与重试策略）。*  

### 4. **🛠️ [OpenHands](https://github.com/All-Hands-AI/OpenHands)**  
*简介：企业级开发自动化平台，支持动态任务执行（代码修改/Web浏览）、角色自适应机制（智能调整Agent行为）。*  

### 5. **🧑‍💻 [gpt-engineer](https://github.com/AntonOsika/gpt-engineer)**  
*简介：CLI工具实现自然语言→完整代码库生成，采用端到端代码生成架构，支持模块化扩展。*  

### 6. **🔬 [微软 RD-Agent](https://github.com/microsoft/RD-Agent)**  
*简介：LLM驱动的研发闭环系统，整合自动化实验迭代（实验设计→代码实现）、加速技术方案落地。*  

### 7. **🌐 [AutoGLM](https://github.com/xiao9905/AutoGLM)**  
*简介：基于LLM的自主研究代理，支持结构化报告生成。*  

### 8. **📊 [Llama Index](https://github.com/run-llama/llama_index)**  
*简介：私有数据智能代理构建工具（如企业知识库问答）。*  

### 9. **🚀 [NVIDIA AgentIQ](https://github.com/NVIDIA/AgentIQ)**  
*简介：企业级多智能体系统协作优化框架。*  

### 10. **🧩 [Giselle](https://github.com/giselles-ai/giselle)**  
*简介：节点式AI构建平台，支持多LLM/数据源连接，提供可视化编排界面。*  

---

**awesome-ai-agents**  <br>
https://github.com/e2b-dev/awesome-ai-agents

**awesome-llm-apps**  <br>
A curated collection of awesome LLM apps built with RAG and AI agents. This repository features LLM apps that use models from OpenAI, Anthropic, Google, and open-source models like DeepSeek, Qwen or Llama that you can run locally on your computer.  <br>
https://github.com/Shubhamsaboo/awesome-llm-apps

---

