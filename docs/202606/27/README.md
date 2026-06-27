# 日报 · 2026-06-27

- 生成时间：2026-06-27 20:55:53 UTC
- 当次推荐总数：20
- 精读区：9
- 速读区：11

## 今日简报（AI）
今日聚焦两篇满分论文，深入探讨on-policy蒸馏中的位置偏差与输出多样性问题。  
最值得关注的方向是on-policy自蒸馏的缺陷——位置偏差导致模型偏好特定输出，而样本演示虽降低多样性却稳定了效果。  
建议优先精读两篇满分论文以理解蒸馏核心矛盾，再速读速读列表中的《Group-Graph Policy Optimization》拓展长序列强化学习视野。

## 精读区
1. [On the Position Bias of On-Policy Distillation](/202606/27/2606.22600v2-on-the-position-bias-of-on-policy-distillation) （10.0/10）
   evidence：在线策略蒸馏中的位置偏差
2. [On-Policy Self-Distillation with Sampled Demonstrations Reduces Output Diversity](/202606/27/2606.26091v1-on-policy-self-distillation-with-sampled-demonstrations-reduces-output-diversity) （10.0/10）
   evidence：在线策略自蒸馏降低输出多样性
3. [Paved with True Intents: Intent-Aware Training Improves LLM Safety Classification Across Training Regimes](/202606/27/2606.27210v1-paved-with-true-intents-intent-aware-training-improves-llm-safety-classification-across-training-regimes) （10.0/10）
   evidence：意图感知训练提升LLM安全分类
4. [Beyond Trajectory Imitation: Strategy-Guided Policy Optimization for LLM Reasoning](/202606/27/2606.24064v1-beyond-trajectory-imitation-strategy-guided-policy-optimization-for-llm-reasoning) （9.0/10）
   evidence：使用策略优化的LLM推理策略蒸馏
5. [ReM-MoA: Reasoning Memory Sustains Mixture-of-Agents Scaling](/202606/27/2606.24437v1-rem-moa-reasoning-memory-sustains-mixture-of-agents-scaling) （9.0/10）
   evidence：用于扩展智能体集群的记忆增强混合智能体框架
6. [FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Calibrated Warm-up and Self-Distillation](/202606/27/2606.26006v1-force-efficient-vla-reinforcement-fine-tuning-via-value-calibrated-warm-up-and-self-distillation) （9.0/10）
   evidence：使用on-policy rollout和自蒸馏进行VLA微调，直接与on-policy蒸馏相关
7. [AutoSpec: Safety Rule Evolution for LLM Agents via Inductive Logic Programming](/202606/27/2606.24245v2-autospec-safety-rule-evolution-for-llm-agents-via-inductive-logic-programming) （8.0/10）
   evidence：AutoSpec自动演化LLM智能体安全规则
8. [Reasoning as Attractor Dynamics: Latent Memory Retrieval via Gibbs-Weighted Energy Minimization](/202606/27/2606.24543v1-reasoning-as-attractor-dynamics-latent-memory-retrieval-via-gibbs-weighted-energy-minimization) （8.0/10）
   evidence：通过吸引子动力学和吉布斯加权能量最小化实现高效推理
9. [What Does It Mean to Break a Distillation Defense?](/202606/27/2606.25059v1-what-does-it-mean-to-break-a-distillation-defense) （8.0/10）
   evidence：对抗蒸馏攻击的防御机制

## 速读区
1. [Group-Graph Policy Optimization for Long-Horizon Agentic Reinforcement Learning](/202606/27/2606.22995v1-group-graph-policy-optimization-for-long-horizon-agentic-reinforcement-learning) （8.0/10）
   evidence：长视界智能体强化学习采用组图策略优化
2. [Weight-Space Geometry of Offline Reasoning Training](/202606/27/2606.23740v1-weight-space-geometry-of-offline-reasoning-training) （8.0/10）
   evidence：离线强化学习蒸馏损失分析用于推理
3. [Finding the Time to Think: Learning Planning Budgets in Real-Time RL](/202606/27/2606.26463v1-finding-the-time-to-think-learning-planning-budgets-in-real-time-rl) （8.0/10）
   evidence：在实时强化学习中学习规划预算以实现高效思考
4. [Autoformalization of Agent Instructions into Policy-as-Code](/202606/27/2606.26649v1-autoformalization-of-agent-instructions-into-policy-as-code) （8.0/10）
   evidence：自动形式化代理安全策略
5. [Hallucination as Context Drift: Synchronization Protocols for Multi-Agent LLM Systems](/202606/27/2606.21666v1-hallucination-as-context-drift-synchronization-protocols-for-multi-agent-llm-systems) （7.0/10）
   evidence：解决多智能体LLM系统中的上下文漂移问题，提出同步协议
6. [Escaping the Self-Confirmation Trap: An Execute-Distill-Verify Paradigm for Agentic Experience Learning](/202606/27/2606.24428v1-escaping-the-self-confirmation-trap-an-execute-distill-verify-paradigm-for-agentic-experience-learning) （7.0/10）
   evidence：用于智能体经验学习的多智能体执行-蒸馏-验证范式
7. [Lifelong In-Context Learning with Transformers Requires Parametric Forms of Attention](/202606/27/2606.25342v1-lifelong-in-context-learning-with-transformers-requires-parametric-forms-of-attention) （7.0/10）
   evidence：用于长序列终身上下文学习的参数化注意力
8. [Offline Multi-agent Continual Cooperation via Skill Partition and Reuse](/202606/27/2606.25389v1-offline-multi-agent-continual-cooperation-via-skill-partition-and-reuse) （7.0/10）
   evidence：多智能体持续协作；面向集群的技能划分与复用
9. [VADAOrchestra: Neurosymbolic Orchestration of Adaptive Reasoning Workflows](/202606/27/2606.22485v2-vadaorchestra-neurosymbolic-orchestration-of-adaptive-reasoning-workflows) （6.0/10）
   evidence：结合智能体LLM的自适应推理工作流神经符号编排
10. [PolicyTrim: Boosting Intrinsic Policy Efficiency of Vision-Language-Action Models](/202606/27/2606.22540v2-policytrim-boosting-intrinsic-policy-efficiency-of-vision-language-action-models) （6.0/10）
   evidence：提升VLA策略的推理效率
11. [PolicyTrim: Boosting Intrinsic Policy Efficiency of Vision-Language-Action Models](/202606/27/2606.22540v3-policytrim-boosting-intrinsic-policy-efficiency-of-vision-language-action-models) （6.0/10）
   evidence：通过优化行动块长度和物理步骤提升VLA模型的内在策略效率，与高效推理相关

---
使用键盘方向键可在日报/论文之间快速切换。
