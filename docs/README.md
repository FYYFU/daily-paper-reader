<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- [日报中心](/daily/README)

- 最新运行日期：2026-06-15
- 运行时间：2026-06-15 22:24:08 UTC
- 运行状态：成功
- 本次总论文数：28
- 精读区：14
- 速读区：14

### 今日简报（AI）
今日精选28篇论文，精读14篇，重点聚焦强化学习中的稀疏更新几何与世界模型自蒸馏，以及多智能体系统的结构记忆与安全自适应辩论。  
最值得关注的是《Dense Supervision, Sparse Updates》提出策略蒸馏的稀疏性与几何新视角，以及《World Model Self-Distillation》用自蒸馏训练世界模型解决通用任务；速读中《ConMem》的结构记忆引导无训练多智能体适应与《ARMOR-MAD》的异构辩论路由也值得深挖。  
普通读者建议优先精读两篇高分论文，并关注多智能体领域将安全约束（如控制障碍函数扩散模型）与自适应路由结合的实用方向。
- 详情：[/202606/15/README](/202606/15/README)

### 精读区论文标签
1. [Dense Supervision, Sparse Updates: On the Sparsity and Geometry of On-Policy Distillation](/202606/15/2606.13657v2-dense-supervision-sparse-updates-on-the-sparsity-and-geometry-of-on-policy-distillation)  
   标签：评分：10.0/10、query:opd
   evidence：明确研究在线策略蒸馏的动态与稀疏性
2. [World Model Self-Distillation: Training World Models to Solve General Tasks](/202606/15/2606.12072v1-world-model-self-distillation-training-world-models-to-solve-general-tasks)  
   标签：评分：9.0/10、query:opd
   evidence：结合自蒸馏和强化学习的世界模型训练
3. [Keep Policy Gradient in Charge: Sibling-Guided Credit Distillation for Long-Horizon Tool-Use Agents](/202606/15/2606.12634v1-keep-policy-gradient-in-charge-sibling-guided-credit-distillation-for-long-horizon-tool-use-agents)  
   标签：评分：9.0/10、query:opd
   evidence：直接提出RL蒸馏方法
4. [Multi-Turn Reasoning When Context Arrives in Pieces: Scalable Sharding and Memory-Augmented RL](/202606/15/2606.12941v2-multi-turn-reasoning-when-context-arrives-in-pieces-scalable-sharding-and-memory-augmented-rl)  
   标签：评分：9.0/10、query:l-context-rl
   evidence：通过记忆增强对长输入序列进行RL训练
5. [Diffusion Policy Optimization without Drifting Apart](/202606/15/2606.13795v1-diffusion-policy-optimization-without-drifting-apart)  
   标签：评分：9.0/10、query:opd
   evidence：扩散策略优化中的自蒸馏
6. [Safety-Contract Graph Multi-Agent Reinforcement Learning for Autonomous Network Security Response](/202606/15/2606.13832v1-safety-contract-graph-multi-agent-reinforcement-learning-for-autonomous-network-security-response)  
   标签：评分：9.0/10、query:ai-safety
   evidence：多智能体强化学习安全合约
7. [Capability Minimization as a Safety Primitive: Risk-Aware Causal Gating for Least-Privilege LLM Agents](/202606/15/2606.13884v1-capability-minimization-as-a-safety-primitive-risk-aware-causal-gating-for-least-privilege-llm-agents)  
   标签：评分：9.0/10、query:ai-safety
   evidence：风险感知因果门控实现安全LLM代理决策
8. [Contract-Based Compositional Shielding for Safe Multi-Agent Reinforcement Learning](/202606/15/2606.14130v1-contract-based-compositional-shielding-for-safe-multi-agent-reinforcement-learning)  
   标签：评分：9.0/10、query:ai-safety
   evidence：多智能体安全强化学习的组合屏蔽
9. [SkillMutator: Benchmarking and Defending Language-and-Code Cross-modal Attacks on LLM Agent Skills](/202606/15/2606.14154v1-skillmutator-benchmarking-and-defending-language-and-code-cross-modal-attacks-on-llm-agent-skills)  
   标签：评分：9.0/10、query:ai-safety
   evidence：对LLM智能体技能的跨模态攻击基准测试与防御
10. [ForceForget: Reinforcement Concept Removal for Enhancing Safety in Text-to-Image Models](/202606/15/2606.14351v1-forceforget-reinforcement-concept-removal-for-enhancing-safety-in-text-to-image-models)  
   标签：评分：9.0/10、query:ai-safety
   evidence：利用强化学习进行文本到图像模型的安全概念擦除
11. [Be My Tutor: On-Policy Co-Distillation for Mutual LLM Improvement via Peer Feedback](/202606/15/2606.14368v1-be-my-tutor-on-policy-co-distillation-for-mutual-llm-improvement-via-peer-feedback)  
   标签：评分：9.0/10、query:opd
   evidence：在线策略协同蒸馏实现模型相互提升
12. [CSPO: Constraint-Sensitive Policy Optimization for Safe Reinforcement Learning](/202606/15/2606.14415v1-cspo-constraint-sensitive-policy-optimization-for-safe-reinforcement-learning)  
   标签：评分：9.0/10、query:ai-safety
   evidence：提出带约束敏感修正的安全强化学习方法
13. [From Shield to Target: Denial-of-Service Attacks on LLM-Based Agent Guardrails](/202606/15/2606.14517v1-from-shield-to-target-denial-of-service-attacks-on-llm-based-agent-guardrails)  
   标签：评分：9.0/10、query:ai-safety
   evidence：针对LLM安全护栏的拒绝服务攻击，涉及越狱与防御
