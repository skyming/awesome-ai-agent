# awesome-ai-agent
5.1 重点关注框架
5.1.1 LangChain/LangGraph
https://github.com/langchain-ai/langchain
https://github.com/langchain-ai/langgraph
使用场景：构建 LLM 驱动的应用（如 RAG 系统、聊天机器人）。
技术亮点：模块化架构，解决上下文保留与多步骤协调。
源码解读：
链式组件设计：研究 Chain 类与外部工具（Tool）的集成；
内存管理：分析 Memory 模块对长对话的支持。
5.1.2 AgentGPT
https://github.com/reworkd/AgentGPT
使用场景：无需编程的 AI 代理部署（如非技术用户定制客服机器人）。
技术亮点：浏览器端部署、可视化界面支持，基于 LangChain 实现。
源码解读：
前端与后端交互逻辑：分析代理配置与任务执行流程；
上下文记忆管理：需研究对话历史存储与检索机制。
5.1.3 AutoGPT
https://github.com/Significant-Gravitas/AutoGPT
使用场景：端到端任务自动化（如代码生成、数据分析）。
技术亮点：基于“思维链”（CoT）实现多步推理。
源码解读：
CoT 实现逻辑：研究子任务拆分与依赖关系管理；
自我修正机制：分析错误检测与重试策略。

5.2 近期高热度开源框架
5.2.1 OpenManus
https://github.com/mannaandpoem/OpenManus
https://github.com/OpenManus/OpenManus-RL
使用场景：快速复刻 Manus 核心功能，支持本地化多智能体协作实验。
技术亮点：模块化协作、实时反馈机制、工具链支持（如虚拟机控制）。
源码解读：
分层架构设计：需求理解层、规划层、执行层；
ReAct 执行流程：通过“思考-行动-观察”循环实现任务分解；
提示词工程优化：提升 LLM 的上下文理解和工具调用精度。
【RL版本】RL 算法与 LLM 决策结合：通过奖励函数引导智能体学习高效策略
【RL版本】状态-动作空间设计：需分析任务状态表示与动作生成逻辑。
5.2.2 Camel-Owl
https://github.com/camel-ai/owl
https://github.com/camel-ai/camel
使用场景：全自动多 Agent 协作（如自动化办公、复杂任务分解）。
技术亮点：复刻 Manus 并优化，支持多 Agent 协作与工具调用。
源码解读：
角色分工与协作：模拟人类团队协作流程；
任务分解算法：需研究其层级化任务分配策略。
工具链集成：分析外部 API 调用与错误处理逻辑。
5.2.3 LangManus 
https://github.com/langmanus/langmanus
https://github.com/langmanus/langmanus-web
使用场景：学术研究（如 DeepSearchg、多 Agent 协作机制探索）。
技术亮点：社区驱动的AI自动化框架核心，实现分层多智能体协作系统。
源码解读：据传来自字节开发的开源项目
模块化智能体设计：代码可能按角色划分模块（如ResearcherAgent、CoderAgent），通过LangChain实现通信
任务流程引擎：基于状态机或LangGraph的Graph类管理任务分解、分配与结果聚合

