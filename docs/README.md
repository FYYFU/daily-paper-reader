<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- [日报中心](/daily/README)

- 最新运行日期：2026-08-01
- 运行时间：2026-08-01 20:38:56 UTC
- 运行状态：成功
- 本次总论文数：18
- 精读区：9
- 速读区：9

### 今日简报（AI）
今日读18篇，精读9篇，核心围绕大模型蒸馏与推理优化。最值得看两篇满分工作：多模态在线自蒸馏（RP-OPSD）与轨迹中继蒸馏（Pass the Baton）。下一步可关注速读中的SVR自适应推理与TRACE-ROUTER智能体路由。
- 详情：[/202608/01/README](/202608/01/README)

### 精读区论文标签
1. [RP-OPSD: Resolution-Privileged On-Policy Self-Distillation for Multimodal Large Language Models](/202608/01/2607.24447v1-rp-opsd-resolution-privileged-on-policy-self-distillation-for-multimodal-large-language-models)  
   标签：评分：10.0/10、query:opd
   evidence：面向多模态大模型的在线策略自蒸馏
2. [Pass the Baton: Trajectory-Relayed On-Policy Distillation](/202608/01/2607.26057v1-pass-the-baton-trajectory-relayed-on-policy-distillation)  
   标签：评分：10.0/10、query:opd
   evidence：轨迹中继的在线策略蒸馏方法
3. [Flux-OPD: On-Policy Distillation with Evolving Contexts](/202608/01/2607.28022v1-flux-opd-on-policy-distillation-with-evolving-contexts)  
   标签：评分：10.0/10、query:opd
   evidence：直接提出用于大模型训练的在线策略蒸馏(OPD)方法，并引入演化上下文
4. [Forecasting Trajectory-Level Safety Risks in Black-Box Multi-Turn Interactions](/202608/01/2607.26820v1-forecasting-trajectory-level-safety-risks-in-black-box-multi-turn-interactions)  
   标签：评分：9.0/10、query:ai-safety
   evidence：面向LLM智能体多轮交互的轨迹级安全风险预测
5. [AgentS4D: Benchmarking Runtime Risks across the Execution Lifecycle of LLM-Based Workspace Agents](/202608/01/2607.27294v1-agents4d-benchmarking-runtime-risks-across-the-execution-lifecycle-of-llm-based-workspace-agents)  
   标签：评分：9.0/10、query:ai-safety
   evidence：提供面向LLM工作空间智能体运行时安全风险的基准
6. [A Sparse Glimpse of the Whole: Train-Free Self-Speculative Decoding](/202608/01/2607.27735v1-a-sparse-glimpse-of-the-whole-train-free-self-speculative-decoding)  
   标签：评分：9.0/10、query:eff-reason
   evidence：用于推理效率提升的免训练投机解码
7. [Understanding Is Done Early: A Depth Division of Labor in Large Language Models and Its Use for Unbounded-Context Memory](/202608/01/2607.28263v1-understanding-is-done-early-a-depth-division-of-labor-in-large-language-models-and-its-use-for-unbounded-context-memory)  
   标签：评分：9.0/10、query:eff-reason
   evidence：提出CoMem，通过中间层写入和查询条件上层重计算，使长上下文推理的计算与内存开销固定，属于推理效率优化。
8. [MANTA: Multi-Agent Network Topology Adaptation for Self-Evolving Multi-Agent Systems](/202608/01/2607.28527v1-manta-multi-agent-network-topology-adaptation-for-self-evolving-multi-agent-systems)  
   标签：评分：9.0/10、query:agent-swarm
   evidence：面向智能体集群的自演化拓扑调整与动态协作
9. [Matryoshka Agent: Unfolding Sub-Agents for Long-Horizon Machine Learning Engineering](/202608/01/2607.25090v1-matryoshka-agent-unfolding-sub-agents-for-long-horizon-machine-learning-engineering)  
   标签：评分：8.0/10、query:agent-swarm
   evidence：提出由编排器与子智能体组成的分层智能体框架，用于复杂长周期任务

### 速读区论文标签
1. [SVR: Self-Verifying Refinement via Joint Verdict-Confidence Reinforcement Learning for Adaptive Test-Time Compute](/202608/01/2607.28457v1-svr-self-verifying-refinement-via-joint-verdict-confidence-reinforcement-learning-for-adaptive-test-time-compute)  
   标签：评分：8.0/10、query:eff-reason
   evidence：面向高效推理的自适应测试时计算
2. [TRACE-ROUTER: Task-Consistent and Adaptive Online Routing for Agentic AI](/202608/01/2607.22465v1-trace-router-task-consistent-and-adaptive-online-routing-for-agentic-ai)  
   标签：评分：7.0/10、query:eff-reason
   evidence：面向LLM路由的成本-质量权衡优化，直接涉及推理效率。
3. [SKIMIX: Multi-Agent Harness-Time Scaling with Skill Mixture for Dynamic Harness Engineering](/202608/01/2607.27994v1-skimix-multi-agent-harness-time-scaling-with-skill-mixture-for-dynamic-harness-engineering)  
   标签：评分：7.0/10、query:agent-swarm
   evidence：多智能体技能混合与迭代协作机制与智能体集群架构需求相关。
4. [MemChain: Learning Interpretable Memory Traces for Memory-Augmented LLM Agents](/202608/01/2607.24097v1-memchain-learning-interpretable-memory-traces-for-memory-augmented-llm-agents)  
   标签：评分：6.0/10、query:eff-reason
   evidence：降低记忆增强智能体的上下文开销，提升推理效率
5. [PLATO: Pointer Learner for Agent and Task Openness](/202608/01/2607.25082v1-plato-pointer-learner-for-agent-and-task-openness)  
   标签：评分：6.0/10、query:agent-swarm
   evidence：面向开放智能体系统的多智能体强化学习，处理智能体与任务动态变化，与智能体集群协作相关。
6. [Tools Are Not Islands: Set-Level Tool Retrieval for LLM Agents via Query-Conditioned Hyperedge Prediction](/202608/01/2607.25718v2-tools-are-not-islands-set-level-tool-retrieval-for-llm-agents-via-query-conditioned-hyperedge-prediction)  
   标签：评分：6.0/10、query:agent-swarm
   evidence：面向LLM智能体的集合级工具检索，支持自主工具使用
7. [dtControl2+$\varepsilon$: Trading Optimality for Explainability in MDPs via Decision Trees](/202608/01/2607.25925v1-dtcontrol2varepsilon-trading-optimality-for-explainability-in-mdps-via-decision-trees)  
   标签：评分：6.0/10、query:opd
   evidence：在MDP中用决策树蒸馏控制器策略，通过允许误差换取更小的可解释表示
8. [Kalman Meets Curriculum: Efficient Dynamic Prompt Selection for Adaptive RL Finetuning](/202608/01/2607.27610v1-kalman-meets-curriculum-efficient-dynamic-prompt-selection-for-adaptive-rl-finetuning)  
   标签：评分：6.0/10、query:eff-reason
   evidence：卡尔曼引导的提示选择使推理RL微调更高效
9. [$Σ$-Mem: An Online Reliability Memory for LLM-based Multi-Agent Systems](/202608/01/2607.27958v1--mem-an-online-reliability-memory-for-llm-based-multi-agent-systems)  
   标签：评分：6.0/10、query:agent-swarm
   evidence：面向大模型多智能体系统的在线可靠性记忆，建模智能体可信度，为智能体集群协同与安全提供支持


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
