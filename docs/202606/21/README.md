# 日报 · 2026-06-21

- 生成时间：2026-06-21 21:00:48 UTC
- 当次推荐总数：17
- 精读区：9
- 速读区：8

## 今日简报（AI）
多模态推理与策略蒸馏成为今日研究焦点，精读收获两篇10分论文。  
最值得看的方向：感知-推理解耦对抗捷径鲁棒性（《Seeing Before Reasoning》）以及多轮策略蒸馏中的智能体干预（《SAGE-OPD》），速读中类型推理与图策略优化也值得一读。  
建议关注这些论文中“先感知后推理”的设计逻辑，并尝试将解耦思路迁移到实际多模态任务中。

## 精读区
1. [Seeing Before Reasoning: Decoupling Perception and Reasoning for Shortcut-Resilient Multimodal On-Policy Self-Distillation](/202606/21/2606.19120v1-seeing-before-reasoning-decoupling-perception-and-reasoning-for-shortcut-resilient-multimodal-on-policy-self-distillation) （10.0/10）
   evidence：直接研究多模态大语言模型上的在线自蒸馏方法
2. [SAGE-OPD: Selective Agent-Guided Intervention for Multi-Turn On-Policy Distillation](/202606/21/2606.19659v1-sage-opd-selective-agent-guided-intervention-for-multi-turn-on-policy-distillation) （10.0/10）
   evidence：多轮on-policy蒸馏与选择性干预
3. [LLM agent safety, multi-turn red-teaming, jailbreak benchmarks, adversarial robustness, safety-critical systems](/202606/21/2606.20408v1-llm-agent-safety-multi-turn-red-teaming-jailbreak-benchmarks-adversarial-robustness-safety-critical-systems) （10.0/10）
   evidence：提出了NRT-Bench，一个针对安全关键系统中LLM智能体的多轮红队测试基准
4. [FragFuse: Bypassing Access Control of Large Language Model Agents via Memory-Based Query Fragmentation and Fusion](/202606/21/2606.15609v1-fragfuse-bypassing-access-control-of-large-language-model-agents-via-memory-based-query-fragmentation-and-fusion) （9.0/10）
   evidence：通过内存分片和融合的越狱攻击
5. [Let Them Steal: Trapping Large Language Model Extraction Attacks with Knowledge Honeypot](/202606/21/2606.15810v1-let-them-steal-trapping-large-language-model-extraction-attacks-with-knowledge-honeypot) （9.0/10）
   evidence：通过知识蜜罐防御模型提取攻击
6. [PowerOPD: Stabilizing On-Policy Distillation with Bounded Power Transformation](/202606/21/2606.17199v1-poweropd-stabilizing-on-policy-distillation-with-bounded-power-transformation) （9.0/10）
   evidence：通过有界幂变换稳定LLM的在线策略蒸馏
7. [Visual-OPSD: Cross-Modal On-Policy Self-Distillation for Efficient Unified Multimodal Reasoning](/202606/21/2606.18974v1-visual-opsd-cross-modal-on-policy-self-distillation-for-efficient-unified-multimodal-reasoning) （9.0/10）
   evidence：跨模态在线策略自蒸馏
8. [TRIDENT: Breaking the Hybrid-Safety-Physics Coupling for Provably Safe Multi-Agent Reinforcement Learning](/202606/21/2606.18308v1-trident-breaking-the-hybrid-safety-physics-coupling-for-provably-safe-multi-agent-reinforcement-learning) （8.0/10）
   evidence：具有可证明安全保证的多智能体强化学习
9. [ToolChain-CRC: Conformal Risk Control for Agentic AI Under Retrieval and Tool-Use Drift](/202606/21/2606.18467v1-toolchain-crc-conformal-risk-control-for-agentic-ai-under-retrieval-and-tool-use-drift) （8.0/10）
   evidence：智能体AI的安全风险控制

## 速读区
1. [Tyler: Typed Latent Reasoning for Language Models -- When to Think, What to Compute, and How Much to Allocate](/202606/21/2606.16360v1-tyler-typed-latent-reasoning-for-language-models----when-to-think-what-to-compute-and-how-much-to-allocate) （8.0/10）
   evidence：类型化潜在推理实现高效计算分配
2. [GraphPO: Graph-based Policy Optimization for Reasoning Models](/202606/21/2606.18954v1-graphpo-graph-based-policy-optimization-for-reasoning-models) （8.0/10）
   evidence：基于图的策略优化通过共享推理状态减少冗余步骤
3. [Manifold Bandits: Bayesian Curriculum Learning over the Latent Geometry of Large Language Models](/202606/21/2606.19750v1-manifold-bandits-bayesian-curriculum-learning-over-the-latent-geometry-of-large-language-models) （8.0/10）
   evidence：基于潜在几何的贝叶斯课程学习提升RL训练效率
4. [Playful Agentic Robot Learning](/202606/21/2606.19419v1-playful-agentic-robot-learning) （7.0/10）
   evidence：通过自主游戏将成功执行蒸馏为技能库
5. [Uncertainty-Aware Reward Modeling for Stable RLHF](/202606/21/2606.19818v1-uncertainty-aware-reward-modeling-for-stable-rlhf) （7.0/10）
   evidence：解决RLHF中奖励模型不确定性和奖励黑客问题，涉及模型安全
6. [Process-Verified Reinforcement Learning for Theorem Proving via Lean](/202606/21/2606.20068v1-process-verified-reinforcement-learning-for-theorem-proving-via-lean) （7.0/10）
   evidence：利用Lean提供的密集验证反馈进行定理证明的强化学习
7. [PACT: Privileged Trace Co-Training for Multi-Turn Tool-Use Agents](/202606/21/2606.16215v1-pact-privileged-trace-co-training-for-multi-turn-tool-use-agents) （6.0/10）
   evidence：通过特权轨迹共训练的师生框架
8. [ExpRL: Exploratory RL for LLM Mid-Training](/202606/21/2606.17024v1-exprl-exploratory-rl-for-llm-mid-training) （6.0/10）
   evidence：基于RL的自动提升LLM推理覆盖率的中间训练方法

---
使用键盘方向键可在日报/论文之间快速切换。