5.3 多智能体协作框架
5.3.1 Swarm 
Swarm是OpenAI发布的一个实验性多智能体编排框架，旨在简化多智能体系统的构建、编排和管理。用于创建和管理多个AI Agent。
https://github.com/kyegomez/swarms
5.3.2 CrewAI
https://github.com/crewAIInc/crewAI
使用场景：角色扮演型协作（如虚拟团队完成设计项目）[[16]]。
技术亮点：支持角色职责分配与动态任务调整[[16]]。
源码解读：
角色定义与通信：研究 Agent 类的职责配置与消息传递机制；
任务协调逻辑：分析任务队列与优先级管理。
5.3.3 AutoGen
https://github.com/microsoft/autogen
使用场景：企业级协作（如客服系统、数据分析流水线）[[12]]。
技术亮点：微软背书，支持多 Agent 动态协商[[12]]。
源码解读：
智能体通信协议：研究对话历史与状态同步机制；
自适应角色调整：分析任务失败时的角色重新分配策略。
5.4 代码编程方向
5.4.1 MetaGPT
https://github.com/geekan/MetaGPT
使用场景：软件开发全流程自动化（需求分析→代码生成）。
技术亮点：SOP（标准操作流程）驱动的角色分工[[3]]。
源码解读：
角色专业化：产品经理、工程师等角色的分工逻辑[[3]]；
SOP 流程实现：研究需求到代码的链式任务执行[[8]]。
5.4.2  OpenHands
https://github.com/All-Hands-AI/OpenHands
使用场景：  
企业级软件开发自动化（如代码修改、命令执行、Web浏览），支持端到端开发流程（如克隆项目、调试部署。  
技术亮点：
动态任务执行：通过自然语言指令驱动开发操作，支持Docker环境集成与API调用；
角色自适应：基于任务失败的智能体接管机制，通过图结构回溯更新权限矩阵；
标准化交互协议：分离通信规则与业务逻辑，实现跨框架智能体协作。
源码解读：
工具接口设计：通过BaseTool类定义交互模板，结合对话历史缓存实现状态同步；
容错机制：在任务异常时触发备用智能体接管，利用轻量级数据格式规范确保流程可追溯。

5.4.3 gpt-engineer
https://github.com/AntonOsika/gpt-engineer
使用场景：  
自然语言生成完整代码库的CLI工具，适用于快速原型开发与端到端流程自动化。  
技术亮点：
端到端代码生成：通过LLM解析用户指令生成可执行代码，覆盖从需求到部署的全生命周期；
模块化架构：支持多步骤代码生成与依赖管理（基于项目描述推测）。
源码解读：
CLI核心逻辑：通过命令行参数解析用户需求，调用LLM生成代码框架（具体实现需参考项目文档）；
代码优化模块：可能包含迭代反馈机制以提升生成质量（资料不足，无法引用来源）。

5.4.4 微软 RD-Agent
https://github.com/microsoft/RD-Agent 
使用场景：  
研究与开发（R&D）自动化，通过LLM驱动实验设计、代码生成与结果分析的闭环流程。  
技术亮点：
LLM驱动闭环：整合研究假设验证与代码实现，支持自动化实验迭代；
跨领域适配：可能内置领域知识库以增强LLM的上下文理解能力（基于项目目标推测）。
源码解读：
研究流程引擎：或采用模块化设计分离研究任务与开发操作（如实验设计、数据分析）；
LLM集成层：可能通过Prompt工程与知识注入优化模型输出（具体实现需参考代码库）。


其它开源
[3] AutoGLM: Autonomous Foundation Agents for GUIs https://http://xiao9905.github.io/AutoGLM/

基于LLM的自主研究代理，支持深度本地与网络研究，生成结构化研究报告
https://github.com/assafelovic/gpt-researcher

开发者优先的开源自主AI代理框架，支持快速构建与部署多模态AI应用
https://github.com/TransformerOptimus/SuperAGI
轻量级实验性框架，旨在探索自主代理的底层逻辑与社区协作
https://github.com/yoheinakajima/babyagi

微软研究院联合高校推出的开源多模态AI基础模型，支持跨数字与物理环境的任务处理
https://github.com/microsoft/Magma
Llama Index
https://github.com/run-llama/llama_index
使用场景：基于私有数据构建智能代理（如企业知识库问答）。
技术亮点：数据框架整合 LLM 与私有数据源。
源码解读：
数据索引构建：研究文档解析与向量化存储逻辑；
查询引擎：分析 LLM 提示词与数据检索的结合策略。

A lightweight, powerful framework for multi-agent workflows 
https://github.com/openai/openai-agents-python
英伟达开源软件库，用于连接、分析和优化企业级多智能体系统（Multi-Agent System），提升 AI 团队协作效率
https://github.com/NVIDIA/AgentIQ
