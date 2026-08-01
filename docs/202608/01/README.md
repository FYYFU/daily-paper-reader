# 日报 · 2026-08-01

- 生成时间：2026-08-01 20:38:56 UTC
- 当次推荐总数：18
- 精读区：9
- 速读区：9

## 今日简报（AI）
今日共读18篇论文，精读9篇、速读9篇；其中两篇满分精读聚焦多模态大模型的分辨率特权自蒸馏与轨迹继传式在线蒸馏。最值得关注的是“RP-OPSD”与“Pass the Baton”两篇10分工作，均探索强化在线蒸馏的效率与稳定性，另可留意8分的自适应测试时计算优化。建议优先精读两篇满分论文，并延伸关注自蒸馏在计算资源受限场景下的落地潜力。

## 精读区
1. [RP-OPSD: Resolution-Privileged On-Policy Self-Distillation for Multimodal Large Language Models](/202608/01/2607.24447v1-rp-opsd-resolution-privileged-on-policy-self-distillation-for-multimodal-large-language-models) （10.0/10）
   evidence：面向多模态大模型的在线策略自蒸馏
2. [Pass the Baton: Trajectory-Relayed On-Policy Distillation](/202608/01/2607.26057v1-pass-the-baton-trajectory-relayed-on-policy-distillation) （10.0/10）
   evidence：轨迹中继的在线策略蒸馏方法
3. [Flux-OPD: On-Policy Distillation with Evolving Contexts](/202608/01/2607.28022v1-flux-opd-on-policy-distillation-with-evolving-contexts) （10.0/10）
   evidence：直接提出用于大模型训练的在线策略蒸馏(OPD)方法，并引入演化上下文
4. [Forecasting Trajectory-Level Safety Risks in Black-Box Multi-Turn Interactions](/202608/01/2607.26820v1-forecasting-trajectory-level-safety-risks-in-black-box-multi-turn-interactions) （9.0/10）
   evidence：面向LLM智能体多轮交互的轨迹级安全风险预测
5. [AgentS4D: Benchmarking Runtime Risks across the Execution Lifecycle of LLM-Based Workspace Agents](/202608/01/2607.27294v1-agents4d-benchmarking-runtime-risks-across-the-execution-lifecycle-of-llm-based-workspace-agents) （9.0/10）
   evidence：提供面向LLM工作空间智能体运行时安全风险的基准
6. [A Sparse Glimpse of the Whole: Train-Free Self-Speculative Decoding](/202608/01/2607.27735v1-a-sparse-glimpse-of-the-whole-train-free-self-speculative-decoding) （9.0/10）
   evidence：用于推理效率提升的免训练投机解码
7. [Understanding Is Done Early: A Depth Division of Labor in Large Language Models and Its Use for Unbounded-Context Memory](/202608/01/2607.28263v1-understanding-is-done-early-a-depth-division-of-labor-in-large-language-models-and-its-use-for-unbounded-context-memory) （9.0/10）
   evidence：提出CoMem，通过中间层写入和查询条件上层重计算，使长上下文推理的计算与内存开销固定，属于推理效率优化。
8. [MANTA: Multi-Agent Network Topology Adaptation for Self-Evolving Multi-Agent Systems](/202608/01/2607.28527v1-manta-multi-agent-network-topology-adaptation-for-self-evolving-multi-agent-systems) （9.0/10）
   evidence：面向智能体集群的自演化拓扑调整与动态协作
9. [Matryoshka Agent: Unfolding Sub-Agents for Long-Horizon Machine Learning Engineering](/202608/01/2607.25090v1-matryoshka-agent-unfolding-sub-agents-for-long-horizon-machine-learning-engineering) （8.0/10）
   evidence：提出由编排器与子智能体组成的分层智能体框架，用于复杂长周期任务

## 速读区
1. [SVR: Self-Verifying Refinement via Joint Verdict-Confidence Reinforcement Learning for Adaptive Test-Time Compute](/202608/01/2607.28457v1-svr-self-verifying-refinement-via-joint-verdict-confidence-reinforcement-learning-for-adaptive-test-time-compute) （8.0/10）
   evidence：面向高效推理的自适应测试时计算
2. [TRACE-ROUTER: Task-Consistent and Adaptive Online Routing for Agentic AI](/202608/01/2607.22465v1-trace-router-task-consistent-and-adaptive-online-routing-for-agentic-ai) （7.0/10）
   evidence：面向LLM路由的成本-质量权衡优化，直接涉及推理效率。
3. [SKIMIX: Multi-Agent Harness-Time Scaling with Skill Mixture for Dynamic Harness Engineering](/202608/01/2607.27994v1-skimix-multi-agent-harness-time-scaling-with-skill-mixture-for-dynamic-harness-engineering) （7.0/10）
   evidence：多智能体技能混合与迭代协作机制与智能体集群架构需求相关。
4. [MemChain: Learning Interpretable Memory Traces for Memory-Augmented LLM Agents](/202608/01/2607.24097v1-memchain-learning-interpretable-memory-traces-for-memory-augmented-llm-agents) （6.0/10）
   evidence：降低记忆增强智能体的上下文开销，提升推理效率
5. [PLATO: Pointer Learner for Agent and Task Openness](/202608/01/2607.25082v1-plato-pointer-learner-for-agent-and-task-openness) （6.0/10）
   evidence：面向开放智能体系统的多智能体强化学习，处理智能体与任务动态变化，与智能体集群协作相关。
6. [Tools Are Not Islands: Set-Level Tool Retrieval for LLM Agents via Query-Conditioned Hyperedge Prediction](/202608/01/2607.25718v2-tools-are-not-islands-set-level-tool-retrieval-for-llm-agents-via-query-conditioned-hyperedge-prediction) （6.0/10）
   evidence：面向LLM智能体的集合级工具检索，支持自主工具使用
7. [dtControl2+$\varepsilon$: Trading Optimality for Explainability in MDPs via Decision Trees](/202608/01/2607.25925v1-dtcontrol2varepsilon-trading-optimality-for-explainability-in-mdps-via-decision-trees) （6.0/10）
   evidence：在MDP中用决策树蒸馏控制器策略，通过允许误差换取更小的可解释表示
8. [Kalman Meets Curriculum: Efficient Dynamic Prompt Selection for Adaptive RL Finetuning](/202608/01/2607.27610v1-kalman-meets-curriculum-efficient-dynamic-prompt-selection-for-adaptive-rl-finetuning) （6.0/10）
   evidence：卡尔曼引导的提示选择使推理RL微调更高效
9. [$Σ$-Mem: An Online Reliability Memory for LLM-based Multi-Agent Systems](/202608/01/2607.27958v1--mem-an-online-reliability-memory-for-llm-based-multi-agent-systems) （6.0/10）
   evidence：面向大模型多智能体系统的在线可靠性记忆，建模智能体可信度，为智能体集群协同与安全提供支持

---
使用键盘方向键可在日报/论文之间快速切换。
