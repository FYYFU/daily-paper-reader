# 日报 · 2026-06-14

- 生成时间：2026-06-14 20:44:46 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日精读9篇、速读14篇，重点覆盖强化学习对手防御与策略蒸馏的稀疏性几何分析。最值得关注的是《PolicyGuard》的测试时逐层对抗防御机制，以及《Dense Supervision, Sparse Updates》揭示的在线蒸馏稀疏性与几何规律；三篇速读中《MAStrike》的Shapley引导多智能体红队攻击和《Multi-Turn Reasoning》的分片记忆推理也具启发性。建议普通读者优先深入强化学习的鲁棒性与效率优化，特别是攻防场景下的实际部署瓶颈。

## 精读区
1. [PolicyGuard: Towards Test-time and Step-level Adversary Defense for Reinforcement Learning Agent](/202606/14/2606.12896v1-policyguard-towards-test-time-and-step-level-adversary-defense-for-reinforcement-learning-agent) （10.0/10）
   evidence：RL智能体测试时步骤级后门防御
2. [Dense Supervision, Sparse Updates: On the Sparsity and Geometry of On-Policy Distillation](/202606/14/2606.13657v1-dense-supervision-sparse-updates-on-the-sparsity-and-geometry-of-on-policy-distillation) （10.0/10）
   evidence：在线策略蒸馏的稀疏性和几何分析
3. [HIPIF: Hierarchical Planning and Information Folding for Long-Horizon LLM Agent Learning](/202606/14/2606.10507v1-hipif-hierarchical-planning-and-information-folding-for-long-horizon-llm-agent-learning) （9.0/10）
   evidence：长上下文干扰问题下的分层强化学习方法
4. [SAIGuard: Communication-State Simulation for Proactive Defense of LLM Multi-Agent Systems](/202606/14/2606.12474v1-saiguard-communication-state-simulation-for-proactive-defense-of-llm-multi-agent-systems) （9.0/10）
   evidence：面向LLM多智能体系统的主动防御
5. [Keep Policy Gradient in Charge: Sibling-Guided Credit Distillation for Long-Horizon Tool-Use Agents](/202606/14/2606.12634v1-keep-policy-gradient-in-charge-sibling-guided-credit-distillation-for-long-horizon-tool-use-agents) （9.0/10）
   evidence：强化学习中的自蒸馏方法应用于长程工具使用智能体，直接涉及RL蒸馏
6. [Individual Control Barrier Functions-Guided Diffusion Model for Safe Offline Multi-Agent Reinforcement Learning](/202606/14/2606.12640v1-individual-control-barrier-functions-guided-diffusion-model-for-safe-offline-multi-agent-reinforcement-learning) （9.0/10）
   evidence：使用控制屏障函数和扩散模型的安全离线多智能体强化学习
7. [Smarter Saboteurs, Better Fixers: Scaling & Security in Linear Multi-Agent Workflows](/202606/14/2606.12709v1-smarter-saboteurs-better-fixers-scaling--security-in-linear-multi-agent-workflows) （9.0/10）
   evidence：多智能体工作流中的智能体安全
8. [Learning to Reason by Analogy via Retrieval-Augmented Reinforcement Fine-Tuning](/202606/14/2606.13680v1-learning-to-reason-by-analogy-via-retrieval-augmented-reinforcement-fine-tuning) （9.0/10）
   evidence：使用黄金相关蒸馏训练检索器，并用强化微调优化策略，直接匹配RL中的蒸馏技术
9. [ConMem: Structured Memory-Guided Adaptation in Training-Free Multi-Agent Systems](/202606/14/2606.08702v1-conmem-structured-memory-guided-adaptation-in-training-free-multi-agent-systems) （8.0/10）
   evidence：多智能体系统通过记忆蒸馏实现协调，与智能体集群架构相关

## 速读区
1. [Can the Environment Speak for Itself? $T^{2}$-GRPO: A Turn-Trajectory Group Relative Policy Optimization for Caregiver Agents](/202606/14/2606.08875v1-can-the-environment-speak-for-itself-t2-grpo-a-turn-trajectory-group-relative-policy-optimization-for-caregiver-agents) （8.0/10）
   evidence：护理场景中的智能体安全强化学习
