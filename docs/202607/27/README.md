# 日报 · 2026-07-27

- 生成时间：2026-07-27 21:14:15 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日处理23篇论文，精读9篇，聚焦两大高分蒸馏方法。

重点推荐跨分词器策略蒸馏（10分）和混合后见自我蒸馏（9分），两者均显著提升LLM对齐效率。

建议深入这两篇论文的字节前缀边缘化与后见机制，验证能否简化蒸馏流程。

## 精读区
1. [Cross-Tokenizer On-Policy Distillation via Byte-Prefix Marginalization](/202607/27/2607.22334v1-cross-tokenizer-on-policy-distillation-via-byte-prefix-marginalization) （10.0/10）
   evidence：直接针对on-policy蒸馏，提出跨分词器的字节前缀边际化方法
2. [H$^2$SD: Hybrid Hindsight Self-Distillation](/202607/27/2607.18955v3-h2sd-hybrid-hindsight-self-distillation) （9.0/10）
   evidence：面向RLVR的混合事后自我蒸馏
3. [VDAR-Router: Adaptive LLMs Routing via Verbalized Query Difficulty Analysis Retrieval](/202607/27/2607.18098v1-vdar-router-adaptive-llms-routing-via-verbalized-query-difficulty-analysis-retrieval) （8.0/10）
   evidence：通过基于查询难度的自适应路由实现高效的LLM推理
4. [Operational Hallucination and Safety Drift in AI Agents](/202607/27/2607.18366v1-operational-hallucination-and-safety-drift-in-ai-agents) （8.0/10）
   evidence：AI智能体中的安全漂移和操作幻觉
5. [Guardrails as Scapegoats: Auditing Unfaithful Safety Refusals in Tool-Augmented LLM Agents](/202607/27/2607.19449v1-guardrails-as-scapegoats-auditing-unfaithful-safety-refusals-in-tool-augmented-llm-agents) （8.0/10）
   evidence：审计工具增强LLM代理中不诚实的安全拒绝
6. [Test-Time Scaling via Error Localization](/202607/27/2607.21453v2-test-time-scaling-via-error-localization) （8.0/10）
   evidence：通过错误定位实现测试时扩展
7. [Adjustment Speed as a Safety Constraint for Nonstationary Reinforcement Learning](/202607/27/2607.21646v1-adjustment-speed-as-a-safety-constraint-for-nonstationary-reinforcement-learning) （8.0/10）
   evidence：非平稳强化学习的安全约束
8. [QLPO: Quadrant-weighted Sampling for Length-aware Policy Optimization](/202607/27/2607.21793v1-qlpo-quadrant-weighted-sampling-for-length-aware-policy-optimization) （8.0/10）
   evidence：面向推理效率的长度感知策略优化
9. [Unified Static-Dynamic Pruning for Efficient LLM Inference](/202607/27/2607.21985v1-unified-static-dynamic-pruning-for-efficient-llm-inference) （8.0/10）
   evidence：通过统一静态动态剪枝实现高效的LLM推理

## 速读区
1. [Efficient Sequential Evaluation of Large Language Models](/202607/27/2607.17409v1-efficient-sequential-evaluation-of-large-language-models) （7.0/10）
   evidence：LLM的高效顺序评估
2. [A Geometric Perspective on Stabilizing Value Conflict Resolution](/202607/27/2607.17946v1-a-geometric-perspective-on-stabilizing-value-conflict-resolution) （7.0/10）
   evidence：通过思维链解决价值冲突，处理LLM中的安全问题
3. [Supra Cognitive Modes: A Routed Architecture for Agent Memory](/202607/27/2607.19096v1-supra-cognitive-modes-a-routed-architecture-for-agent-memory) （7.0/10）
   evidence：智能体记忆架构处理长历史，与长上下文RL相关
4. [Off-Context GRPO: Learning to Reason on Hard Problems using Privileged Information](/202607/27/2607.19313v1-off-context-grpo-learning-to-reason-on-hard-problems-using-privileged-information) （7.0/10）
   evidence：提出OC-GRPO方法，用于在难题上学习推理
5. [Robust Asynchronous Q-Learning under Reward and State Corruption via Batching](/202607/27/2607.20822v2-robust-asynchronous-q-learning-under-reward-and-state-corruption-via-batching) （7.0/10）
   evidence：对抗奖励和状态损坏的鲁棒强化学习
6. [TOUR: A Trajectory-Level Unlearning Benchmark for Offline Reinforcement Learning](/202607/27/2607.21111v1-tour-a-trajectory-level-unlearning-benchmark-for-offline-reinforcement-learning) （7.0/10）
   evidence：离线RL轨迹级遗忘基准用于安全评估
7. [FedAgentKE: Federated Semantic Knowledge Evolution for Heterogeneous Agents](/202607/27/2607.21361v1-fedagentke-federated-semantic-knowledge-evolution-for-heterogeneous-agents) （7.0/10）
   evidence：面向异构智能体的语义知识蒸馏
8. [PATS: Policy-Aware Training Scaffolding for Agentic Reinforcement Learning](/202607/27/2607.21419v1-pats-policy-aware-training-scaffolding-for-agentic-reinforcement-learning) （7.0/10）
   evidence：针对长视野agentic RL的策略感知训练脚手架
9. [Adaptive Undulatory Locomotion of Snake-like Robots in Dynamic Viscous Environments via Deep Reinforcement Learning](/202607/27/2607.21960v1-adaptive-undulatory-locomotion-of-snake-like-robots-in-dynamic-viscous-environments-via-deep-reinforcement-learning) （7.0/10）
   evidence：强化学习中师生蒸馏用于蛇形机器人运动
10. [VirtualSet: Typed Ontology Worlds as an LLM Generation Target for Grounded Queries and Guarded Decisions](/202607/27/2607.18821v2-virtualset-typed-ontology-worlds-as-an-llm-generation-target-for-grounded-queries-and-guarded-decisions) （6.0/10）
   evidence：类型化本体界面用于接地和安全的LLM生成
11. [Reasoning Error from Known Fact: Step-Level Self-Consistency Group Relative Policy Optimization for LLM](/202607/27/2607.18915v1-reasoning-error-from-known-fact-step-level-self-consistency-group-relative-policy-optimization-for-llm) （6.0/10）
   evidence：使用GRPO改进推理正确性
12. [AttriMem: Attribution-Guided Process Feedback for Agent Memory Learning](/202607/27/2607.21106v1-attrimem-attribution-guided-process-feedback-for-agent-memory-learning) （6.0/10）
   evidence：关注基于归因引导的RL反馈来学习智能体记忆，与智能体集群的记忆管理相关
13. [Explainable Belief Harmonization under Dynamic Epistemic Partitions](/202607/27/2607.21210v1-explainable-belief-harmonization-under-dynamic-epistemic-partitions) （6.0/10）
   evidence：多智能体信念协调
14. [Deconstructing Off-Policy Ratios: Entropy-Scaled Trust Regions for Asynchronous Reinforcement Learning](/202607/27/2607.22186v1-deconstructing-off-policy-ratios-entropy-scaled-trust-regions-for-asynchronous-reinforcement-learning) （6.0/10）
   evidence：异步强化学习用于大模型后训练，提出熵尺度信任域

---
使用键盘方向键可在日报/论文之间快速切换。