14. [Provably Safe, Yet Scalable Reinforcement Learning](/202606/15/2606.14536v1-provably-safe-yet-scalable-reinforcement-learning)  
   标签：评分：9.0/10、query:ai-safety
   evidence：具有形式化安全保证的可证明安全强化学习

### 速读区论文标签
1. [ConMem: Structured Memory-Guided Adaptation in Training-Free Multi-Agent Systems](/202606/15/2606.08702v1-conmem-structured-memory-guided-adaptation-in-training-free-multi-agent-systems)  
   标签：评分：8.0/10、query:agent-swarm
   evidence：多智能体系统的结构化记忆引导适应
2. [Individual Control Barrier Functions-Guided Diffusion Model for Safe Offline Multi-Agent Reinforcement Learning](/202606/15/2606.12640v1-individual-control-barrier-functions-guided-diffusion-model-for-safe-offline-multi-agent-reinforcement-learning)  
   标签：评分：8.0/10、query:ai-safety
   evidence：使用控制屏障函数和扩散模型的安全离线多智能体强化学习
3. [ARMOR-MAD: Adaptive Routing for Heterogeneous Multi-Agent Debate in Large Language Model Reasoning](/202606/15/2606.13197v1-armor-mad-adaptive-routing-for-heterogeneous-multi-agent-debate-in-large-language-model-reasoning)  
   标签：评分：8.0/10、query:eff-reason
   evidence：自适应路由实现高效多智能体辩论推理
4. [ReSum: Synergizing LLM Reasoning and Summarization with Reinforcement Learning](/202606/15/2606.13316v1-resum-synergizing-llm-reasoning-and-summarization-with-reinforcement-learning)  
   标签：评分：8.0/10、query:eff-reason
   evidence：通过自我摘要压缩推理轨迹以提升效率
5. [Beyond Runtime Enforcement: Shield Synthesis as Defensibility Analysis for Adversarial Networks](/202606/15/2606.13621v1-beyond-runtime-enforcement-shield-synthesis-as-defensibility-analysis-for-adversarial-networks)  
   标签：评分：8.0/10、query:ai-safety
   evidence：面向对抗RL的盾牌合成安全分析
6. [Back on Track: Aligning Rewards and States for Reasoning in Diffusion Large Language Models](/202606/15/2606.08501v1-back-on-track-aligning-rewards-and-states-for-reasoning-in-diffusion-large-language-models)  
   标签：评分：7.0/10、query:eff-reason
   evidence：为扩散大语言模型的推理对齐奖励与状态
7. [Momentum for Reasoning: Dense Intrinsic Signals in Policy Optimization](/202606/15/2606.08815v1-momentum-for-reasoning-dense-intrinsic-signals-in-policy-optimization)  
   标签：评分：7.0/10、query:eff-reason
   evidence：密集的内在信号改进推理策略优化
8. [Anything2Skill: Compiling External Knowledge into Reusable Skills for Agents](/202606/15/2606.09316v1-anything2skill-compiling-external-knowledge-into-reusable-skills-for-agents)  
   标签：评分：7.0/10、query:agent-swarm
   evidence：将外部知识编译为智能体可复用技能
9. [Fast and Highly Expressive Policy Learning for Offline Reinforcement Learning via Bootstrapped Flow Q-Learning](/202606/15/2606.10613v1-fast-and-highly-expressive-policy-learning-for-offline-reinforcement-learning-via-bootstrapped-flow-q-learning)  
   标签：评分：7.0/10、query:opd
   evidence：将策略蒸馏作为基线方法，提出无需蒸馏的替代方案
10. [Event-Driven Reinforcement Learning Enables Long-Horizon Control in Semiconductor Fabrication](/202606/15/2606.10705v1-event-driven-reinforcement-learning-enables-long-horizon-control-in-semiconductor-fabrication)  
   标签：评分：7.0/10、query:l-context-rl
   evidence：使用强化学习进行半导体制造中的长时程控制
11. [sGPO: Trading Inference FLOPs for Training Efficiency in RLVR](/202606/15/2606.08854v1-sgpo-trading-inference-flops-for-training-efficiency-in-rlvr)  
   标签：评分：6.0/10、query:eff-reason
   evidence：用推理FLOPs作为训练效率代理
12. [Learning What to Remember: Observability-Safe Memory Retention via Constrained Optimization for Long-Horizon Language Agents](/202606/15/2606.10616v2-learning-what-to-remember-observability-safe-memory-retention-via-constrained-optimization-for-long-horizon-language-agents)  
   标签：评分：6.0/10、query:l-context-rl
   evidence：长时程智能体记忆保留，可用于长上下文RL
13. [Effective Reinforcement Learning for Agentic Search by Recycling Zero-Variance Queries During Training](/202606/15/2606.10709v1-effective-reinforcement-learning-for-agentic-search-by-recycling-zero-variance-queries-during-training)  
   标签：评分：6.0/10、query:agent-swarm
   evidence：通过查询回收实现智能体搜索的强化学习
14. [Organize then Retrieve: Hierarchical Memory Navigation for Efficient Agents](/202606/15/2606.11680v1-organize-then-retrieve-hierarchical-memory-navigation-for-efficient-agents)  
   标签：评分：6.0/10、query:eff-reason
   evidence：基于层级记忆的高效智能体，提升推理效率


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
