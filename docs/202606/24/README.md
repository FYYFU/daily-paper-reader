# 日报 · 2026-06-24

- 生成时间：2026-06-24 22:05:06 UTC
- 当次推荐总数：29
- 精读区：15
- 速读区：14

## 今日简报（AI）
1) 今日聚焦强化学习安全基准测试(CRAX)与在线策略蒸馏位置偏差两篇满分论文，并涉及分层控制、上下文压缩及多轮编码智能体安全等关键议题。
2) 最值得精读的是《CRAX》提出的快速安全RL基准框架，以及《On the Position Bias of On-Policy Distillation》揭示的蒸馏位置偏差现象，均为10/10分。
3) 建议普通读者优先精读这两篇满分论文，再根据兴趣选择长上下文智能体安全或可解释安全导向等速读工作。

## 精读区
1. [CRAX: Fast Safe Reinforcement Learning Benchmarking](/202606/24/2606.20376v2-crax-fast-safe-reinforcement-learning-benchmarking) （10.0/10）
   evidence：安全强化学习基准测试
2. [On the Position Bias of On-Policy Distillation](/202606/24/2606.22600v1-on-the-position-bias-of-on-policy-distillation) （10.0/10）
   evidence：强化学习中的策略蒸馏
3. [On the Position Bias of On-Policy Distillation](/202606/24/2606.22600v2-on-the-position-bias-of-on-policy-distillation) （10.0/10）
   evidence：直接研究在线策略蒸馏，发现位置偏差并提出改进权重
4. [ReNIO: Reweighting Negative Trajectory Importance for LLM On-Policy Distillation](/202606/24/2606.23104v1-renio-reweighting-negative-trajectory-importance-for-llm-on-policy-distillation) （10.0/10）
   evidence：基于负轨迹重加权的LLM在线策略蒸馏
5. [Reinforcement Learning Towards Broadly and Persistently Beneficial Models](/202606/24/2606.24014v1-reinforcement-learning-towards-broadly-and-persistently-beneficial-models) （10.0/10）
   evidence：强化学习对齐与安全
6. [Beyond Trajectory Imitation: Strategy-Guided Policy Optimization for LLM Reasoning](/202606/24/2606.24064v1-beyond-trajectory-imitation-strategy-guided-policy-optimization-for-llm-reasoning) （10.0/10）
   evidence：面向大语言模型推理的策略引导策略优化蒸馏
7. [Blockwise Policy-Drift Gating for On-Policy Distillation](/202606/24/2606.24084v1-blockwise-policy-drift-gating-for-on-policy-distillation) （10.0/10）
   evidence：提出块级策略漂移门控用于在策略蒸馏OPD直接解决OPD在长期任务中的脆弱性问题
8. [AsyncOPD: How Stale Can On-Policy Distillation Be?](/202606/24/2606.24143v1-asyncopd-how-stale-can-on-policy-distillation-be) （10.0/10）
   evidence：直接研究大语言模型后训练中的在线策略蒸馏（OPD）及异步流水线
9. [Local LLM Agents as Vulnerable Runtimes:A Source-Code Audit of the Agent Runtime Layer](/202606/24/2606.21071v1-local-llm-agents-as-vulnerable-runtimesa-source-code-audit-of-the-agent-runtime-layer) （9.0/10）
   evidence：本地LLM智能体运行时安全性审计
10. [The Geometry of Refusal: Linear Instability in Safety-Aligned LLMs](/202606/24/2606.22686v1-the-geometry-of-refusal-linear-instability-in-safety-aligned-llms) （9.0/10）
   evidence：通过对比对数导向揭示安全对齐的脆弱性和越狱方法
11. [Beyond Penalizing Mistakes: Stabilizing Efficiency Training in Large Reasoning Models via Adaptive Correct-Only Rewards](/202606/24/2606.22716v1-beyond-penalizing-mistakes-stabilizing-efficiency-training-in-large-reasoning-models-via-adaptive-correct-only-rewards) （9.0/10）
   evidence：自适应正确奖励稳定推理模型效率训练
12. [A Formula-Driven Survey and Research Agenda for On-Policy Distillation](/202606/24/2606.22793v1-a-formula-driven-survey-and-research-agenda-for-on-policy-distillation) （9.0/10）
   evidence：在线策略蒸馏综述
13. [Finding the Evidence: Discovering Decision-Supporting Tokens for On-Policy Reasoning Distillation](/202606/24/2606.22830v1-finding-the-evidence-discovering-decision-supporting-tokens-for-on-policy-reasoning-distillation) （9.0/10）
   evidence：基于策略的推理蒸馏，发现决策和证据令牌
