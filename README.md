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

 - **📖 [Agent核心技术概念与范式发生了哪些演变以及背后的思考](https://mp.weixin.qq.com/s/11Krmb5KYmCHDQ4zN9O4uQ)**  
    *简介：围绕Agent技术从能力拼装到工程化落地的演变路径，梳理核心概念、主流架构范式与关键取舍，结合实践反思其背后的方法论与设计思维。*


  ## Agent 框架

 - **📖 [框架深度评测与对比分析](frameworks/frameworks-eval.md)**  
    *简介：全面评测主流 Agent 框架，覆盖六大类别：通用开发（LangChain/LangGraph/OpenAI Agents SDK）、多Agent协作（AutoGen/CrewAI/MetaGPT/AgentScope/Camel-Owl）、自主Agent（AutoGPT/BabyAGI/gpt-engineer）、数据与RAG（LlamaIndex/MemGPT）、平台级工具（Dify/Flowise/Spring AI Alibaba）、领域专用（TradingAgents/GPT-Researcher）。从架构设计、核心能力、适用场景等维度深度对比，提供选型决策矩阵，助你快速定位最佳技术方案。*

 - **📖 [LangGraph 官方文档](https://langchain-ai.github.io/langgraph/)**
     *简介：LangChain 团队推出的状态图式 Agent 编排框架，支持循环、分支、持久化与人工干预，提供细粒度控制流与记忆管理，适合构建复杂多步骤 Agent 工作流。*

 - **📄 [AutoGen: Enabling Next-Gen LLM Application via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155)**
     *简介：微软研究院提出的多 Agent 对话框架，支持 Agent 间自主对话协作、人机协同、代码执行与工具调用，可构建研究助手、编码团队等复杂应用场景。*
    
 - **📖 [如何设计一个AI Agent系统](https://mp.weixin.qq.com/s/8ArJk0vpGP0o97kEtqscqA)**  
    *简介：大淘宝 SRE 团队出品，从工程实践出发，系统讲解如何以LLM为认知核心，围绕规划、记忆、工具与执行框架构建可控可用的Agent系统，并结合研发流程、设计范式、知识管理与资损分析案例，给出工业落地方法论与实践体会。*

  
  ## Harness 实践

 - **📖 [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)**  
   *简介：Harness 设计是 Agentic Coding 前沿性能的关键。本文介绍 Anthropic 如何在前端设计与长时自主软件工程任务中进一步释放 Claude 的能力。*

- **📖 [Harness design for long-running application development](https://www.anthropic.com/engineering/harness-design-long-running-apps)**  
   *简介：Harness 设计是 Agentic Coding 前沿性能的关键。本文分享 Anthropic 如何在前端设计与长时自主软件工程任务中进一步推动 Claude 的能力边界。*

- **📖 [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)**  
   *简介：Context 是 AI Agent 的关键且有限资源。本文系统讨论如何高效策划、组织与管理上下文，以提升智能体在复杂任务中的稳定性与产出质量。*

- **📖 [OpenAI — Harness Engineering: Harnessing Codex in an Agent-First World](https://openai.com/zh-Hans-CN/index/harness-engineering/)**  
   *简介：OpenAI 分享在 Agent-First 时代如何通过 Harness Engineering 驱动 Codex 的稳定产出，重点覆盖上下文组织、工具调用编排、执行反馈闭环与工程可控性。*


 - **📖 [Agent Harness 解析：智能体架构深度拆解](https://mp.weixin.qq.com/s/H8_U4vENXJuiojXtXbCF5w)**  
    *简介：系统拆解 Agent Harness 的核心定义与工程边界，覆盖编排循环、工具调用、记忆体系、上下文管理、状态持久化、错误恢复与安全护栏等关键组件，并对 Anthropic、OpenAI、LangChain 等主流框架的落地模式进行对比，帮助从“模型能力”转向“基础设施能力”理解生产级智能体。*

 - **📖 [用第一性原理拆解 Agentic Coding：从理论到实操](https://mp.weixin.qq.com/s/Zlwn42KyfjgwfX6lp-JthQ)**  
    *简介：从第一性原理出发，系统拆解 Agentic Coding 的底层机制与工程实践：涵盖 LLM 自回归与 Attention 约束、Agent Loop 与工具调用原理、上下文管理与短对话策略、项目规则与复利工程（Compounding Engineering）等关键方法，帮助开发者从“会用 AI”走向“驾驭 AI 协作”的实战能力升级。*

 - **📖 [逆向深扒Claude Code源码，我发现了什么！？](https://mp.weixin.qq.com/s/hskSjAkezaV2epVzUq6ziw)**  
    *简介：基于 Claude Code v2.1.88 泄露源码的逆向工程分析，系统拆解其最小 Agent Loop 如何通过 12 层渐进式 Harness 升级为工业级编码代理，重点覆盖工具系统、权限与安全、上下文压缩、子代理协同、Skills 按需注入、会话持久化与编译时特性门控等核心设计。*

 - **📖 [深度解析 Hermes Agent 如何实现“自进化”及其 Prompt / Context / Harness 的设计实践](https://mp.weixin.qq.com/s/2xFei8dMx99lc-iyrZZrww)**  
    *简介：聚焦 Hermes 从“自主执行”迈向“自进化”的关键机制，系统拆解动态 Skill 沉淀与 RL 训练闭环两条演进路径，并从 Prompt、Context、Harness 三个工程维度分析其在异构模型兼容、长上下文压缩、记忆管理、错误自愈与安全约束上的设计取舍与落地实践。*

 - **📖 [拆完Hermes源码，我发现Agent的"自我进化"根本不需要训练模型](https://mp.weixin.qq.com/s/qdycBcCUujnVBkO4vky0wA)**  
    *简介：基于 Hermes Agent 源码逆向分析，重点拆解其通过“四维记忆 + 技能自动生成 + 后台审查（KEPA）”实现的自进化机制，说明 Agent 能力提升可通过 Prompt Engineering 与文件持久化闭环达成，而不必依赖模型微调，并与 OpenClaw 的学习范式做了工程化对比。*

 - **📖 [QQ音乐Harness Engineering实践](https://mp.weixin.qq.com/s/yw3DvqKBIV5fIZkSG12zdA)**  
    *简介：结合 QQ 音乐在 Monorepo Microservices 场景的落地案例，系统阐述如何以“代码产出 = AI 能力 × 上下文质量”为核心，通过五阶段四门禁、三层知识体系、三仓联动、Skill/Agent/Command 协同与 Self-Refinement 闭环，将 AI 协作从对话式编码升级为可控、可审计、可复用的工程流程。*

 - **📖 [Claude Code Harness 工程：数仓侧落地方案｜得物技术](https://mp.weixin.qq.com/s/KmQJU7nXmYh5qgWPj4ajlw)**  
    *简介：围绕数仓场景中 AI Coding 的上下文失忆、规范不稳与 context 膨胀问题，提出以 CLAUDE.md 持久化、Auto Memory、hooks 强校验、subagents 隔离与 SKILL 改造为核心的五层 Harness 防御体系，并给出可直接落地的 8 步工作流与工程化实施路径。*

 - **📖 [横向拆解Claude Code、Codex等六大Agent上下文压缩策略后，我们做了第 7 个](https://mp.weixin.qq.com/s/BQwyvE2qIfguwKk63F3LZw)**  
    *简介：横向对比 Claude Code、Codex、OpenCode、Cline、Cursor、Amp 与 MemGPT/Letta 的上下文压缩策略，提炼分层渐进、成本递增、增量摘要、用户消息保护与单调边界等共识，并面向云端多用户 Agent 落地四级水位线（Snip / Prune / Summarize）方案，补充存储分离、跨轮缓存与多用户隔离等工程实践。*


  ## 感知记忆 

 - **📖 [从架构到代码：深入理解 OpenClaw 的双源记忆系统](https://mp.weixin.qq.com/s/Ok3VwXft5fvvNWLBL6r2AA)**  
    *简介：围绕 OpenClaw 的“动态会话日志（JSONL）+ 静态长期记忆（Markdown）”双源记忆架构，深入拆解记忆生成、分块索引、向量与关键词混合检索（sqlite-vec + FTS5）以及 Agent 调用链路，并分析其在上下文容量、信息保真与 token 成本之间的工程权衡。*

 - **📖 [深度拆解 Hermes Agent 记忆系统：它修正了 OpenClaw 的哪层误区？](https://mp.weixin.qq.com/s/0n5aw2I0yoyHS7W5fQ6ydA)**  
    *简介：从运行时分层视角解析 Hermes 的记忆设计：通过 MEMORY/USER 热记忆、session_search 历史检索、skills 程序性记忆与可选 Honcho 外部建模，将“常驻事实、历史档案与流程经验”分层治理，并结合压缩前 memory flush 与 prompt cache 稳定前缀策略，展示其对长期 Agent 连续性与成本控制的工程取舍。*

  - **📄 [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560)**
     *简介：借鉴操作系统内存分页机制，将有限上下文窗口视为"主存"，外部存储视为"磁盘"，通过自主管理的内存分页与检索策略突破上下文瓶颈，支持长期对话与多会话持久化。*

  - **📄 [Let All Context Be Memorized: A Memory Bank Design for LLMs](https://arxiv.org/abs/2402.13315)**
     *简介：提出记忆银行架构，将历史信息按重要性分层存储，通过计算记忆的"存取频率"与"时间衰减"实现动态召回，有效缓解长对话中的信息遗忘问题。*

  ## RAG 实践

 - **📖 [大淘宝技术-RAG 全链路技术详解](https://mp.weixin.qq.com/s/aA2PFaabKNlDq96jhAdDkQ)**  
    *简介：深入解析RAG技术全链路实现细节。*

 - **📖 [大淘宝技术-AI 答疑助手优化实践：从 RAG 到 LightRAG 的全链路升级](https://mp.weixin.qq.com/s/b7iygA6YIqFJ-b9Yr3EzHA)**  
    *简介：分享从RAG到LightRAG的优化升级实践经验。*

 - **📖 [浏览器自动化：从GUI到OpenCLI](https://mp.weixin.qq.com/s/hp8yj2_qc2MmCi1jYpfx5g)**  
    *简介：探讨浏览器自动化从 GUI 到 OpenCLI 的技术演进与实践。*

  - **📄 [LightRAG: Simple and Fast Retrieval-Augmented Generation](https://arxiv.org/abs/2410.05779)**
     *简介：轻量级 RAG 框架，采用双层检索架构（细粒度关键词 + 精粒度语义），显著降低索引与查询延迟，相比 GraphRAG 在效率与成本上更友好，适合快速落地场景。*

  - **📄 [From Local to Global: A Graph RAG Approach to Query-Focused Summarization](https://arxiv.org/abs/2404.16130)**
     *简介：微软提出的图结构 RAG 方法，将文档实体抽取为知识图谱，通过社区检测与分层摘要实现"全局问题"的答案合成，在需要跨文档推理的场景中表现优异。*

## 评估观测

  - **📊 [Bringing Observability to Claude Code: OpenTelemetry in Action](https://signoz.io/blog/claude-code-monitoring-with-opentelemetry/)**
    *简介：SigNoz 官方出品的深度实践指南，从零搭建 OpenTelemetry 监控体系。深入剖析 Token 用量分析、成本核算、响应延迟控制等生产级场景，适合需要完整可观测性方案的团队落地实施。*

  - **🔧 [@devtheops/opencode-plugin-otel](https://github.com/devtheops/opencode-plugin-otel) · [npm](https://www.npmjs.com/package/@devtheops/opencode-plugin-otel)**
    *简介：功能完善的开源 OTel 插件，完整呈现 Claude Code 到 OpenTelemetry 的数据链路。通过研读源码可深入理解如何为 AI
  应用构建生产级可观测性数据模型，是学习和定制监控方案的绝佳参考实现。*

 - **📖 [Agent Tracing 技术方案对比：LangSmith vs Langfuse vs Phoenix](https://mp.weixin.qq.com/s/iVsw0u4sRa7IOA2iGtsYIw)**  
    *简介：横向对比 LangSmith、Langfuse、Phoenix 三款 Agent Tracing 方案，覆盖产品定位、追踪/评测/数据集/监控、框架集成、部署方式与定价，并指出 LangSmith 不支持私有化部署，补充 Langfuse 与 Phoenix 作为可自部署替代选型。*

  - **📊 [agenttrace](https://github.com/luoyuctl/agenttrace)**  
    *简介：本地优先的AI编码智能体会话观测工具，可读取Claude Code、Codex CLI、Gemini CLI、Qwen
  Code、Aider、Cursor、OpenCode、OpenClaw等日志，帮助开发者查看成本、Token、耗时、工具失败和慢任务原因。*

 - **🚀 [NVIDIA AgentIQ](https://github.com/NVIDIA/AgentIQ)**  
    *简介：企业级智能体观测与优化工具包，提供运行时性能分析、执行流程追踪、超参数/提示词优化器，支持 MCP/A2A 协议。*
    

  ## 工具生态

 - **📖 [如何让你的 Agent 更准确：MCP 工具设计技巧](https://mp.weixin.qq.com/s/wpiROVdoJAHvolkEpYo20w)**  
    *简介：围绕“工具是 Agent 的用户界面”这一核心理念，系统讲解 MCP 工具在命名、描述、参数 schema、输出与错误处理上的设计方法，结合工具粒度控制、上下文与 token 成本、Skills 与 MCP 互补等实践，帮助提升 Agent 的工具选择准确率与调用稳定性。*

 - **📖 [一文读懂 Agent Tools，拒绝复杂化、碎片化、黑盒化](https://mp.weixin.qq.com/s/rsu-k8NwzWceOfPxTRKkBA)**  
    *简介：从 Agent 工具全生命周期出发，系统梳理类型安全、LLM 友好接口、自我修复与人机确认等关键设计原则，并结合 AgentKit Gateway 在工具转化、调用治理、技能化管理与身份鉴权上的企业级实践，给出破解 Tools 碎片化、复杂化、黑盒化的落地路径。*

- **📖 [Code execution with MCP: Building more efficient agents](https://www.anthropic.com/engineering/code-execution-with-mcp)**  
   *简介：传统直接工具调用会为每个定义与中间结果持续消耗上下文。本文说明为何让 Agent 通过编写代码来调用工具更易扩展，并详细介绍在 MCP 中的实现方式。*

- **📖 [Writing effective tools for agents — with agents](https://www.anthropic.com/engineering/writing-tools-for-agents)**  
   *简介：Agent 的效果高度依赖可用工具质量。本文分享如何编写高质量工具与评测流程，并说明如何借助 Claude 反向优化其自身工具以进一步提升性能。*


  ## 评测基准

 - **📊 [AI Agent评测基准大揭秘：智能体的「体检标准」](https://mp.weixin.qq.com/s/9GCY-ufxNVnc-yCdFGnOeQ)**  
    *简介：深度解析主流Agent评估体系，系统性梳理 GAIA、AgentBench、PaperBench、WAA等七大主流评测基准，覆盖通用能力、安全鲁棒性、中文场景及科研复现等多维度评估体系。*

 - **📊 [XBench](https://github.com/xbench-ai/xbench)**  
    *简介：红杉中国推出的双轨测评体系：AGI Tracking测试技术上限，Profession-Aligned量化商业场景效用价值（如招聘/营销）。*

 - **🔍 [ClawBench](https://github.com/reacher-z/ClawBench)**  
    *简介：面向真实生产网页的AI浏览器Agent评测基准，153个日常任务、144个真实网站、15个类别；通过提交拦截层（Chrome扩展+CDP）保证真实环境下的端到端评测不产生副作用。评测了7个前沿模
  型，最佳通过率33.3%。[[paper](https://arxiv.org/abs/2604.08523)]*

  
  ## 自我进化

  - **📄 [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651)**
      *简介：Aman Madaan et al. (CMU, Google, Allen AI)，单一 LLM 同时作为生成器、反馈提供者和优化者，通过迭代式自我反馈改进输出，无需额外训练数据或强化学习。在 7 个任务上平均提升 20%。*

  - **📄 [OPRO: Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409)**
      *简介：Chengrun Yang et al. (Google DeepMind) 提出的方法，将 LLM 作为通用优化器，用自然语言描述优化任务，以历史解和评分为上下文迭代生成新候选解。GSM8K 提升 8%，Big-Bench Hard 提升 50%。*

  - **📄 [TextGrad: Automatic Differentiation via Text](https://arxiv.org/abs/2406.07496)**
      *简介：Mert Yuksekgonul et al. (Stanford) 提出的框架，借鉴神经网络反向传播思想，通过 LLM 提供的文本反馈"反向传播"优化复合 AI 系统各组件。采用 PyTorch 风格 API，GPT-4o 准确率从 51% 提升至
  55%。[[GitHub](https://github.com/zou-group/TextGrad)]*

  - **📄 [DSPy: Compiling Declarative Language Model Calls](https://arxiv.org/abs/2310.03714)**
      *简介：Omar Khattab et al. (Stanford) 提出的声明式 LM 编程框架，将 LM 管道抽象为计算图，编译器自动优化提示词、微调策略与推理流程。GPT-3.5 提升 >25%，llama2-13b-chat 提升
  >65%。[[文档](https://dspy.ai/)]*

  - **📄 [ADAS: Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435)**
      *简介： Shengran Hu, Cong Lu, Jeff Clune 提出"元智能体搜索"（Meta Agent Search）框架，让智能体通过编程自动发现新智能体架构，构建不断增长的发现档案。发明的智能体超越手工设计 SOTA，且跨领域迁移鲁棒。*

  - **📄 [STOP: Self-Teaching Optimization Program]()**
      *简介：递归自改进框架，LLM 通过生成自教学样本、反思自身解法、蒸馏推理能力来实现无外部数据的持续优化。核心是代码层面的递归改进循环。*

  
  ## 安全实践
  
  - **📖 [Claude Code 源码架构解析：从启动、Prompt 到权限管道](https://mp.weixin.qq.com/s/ibU8rAPPkcWrBKw3wArUFw)**  
    *简介：基于 Claude Code 本地源码，沿“启动链路→Prompt 装配→主循环→工具契约→文件编辑约束→权限决策→上下文压缩与记忆续航”主线，系统拆解其 Agent Runtime 的分层实现与治理边界，并讨论高权限扩展入口（hooks/MCP/skills）带来的安全面问题。*

  - **🛡️ [AgentDojo: A Benchmark for Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2406.05156)**
     *简介：Agent 安全评测基准，覆盖提示注入、工具滥用、权限绕过、数据泄露等 50+ 攻击场景，提供标准化攻击库与防御评测流程，量化 Agent 安全边界。*

  - **🛡️ [ToolEmu: A Framework for Evaluating the Safety of Tool-Using LLMs](https://arxiv.org/abs/2402.00908)**
     *简介：工具使用安全风险分析框架，通过模拟工具执行环境检测 Agent 在调用工具时的潜在危害行为（如文件删除、API 滥用），支持风险等级分类与安全策略制定。*

    
  ## 开源项目

 - **📈 [openclaw](https://github.com/openclaw/openclaw)**  
    *简介：OpenClaw开源项目。*

 - **🤖 [Claude Code](https://github.com/claude-code-best/claude-code)**  
    *简介：Anthropic官方泄露版本的Claude Code源码。*

 - **🛠️ [NotFair](https://github.com/nowork-studio/NotFair)**  
    *简介：面向营销场景的开源 Claude Code Skills 套件（约2.9k stars，MIT开源）。覆盖 SEO 站点分析、关键词研究、内容写作、Google Ads 审计与出价管理、Meta Ads（Facebook + Instagram）广告效果分析，通过 Google Ads MCP、Meta Ads MCP、Google Search Console MCP 和 Google Analytics（GA4）MCP 接入实时数据，是目前开源生态中覆盖付费广告+自然搜索最完整的 Agent Skills 实现。*

 - **🤖 [OpenAI Codex](https://github.com/openai/codex)**  
    *简介：OpenAI出品，专精于理解自然语言并生成对应代码。核心特点：自然语言转代码、多语言支持、GitHub Copilot核心引擎。*

 - **📊 [Gemini CLI](https://github.com/google-gemini/gemini-cli)**  
    *简介：Google官方推出的Gemini命令行工具，支持多模态交互与本地文件处理。核心特点：多模态交互、本地文件处理、流式响应、多语言支持、开发者工具。*

 - **🦌 [DeerFlow](https://github.com/bytedance/deer-flow)**  
    *简介：字节跳动推出的深度研究框架，集成多智能体协作与端到端研究自动化。核心特点：多智能体分工（基于LangGraph实现模块化架构）、工具深度集成（支持Tavily/DuckDuckGo搜索、Python代
  码执行、学术资源抓取）、人机协同创作（提供类Notion的交互式编辑界面）、MCP无缝扩展。*

 - **🌐 [Suna](https://github.com/kortix-ai/suna)**  
    *简介：Kortix AI推出的通用型智能体，专注于跨平台任务自动化执行。核心特点：浏览器自动化引擎（基于Playwright实现网页导航、数据抓取及表单操作）、安全沙箱环境（通过Docker容器隔离
  任务执行）、多工具链协同、企业级部署。*


 - **🖥️ [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)**  
    *简介：字节跳动开源的桌面端UI自动化测试框架，支持跨平台界面元素识别与操作。核心特点：视觉定位引擎、无侵入式测试、多语言脚本支持。*

  
 - **🤖 [AgentGPT](https://github.com/reworkd/AgentGPT)**  
    *简介：浏览器端部署目标驱动智能体，支持零代码编排（自然语言设定目标→自动分解任务）、Next.js可视化面板、开源扩展（OpenAI/Anthropic模型集成）。*


 - **🛠️ [OpenHands](https://github.com/All-Hands-AI/OpenHands)**  
    *简介：企业级开发自动化平台，支持动态任务执行（代码修改/Web浏览）、角色自适应机制（智能调整Agent行为）。*


 - **🔬 [微软 RD-Agent](https://github.com/microsoft/RD-Agent)**  
    *简介：LLM驱动的研发闭环系统，整合自动化实验迭代（实验设计→代码实现）、加速技术方案落地。*


  ## 实操 DEMO

 - **🛠️ [Trae-Agent](https://github.com/bytedance/trae-agent)**  
    *简介：字节跳动开源的智能开发工具核心组件，集成于AI原生IDE Trae（The Real AI
  Engineer），支持自然语言驱动的编程任务自动化，显著提升开发效率。提供多模型支持、工具链集成与操作日志追溯能力，助力开发者构建智能协作工作流。*

 - **🤖 [OpenManus](https://github.com/mannaandpoem/OpenManus)**  
    *简介：MetaGPT团队开源多智能体协作框架，支持快速复刻Manus核心功能，提供模块化协作机制与完整工具链支持（含强化学习版本）。*


  ## 资源中心

 - **📚 [《深入理解 AI Agent：设计原理与工程实践》（李博杰 著）](https://github.com/bojieli/ai-agent-book)**  
    *简介：《深入理解 AI Agent：设计原理与工程实践》开源主仓库：全书正文、编译版 PDF 与按章配套代码。*

 - **📚 [awesome-foundation-agents](https://github.com/FoundationAgents/awesome-foundation-agents)**  
    *简介：系统性整理基础智能体研究路径的论文精选集，聚焦核心概念定义与技术演进脉络，提供领域研究全景导航。*

 - **🔍 [Awesome Generative AI Guide](https://github.com/aishwaryanr/awesome-generative-ai-guide)**  
    *简介：全面的生成式AI资源中心，整合研究论文、面试题库、免费课程与开发笔记。*
    
 - **🎓 [Awesome-Agent-Papers](https://github.com/luo-junyu/Awesome-Agent-Papers)**  
    *简介：智能体领域前沿论文聚合仓库，覆盖大语言模型智能体、多智能体协作、人-智能体交互三大方向，持续追踪学术界突破性成果。*

 - **📈 [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills)**  
    *简介：OpenClaw技能资源汇总。*

 - **📈 [showcase](https://docs.openclaw.ai/start/showcase)**  
    *简介：OpenClaw展示案例。*

 - **📈 [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases)**  
    *简介：OpenClaw用例资源汇总。*

 - **📚 [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)**  
    *简介：AI Agent资源汇总。*

 - **📚 [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)**  
    *简介：精选的LLM应用集合，基于RAG和AI agents构建，支持OpenAI、Anthropic、Google以及DeepSeek、Qwen、Llama等开源模型，可本地运行。*
