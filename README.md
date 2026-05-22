 # awesome-ai-agent

  ![ai-agent-arch](https://github.com/user-attachments/assets/3112113e-4469-4412-ae28-7444516dedd8)

  ## 概念篇

  - **📊 [【译文】A Visual Guide to LLM Agents](https://mp.weixin.qq.com/s/y-JyvYaI3IQKE1ZM4RhiqA)**
    *简介：可视化解读LLM Agents技术架构，通过图形化演示降低理解门槛。*
    
  - **🏗️ [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)**
    *简介：Lilian Weng (Lil'Log) 撰写的 Agent 领域里程碑式博文。系统性地讲述了 Agent = LLM + 规划 + 记忆 + 工具使用的架构公式，详细拆解了任务分解、自我反思、长短期记忆机制及外部工具集成等核心组件。*

  - **📝 [Agent 核心论文深度解析（译文集）](key-concepts/page_tran.md)**
    *简介：深度解读 CoT (思维链)、ToT (思维树)、Reflexion (反思)、ReAct (推理+行动) 及 Toolformer (自监督工具学习) 等 Agent 核心论文，系统掌握智能体推理与规划的演进脉络。*

  - **🤖 [AI Agent：7大认知框架全解析与代码实现](https://zhuanlan.zhihu.com/p/703716036)**
    *简介：系统拆解AI Agent核心框架设计，结合可复现代码演示工程实现路径。*

  - **🔍 [技术人的大模型应用初学指南](https://mp.weixin.qq.com/s/NeR1yPdmK6Z1hZVLRSgxrQ)**
    *简介：大淘宝技术团队撰写的实践指南，帮助开发者快速掌握大模型应用落地的核心方法论。*


  ## 教程资源

  - **🎓 [微软-AI Agents for Beginners - A Course](https://github.com/microsoft/ai-agents-for-beginners)**
    *简介：微软官方开源入门课程，包含12课时实践项目及行业应用案例解析。*

  - **📚 [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)**
    *简介：微软官方21课时入门课程，覆盖提示工程到应用开发全流程。*

  - **🔍 [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai-guide)**
    *简介：全面的生成式AI资源中心，整合研究论文、面试题库、免费课程与开发笔记。*

  ## 入门实操

  - **🛠️ [Trae-Agent](https://github.com/bytedance/trae-agent)**
    *简介：字节跳动开源的智能开发工具核心组件，集成于AI原生IDE Trae（The Real AI
  Engineer），支持自然语言驱动的编程任务自动化，显著提升开发效率。提供多模型支持、工具链集成与操作日志追溯能力，助力开发者构建智能协作工作流。*

  - **🤖 [OpenManus](https://github.com/mannaandpoem/OpenManus)**
    *简介：MetaGPT团队开源多智能体协作框架，支持快速复刻Manus核心功能，提供模块化协作机制与完整工具链支持（含强化学习版本）。*

  ## Agent 文章

  - **📚 [awesome-foundation-agents](https://github.com/FoundationAgents/awesome-foundation-agents)**
    *简介：系统性整理基础智能体研究路径的论文精选集，聚焦核心概念定义与技术演进脉络，提供领域研究全景导航。*

  - **🎓 [Awesome-Agent-Papers](https://github.com/luo-junyu/Awesome-Agent-Papers)**
    *简介：智能体领域前沿论文聚合仓库，覆盖大语言模型智能体、多智能体协作、人-智能体交互三大方向，持续追踪学术界突破性成果。*

  - **📖 [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)**
    *简介：Agents still face challenges working across many context windows. We looked to human engineers for inspiration in creating a more effective harness for long-running
  agents.*

  ## 评测基准

  - **📊 [AI Agent评测基准大揭秘：智能体的「体检标准」](https://mp.weixin.qq.com/s/9GCY-ufxNVnc-yCdFGnOeQ)**
    *简介：深度解析主流Agent评估体系，系统性梳理 GAIA、AgentBench、PaperBench、WAA等七大主流评测基准，覆盖通用能力、安全鲁棒性、中文场景及科研复现等多维度评估体系。*

  - **📊 [XBench](https://github.com/xbench-ai/xbench)**
    *简介：红杉中国推出的双轨测评体系：AGI Tracking测试技术上限，Profession-Aligned量化商业场景效用价值（如招聘/营销）。*

  - **🔍 [ClawBench](https://github.com/reacher-z/ClawBench)**
    *简介：面向真实生产网页的AI浏览器Agent评测基准，153个日常任务、144个真实网站、15个类别；通过提交拦截层（Chrome扩展+CDP）保证真实环境下的端到端评测不产生副作用。评测了7个前沿模
  型，最佳通过率33.3%。[[paper](https://arxiv.org/abs/2604.08523)]*

  ## Agent 框架

  ### 一、通用开发框架

  - **🔗 [LangChain](https://github.com/langchain-ai/langchain)**
    *简介：最流行的LLM应用开发框架，提供链式调用、工具集成与Agent构建能力，生态丰富。*

  - **🧩 [LangGraph](https://langchain-ai.github.io/langgraph/)**
    *简介：LangChain生态的有状态多代理系统，基于图结构构建循环工作流，应该是生产环境使用最多的框架了。*

  - **🤖 [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)**
    *简介：轻量级开发套件，支持快速构建生产级Agentic AI应用（Swarm项目升级版）。*

  - **🧠 [Semantic Kernel](https://github.com/microsoft/semantic-kernel)**
    *简介：微软轻量级AI编排框架，支持技能规划、记忆管理，与Azure AI服务深度集成。*

  ### 二、多Agent协作框架

  - **⚙️ [Microsoft AutoGen](https://github.com/microsoft/autogen)**
    *简介：微软多代理对话框架，支持复杂工作流编排与自定义角色协作。*

  - **👥 [CrewAI](https://github.com/joaomdmoura/crewai)**
    *简介：面向角色扮演型Agent的编排框架，支持任务委派与团队协作。*

  - **🏢 [MetaGPT](https://github.com/geekan/MetaGPT)**
    *简介：多Agent协作框架，模拟软件公司角色分工（产品经理、架构师、工程师等），支持完整软件开发流程自动化。*

  - **🔬 [AgentScope](https://github.com/modelscope/agentscope)**
    *简介：阿里达摩院开源的多Agent框架，支持分布式部署、丰富工具生态与可视化工作流编排。*

  - **🤝 [AgentVerse](https://github.com/openbmb/agentverse)**
    *简介：清华OpenBMB开源的多Agent框架，支持角色定制、协作模式与可视化环境模拟。*

  ### 三、国产优化框架

  - **🐉 [Qwen Agent](https://github.com/QwenLM/Qwen-Agent)**
    *简介：基于通义千问的LLM应用框架，支持指令遵循、工具调用与记忆管理。*

  - **🚀 [Spring AI Alibaba](https://github.com/alibaba/spring-ai-alibaba)**
    *简介：阿里巴巴开源的Spring AI扩展库，集成通义千问等国产大模型，提供企业级AI应用开发框架与工具链。*

  - **🌟 [Agents](https://github.com/ModelBest/Agents)**
    *简介：智谱AI开源的Agent框架，支持多Agent协作、工具调用与GLM模型深度集成。*

  ### 四、自主Agent框架

  - **🎯 [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)**
    *简介：2023年爆火的自主Agent项目，支持目标拆解、任务执行与自主迭代优化。*

  - **👶 [BabyAGI](https://github.com/yoheinakajima/babyagi)**
    *简介：轻量级任务驱动Agent，基于向量存储实现任务管理与执行循环。*

  ### 五、数据与RAG增强框架

  - **🔍 [LlamaIndex](https://github.com/run-llama/llama_index)**
    *简介：数据框架+Agent构建工具，擅长结构化数据检索与多模态RAG Agent开发。*

  ### 六、平台级工具

  - **🛠️ [Dify](https://github.com/langgenius/dify)**
    *简介：开源LLM应用开发平台，提供可视化Agent编排、RAG工作流与一站式部署能力。*

  ### 七、领域专用框架

  - **📈 [TradingAgents](https://github.com/TauricResearch/TradingAgents)**
    *简介：开源金融交易Agent框架，支持量化策略开发与回测系统集成。*

  ## OpenClaw专题

  - **📈 [openclaw](https://github.com/openclaw/openclaw)**
    *简介：OpenClaw开源项目。*

  - **📈 [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills)**
    *简介：OpenClaw技能资源汇总。*

  - **📈 [showcase](https://docs.openclaw.ai/start/showcase)**
    *简介：OpenClaw展示案例。*

  - **📈 [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases)**
    *简介：OpenClaw用例资源汇总。*

  ## RAG 实践

  - **📖 [大淘宝技术-RAG 全链路技术详解](https://mp.weixin.qq.com/s/aA2PFaabKNlDq96jhAdDkQ)**
    *简介：深入解析RAG技术全链路实现细节。*

  - **📖 [大淘宝技术-AI 答疑助手优化实践：从 RAG 到 LightRAG 的全链路升级](https://mp.weixin.qq.com/s/b7iygA6YIqFJ-b9Yr3EzHA)**
    *简介：分享从RAG到LightRAG的优化升级实践经验。*

  ## 开源项目

  - **🤖 [Claude Code](https://github.com/claude-code-best/claude-code)**
    *简介：Anthropic官方泄露版本的Claude Code源码。*

  - **🦌 [DeerFlow](https://github.com/bytedance/deer-flow)**
    *简介：字节跳动推出的深度研究框架，集成多智能体协作与端到端研究自动化。核心特点：多智能体分工（基于LangGraph实现模块化架构）、工具深度集成（支持Tavily/DuckDuckGo搜索、Python代
  码执行、学术资源抓取）、人机协同创作（提供类Notion的交互式编辑界面）、MCP无缝扩展。*

  - **🌐 [Suna](https://github.com/kortix-ai/suna)**
    *简介：Kortix AI推出的通用型智能体，专注于跨平台任务自动化执行。核心特点：浏览器自动化引擎（基于Playwright实现网页导航、数据抓取及表单操作）、安全沙箱环境（通过Docker容器隔离
  任务执行）、多工具链协同、企业级部署。*

  - **📊 [Gemini CLI](https://github.com/google-gemini/gemini-cli)**
    *简介：Google官方推出的Gemini命令行工具，支持多模态交互与本地文件处理。核心特点：多模态交互、本地文件处理、流式响应、多语言支持、开发者工具。*

  - **🤖 [OpenAI Codex](https://github.com/openai/codex)**
    *简介：OpenAI出品，专精于理解自然语言并生成对应代码。核心特点：自然语言转代码、多语言支持、GitHub Copilot核心引擎。*

  - **🖥️ [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)**
    *简介：字节跳动开源的桌面端UI自动化测试框架，支持跨平台界面元素识别与操作。核心特点：视觉定位引擎、无侵入式测试、多语言脚本支持。*

  ## 其他开源

  - **🤖 [OpenAI Codex](https://github.com/openai/codex)**
    *简介：OpenAI出品，专精于理解自然语言并生成对应代码。核心特点：自然语言转代码、多语言支持、GitHub Copilot核心引擎。*

  - **🖥️ [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)**
    *简介：字节跳动开源的桌面端UI自动化测试框架，支持跨平台界面元素识别与操作。核心特点：视觉定位引擎、无侵入式测试、多语言脚本支持。*

  ## 其他开源

  - **🤖 [AgentGPT](https://github.com/reworkd/AgentGPT)**
    *简介：浏览器端部署目标驱动智能体，支持零代码编排（自然语言设定目标→自动分解任务）、Next.js可视化面板、开源扩展（OpenAI/Anthropic模型集成）。*

  - **🦉 [Camel-Owl](https://github.com/camel-ai/owl)**
    *简介：全自动多Agent协作框架（关联[camel-ai/camel](https://github.com/camel-ai/camel)），实现复杂任务分解/多角色分工（如Planner-Executor协作）、优化Manus架构、深度工具链集成（
  含API调用错误处理）。*

  - **🛠️ [OpenHands](https://github.com/All-Hands-AI/OpenHands)**
    *简介：企业级开发自动化平台，支持动态任务执行（代码修改/Web浏览）、角色自适应机制（智能调整Agent行为）。*

  - **🧑‍💻 [gpt-engineer](https://github.com/AntonOsika/gpt-engineer)**
    *简介：CLI工具实现自然语言→完整代码库生成，采用端到端代码生成架构，支持模块化扩展。*

  - **🔬 [微软 RD-Agent](https://github.com/microsoft/RD-Agent)**
    *简介：LLM驱动的研发闭环系统，整合自动化实验迭代（实验设计→代码实现）、加速技术方案落地。*

  - **🌐 [AutoGLM](https://github.com/xiao9905/AutoGLM)**
    *简介：基于LLM的自主研究代理，支持结构化报告生成。*

  - **🚀 [NVIDIA AgentIQ](https://github.com/NVIDIA/AgentIQ)**
    *简介：企业级多智能体系统协作优化框架。*

  - **🧩 [Giselle](https://github.com/giselles-ai/giselle)**
    *简介：节点式AI构建平台，支持多LLM/数据源连接，提供可视化编排界面。*

  - **📊 [agenttrace](https://github.com/luoyuctl/agenttrace)**
    *简介：本地优先的AI编码智能体会话观测工具，可读取Claude Code、Codex CLI、Gemini CLI、Qwen
  Code、Aider、Cursor、OpenCode、OpenClaw等日志，帮助开发者查看成本、Token、耗时、工具失败和慢任务原因。*

  ---

  - **📚 [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)**
    *简介：AI Agent资源汇总。*

  - **📚 [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)**
    *简介：精选的LLM应用集合，基于RAG和AI agents构建，支持OpenAI、Anthropic、Google以及DeepSeek、Qwen、Llama等开源模型，可本地运行。*