2. [MAStrike: Shapley-Guided Collusive Red-Teaming on Multi-Agent Systems](/202606/14/2606.12918v1-mastrike-shapley-guided-collusive-red-teaming-on-multi-agent-systems) （8.0/10）
   evidence：多智能体系统上的协同红队测试
3. [Multi-Turn Reasoning When Context Arrives in Pieces: Scalable Sharding and Memory-Augmented RL](/202606/14/2606.12941v1-multi-turn-reasoning-when-context-arrives-in-pieces-scalable-sharding-and-memory-augmented-rl) （8.0/10）
   evidence：基于记忆的强化学习用于多轮长上下文推理
4. [ARMOR-MAD: Adaptive Routing for Heterogeneous Multi-Agent Debate in Large Language Model Reasoning](/202606/14/2606.13197v1-armor-mad-adaptive-routing-for-heterogeneous-multi-agent-debate-in-large-language-model-reasoning) （8.0/10）
   evidence：自适应路由提升多智能体推理效率
5. [ReSum: Synergizing LLM Reasoning and Summarization with Reinforcement Learning](/202606/14/2606.13316v1-resum-synergizing-llm-reasoning-and-summarization-with-reinforcement-learning) （8.0/10）
   evidence：利用自摘要提升RLVR推理效率
6. [Personalized and Robust Proactive Robot Assistance with Uncertainty-Guided LLM Reasoning](/202606/14/2606.08458v1-personalized-and-robust-proactive-robot-assistance-with-uncertainty-guided-llm-reasoning) （7.0/10）
   evidence：不确定性引导的高效LLM推理
7. [Rethinking the Divergence Regularization in LLM RL](/202606/14/2606.09821v1-rethinking-the-divergence-regularization-in-llm-rl) （7.0/10）
   evidence：讨论LLM RL中的散度正则化，与on-policy蒸馏方法相关
8. [An Agency-Transferring Model-Free Policy Enhancement Technique](/202606/14/2606.09825v1-an-agency-transferring-model-free-policy-enhancement-technique) （7.0/10）
   evidence：从基线策略向学习策略转移代理权的RL方法
9. [Game-Theoretic Multi-Agent Control for Robust Contextual Reasoning in LLMs](/202606/14/2606.10322v1-game-theoretic-multi-agent-control-for-robust-contextual-reasoning-in-llms) （7.0/10）
   evidence：基于博弈论的防御提示注入和上下文投毒
10. [Learning What to Remember: Observability-Safe Memory Retention via Constrained Optimization for Long-Horizon Language Agents](/202606/14/2606.10616v1-learning-what-to-remember-observability-safe-memory-retention-via-constrained-optimization-for-long-horizon-language-agents) （7.0/10）
   evidence：长时域智能体通过约束优化进行记忆保留
11. [CATPO: Critique-Augmented Tree Policy Optimization](/202606/14/2606.08346v1-catpo-critique-augmented-tree-policy-optimization) （6.0/10）
   evidence：通过树信息评分减少推理强化学习中的计算浪费
12. [Learnable Token Sparsification for Efficient Gigapixel Whole Slide Image Reasoning](/202606/14/2606.08641v1-learnable-token-sparsification-for-efficient-gigapixel-whole-slide-image-reasoning) （6.0/10）
   evidence：用于千兆像素图像高效推理的可训练令牌稀疏化
13. [Distilling Safe LLM Systems via Soft Prompts for On Device Settings](/202606/14/2606.09388v1-distilling-safe-llm-systems-via-soft-prompts-for-on-device-settings) （6.0/10）
   evidence：基于蒸馏的端侧大模型安全对齐
14. [Demystifying Hidden-State Recurrence: Switchable Latent Reasoning with On-Policy Reinforcement Learning](/202606/14/2606.13106v1-demystifying-hidden-state-recurrence-switchable-latent-reasoning-with-on-policy-reinforcement-learning) （6.0/10）
   evidence：使用在线强化学习的可切换潜在推理，压缩推理过程

---
使用键盘方向键可在日报/论文之间快速切换。
