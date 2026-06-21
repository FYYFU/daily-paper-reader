<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- [日报中心](/daily/README)

- 最新运行日期：2026-06-21
- 运行时间：2026-06-21 21:00:48 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：9
- 速读区：8

### 今日简报（AI）
今日17篇论文聚焦多模态自蒸馏与推理模型优化，两篇满分论文分别提出解耦感知-推理的短路鲁棒方法及智能体引导的多轮蒸馏。

最值得看的两个方向：《Seeing Before Reasoning》的感知-推理解耦策略有效避免捷径，以及《SAGE-OPD》的选择性智能体干预显著提升多轮蒸馏效果。

建议优先精读这两篇满分论文，理解解耦蒸馏与智能体引导的核心思路；速读可快速浏览Tyler的推理计算分配和GraphPO的图优化方法。
- 详情：[/202606/21/README](/202606/21/README)

### 精读区论文标签
1. [Seeing Before Reasoning: Decoupling Perception and Reasoning for Shortcut-Resilient Multimodal On-Policy Self-Distillation](/202606/21/2606.19120v1-seeing-before-reasoning-decoupling-perception-and-reasoning-for-shortcut-resilient-multimodal-on-policy-self-distillation)  
   标签：评分：10.0/10、query:opd
   evidence：直接研究多模态大语言模型上的在线自蒸馏方法
2. [SAGE-OPD: Selective Agent-Guided Intervention for Multi-Turn On-Policy Distillation](/202606/21/2606.19659v1-sage-opd-selective-agent-guided-intervention-for-multi-turn-on-policy-distillation)  
   标签：评分：10.0/10、query:opd
   evidence：多轮on-policy蒸馏与选择性干预
3. [LLM agent safety, multi-turn red-teaming, jailbreak benchmarks, adversarial robustness, safety-critical systems](/202606/21/2606.20408v1-llm-agent-safety-multi-turn-red-teaming-jailbreak-benchmarks-adversarial-robustness-safety-critical-systems)  
   标签：评分：10.0/10、query:ai-safety
   evidence：提出了NRT-Bench，一个针对安全关键系统中LLM智能体的多轮红队测试基准
4. [FragFuse: Bypassing Access Control of Large Language Model Agents via Memory-Based Query Fragmentation and Fusion](/202606/21/2606.15609v1-fragfuse-bypassing-access-control-of-large-language-model-agents-via-memory-based-query-fragmentation-and-fusion)  
   标签：评分：9.0/10、query:ai-safety
   evidence：通过内存分片和融合的越狱攻击
5. [Let Them Steal: Trapping Large Language Model Extraction Attacks with Knowledge Honeypot](/202606/21/2606.15810v1-let-them-steal-trapping-large-language-model-extraction-attacks-with-knowledge-honeypot)  
   标签：评分：9.0/10、query:ai-safety
   evidence：通过知识蜜罐防御模型提取攻击
6. [PowerOPD: Stabilizing On-Policy Distillation with Bounded Power Transformation](/202606/21/2606.17199v1-poweropd-stabilizing-on-policy-distillation-with-bounded-power-transformation)  
   标签：评分：9.0/10、query:opd
   evidence：通过有界幂变换稳定LLM的在线策略蒸馏
7. [Visual-OPSD: Cross-Modal On-Policy Self-Distillation for Efficient Unified Multimodal Reasoning](/202606/21/2606.18974v1-visual-opsd-cross-modal-on-policy-self-distillation-for-efficient-unified-multimodal-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：跨模态在线策略自蒸馏
8. [TRIDENT: Breaking the Hybrid-Safety-Physics Coupling for Provably Safe Multi-Agent Reinforcement Learning](/202606/21/2606.18308v1-trident-breaking-the-hybrid-safety-physics-coupling-for-provably-safe-multi-agent-reinforcement-learning)  
   标签：评分：8.0/10、query:ai-safety
   evidence：具有可证明安全保证的多智能体强化学习
9. [ToolChain-CRC: Conformal Risk Control for Agentic AI Under Retrieval and Tool-Use Drift](/202606/21/2606.18467v1-toolchain-crc-conformal-risk-control-for-agentic-ai-under-retrieval-and-tool-use-drift)  
   标签：评分：8.0/10、query:ai-safety
   evidence：智能体AI的安全风险控制

### 速读区论文标签
1. [Tyler: Typed Latent Reasoning for Language Models -- When to Think, What to Compute, and How Much to Allocate](/202606/21/2606.16360v1-tyler-typed-latent-reasoning-for-language-models----when-to-think-what-to-compute-and-how-much-to-allocate)  
   标签：评分：8.0/10、query:eff-reason
   evidence：类型化潜在推理实现高效计算分配
2. [GraphPO: Graph-based Policy Optimization for Reasoning Models](/202606/21/2606.18954v1-graphpo-graph-based-policy-optimization-for-reasoning-models)  
   标签：评分：8.0/10、query:eff-reason
   evidence：基于图的策略优化通过共享推理状态减少冗余步骤
3. [Manifold Bandits: Bayesian Curriculum Learning over the Latent Geometry of Large Language Models](/202606/21/2606.19750v1-manifold-bandits-bayesian-curriculum-learning-over-the-latent-geometry-of-large-language-models)  
   标签：评分：8.0/10、query:eff-reason
   evidence：基于潜在几何的贝叶斯课程学习提升RL训练效率
4. [Playful Agentic Robot Learning](/202606/21/2606.19419v1-playful-agentic-robot-learning)  
   标签：评分：7.0/10、query:opd
   evidence：通过自主游戏将成功执行蒸馏为技能库
5. [Uncertainty-Aware Reward Modeling for Stable RLHF](/202606/21/2606.19818v1-uncertainty-aware-reward-modeling-for-stable-rlhf)  
   标签：评分：7.0/10、query:ai-safety
   evidence：解决RLHF中奖励模型不确定性和奖励黑客问题，涉及模型安全
6. [Process-Verified Reinforcement Learning for Theorem Proving via Lean](/202606/21/2606.20068v1-process-verified-reinforcement-learning-for-theorem-proving-via-lean)  
   标签：评分：7.0/10、query:eff-reason
   evidence：利用Lean提供的密集验证反馈进行定理证明的强化学习
7. [PACT: Privileged Trace Co-Training for Multi-Turn Tool-Use Agents](/202606/21/2606.16215v1-pact-privileged-trace-co-training-for-multi-turn-tool-use-agents)  
   标签：评分：6.0/10、query:opd
   evidence：通过特权轨迹共训练的师生框架
8. [ExpRL: Exploratory RL for LLM Mid-Training](/202606/21/2606.17024v1-exprl-exploratory-rl-for-llm-mid-training)  
   标签：评分：6.0/10、query:eff-reason
   evidence：基于RL的自动提升LLM推理覆盖率的中间训练方法


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