14. [SPIRAL: Learning to Search and Aggregate](/202606/24/2606.23595v1-spiral-learning-to-search-and-aggregate) （9.0/10）
   evidence：通过RL训练实现高效的搜索与聚合推理
15. [PixJail: Self-Evolving Paper-to-Pipeline Reproduction for Text-to-Image Jailbreak Evaluation](/202606/24/2606.24081v1-pixjail-self-evolving-paper-to-pipeline-reproduction-for-text-to-image-jailbreak-evaluation) （9.0/10）
   evidence：文本到图像越狱评估框架

## 速读区
1. [Imagine to Ensure Safety in Hierarchical Reinforcement Learning](/202606/24/2606.22509v1-imagine-to-ensure-safety-in-hierarchical-reinforcement-learning) （8.0/10）
   evidence：分层强化学习中的安全探索
2. [Governance Decay: How Context Compaction Silently Erases Safety Constraints in Long-Horizon LLM Agents](/202606/24/2606.22528v1-governance-decay-how-context-compaction-silently-erases-safety-constraints-in-long-horizon-llm-agents) （8.0/10）
   evidence：上下文压缩导致长程LLM智能体安全约束失效，并引入新基准
3. [AgentLens: Interpretable Safety Steering via Mechanistic Subspaces for Multi-Turn Coding Agent](/202606/24/2606.22673v1-agentlens-interpretable-safety-steering-via-mechanistic-subspaces-for-multi-turn-coding-agent) （8.0/10）
   evidence：通过机制可解释性对多轮编码智能体进行安全引导
4. [Safe and Generalizable Hierarchical Multi-Agent RL via Constraint Manifold Control](/202606/24/2606.24010v1-safe-and-generalizable-hierarchical-multi-agent-rl-via-constraint-manifold-control) （8.0/10）
   evidence：基于约束流形的安全多智能体强化学习
5. [Latent Visual States for Efficient Multimodal Reasoning](/202606/24/2606.24233v1-latent-visual-states-for-efficient-multimodal-reasoning) （8.0/10）
   evidence：通过潜在视觉状态实现高效多模态推理
6. [Temporal Self-Imitation Learning](/202606/24/2606.19752v1-temporal-self-imitation-learning) （7.0/10）
   evidence：时序自模仿学习将高效轨迹作为自蒸馏信号改进策略
7. [Multi-Agent Transactive Memory](/202606/24/2606.19911v1-multi-agent-transactive-memory) （7.0/10）
   evidence：提出多智能体交易记忆，用于跨LLM智能体群体的知识共享，与智能体集群架构相关
8. [Adversarial observations in probabilistic State-Space Models for robust Reinforcement Learning](/202606/24/2606.20880v1-adversarial-observations-in-probabilistic-state-space-models-for-robust-reinforcement-learning) （7.0/10）
   evidence：对状态空间模型的对抗攻击以增强鲁棒RL
9. [Revelio: Cost-Efficient Agentic Memory Safety Vulnerability Detection For Repository-Scale Codebases](/202606/24/2606.22263v1-revelio-cost-efficient-agentic-memory-safety-vulnerability-detection-for-repository-scale-codebases) （7.0/10）
   evidence：检测基于LLM的智能体中的内存安全漏洞
10. [Group-Graph Policy Optimization for Long-Horizon Agentic Reinforcement Learning](/202606/24/2606.22995v1-group-graph-policy-optimization-for-long-horizon-agentic-reinforcement-learning) （7.0/10）
   evidence：提出组图策略优化用于长视界智能体强化学习处理长期任务中的信用分配问题与长上下文RL训练相关
11. [EnvRL: Learn from Environment Dynamics in Agentic Reinforcement Learning](/202606/24/2606.17680v1-envrl-learn-from-environment-dynamics-in-agentic-reinforcement-learning) （6.0/10）
   evidence：面向长程智能体任务的RL
12. [From Trainee to Trainer: LLM-Designed Training Environment for RL with Multi-Agent Reasoning](/202606/24/2606.17682v1-from-trainee-to-trainer-llm-designed-training-environment-for-rl-with-multi-agent-reasoning) （6.0/10）
   evidence：基于LLM设计环境的的多智能体强化学习
13. [StepGuard: Guarding Web Navigation via Single-Step Calibration](/202606/24/2606.17871v1-stepguard-guarding-web-navigation-via-single-step-calibration) （6.0/10）
   evidence：通过单步校准的强化学习智能体安全
14. [Knowledge Reutilization in Meta-Reinforcement Learning](/202606/24/2606.18132v1-knowledge-reutilization-in-meta-reinforcement-learning) （6.0/10）
   evidence：元强化学习中的知识迁移类似蒸馏

---
使用键盘方向键可在日报/论文之间快速切换。
