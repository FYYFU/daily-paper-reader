# 日报 · 2026-06-25

- 生成时间：2026-06-25 21:42:40 UTC
- 当次推荐总数：32
- 精读区：18
- 速读区：14

## 今日简报（AI）
今日共处理32篇论文，精读18篇完成高分深度分析，速读14篇覆盖前沿方向；最值得关注的两篇满分精读分别揭示了长程LLM智能体中的安全约束隐形消失机制（治理衰减）与在线策略蒸馏的位置偏差问题；建议优先阅读这两篇论文，对理解大模型安全性与训练效率瓶颈具有直接指导意义。

## 精读区
1. [Governance Decay: How Context Compaction Silently Erases Safety Constraints in Long-Horizon LLM Agents](/202606/25/2606.22528v1-governance-decay-how-context-compaction-silently-erases-safety-constraints-in-long-horizon-llm-agents) （10.0/10）
   evidence：上下文压缩导致LLM代理中安全约束被擦除
2. [On the Position Bias of On-Policy Distillation](/202606/25/2606.22600v2-on-the-position-bias-of-on-policy-distillation) （10.0/10）
   evidence：在线策略蒸馏位置偏差
3. [Finding the Evidence: Discovering Decision-Supporting Tokens for On-Policy Reasoning Distillation](/202606/25/2606.22830v1-finding-the-evidence-discovering-decision-supporting-tokens-for-on-policy-reasoning-distillation) （10.0/10）
   evidence：面向推理的on-policy蒸馏，发现决策和支持证据
4. [AsyncOPD: How Stale Can On-Policy Distillation Be?](/202606/25/2606.24143v1-asyncopd-how-stale-can-on-policy-distillation-be) （10.0/10）
   evidence：直接研究异步设置下的on-policy蒸馏
5. [V-Zero: Answer-Label-Free On-Policy Distillation with Contrastive Evidence Gating for Fine-Grained Visual Reasoning](/202606/25/2606.25319v1-v-zero-answer-label-free-on-policy-distillation-with-contrastive-evidence-gating-for-fine-grained-visual-reasoning) （10.0/10）
   evidence：直接针对视觉推理的在线策略蒸馏方法
6. [Local LLM Agents as Vulnerable Runtimes:A Source-Code Audit of the Agent Runtime Layer](/202606/25/2606.21071v1-local-llm-agents-as-vulnerable-runtimesa-source-code-audit-of-the-agent-runtime-layer) （9.0/10）
   evidence：审计本地LLM代理运行时的安全性，关注代理安全与漏洞
7. [AgentLens: Interpretable Safety Steering via Mechanistic Subspaces for Multi-Turn Coding Agent](/202606/25/2606.22673v1-agentlens-interpretable-safety-steering-via-mechanistic-subspaces-for-multi-turn-coding-agent) （9.0/10）
   evidence：多轮编码代理的可解释安全引导
8. [The Geometry of Refusal: Linear Instability in Safety-Aligned LLMs](/202606/25/2606.22686v1-the-geometry-of-refusal-linear-instability-in-safety-aligned-llms) （9.0/10）
   evidence：研究安全对齐的脆弱性和拒绝方向
9. [Beyond Penalizing Mistakes: Stabilizing Efficiency Training in Large Reasoning Models via Adaptive Correct-Only Rewards](/202606/25/2606.22716v1-beyond-penalizing-mistakes-stabilizing-efficiency-training-in-large-reasoning-models-via-adaptive-correct-only-rewards) （9.0/10）
   evidence：在大推理模型中稳定效率训练
10. [Beyond Trajectory Imitation: Strategy-Guided Policy Optimization for LLM Reasoning](/202606/25/2606.24064v1-beyond-trajectory-imitation-strategy-guided-policy-optimization-for-llm-reasoning) （9.0/10）
   evidence：策略引导蒸馏用于大语言模型推理的策略优化
11. [Blockwise Policy-Drift Gating for On-Policy Distillation](/202606/25/2606.24084v1-blockwise-policy-drift-gating-for-on-policy-distillation) （9.0/10）
   evidence：直接针对on-policy蒸馏提出块策略漂移门控
12. [ReM-MoA: Reasoning Memory Sustains Mixture-of-Agents Scaling](/202606/25/2606.24437v1-rem-moa-reasoning-memory-sustains-mixture-of-agents-scaling) （9.0/10）
   evidence：记忆增强的混合智能体架构，维持缩放性能
13. [Themis: An explainable AI-enabled framework for Reinforcement Learning with Human Feedback](/202606/25/2606.24622v1-themis-an-explainable-ai-enabled-framework-for-reinforcement-learning-with-human-feedback) （9.0/10）
   evidence：结合可解释性与人类反馈的强化学习安全框架
14. [What Does It Mean to Break a Distillation Defense?](/202606/25/2606.25059v1-what-does-it-mean-to-break-a-distillation-defense) （9.0/10）
   evidence：蒸馏攻击防御LLM安全
15. [PolicyAlign: Direct Policy-Based Safety Alignment for Large Language Models](/202606/25/2606.25442v1-policyalign-direct-policy-based-safety-alignment-for-large-language-models) （9.0/10）
   evidence：利用在线策略自蒸馏进行大模型安全对齐
16. [How Reliable Is Your Jailbreak Judge? Calibration and Adversarial Robustness of Automated ASR Scoring](/202606/25/2606.25487v1-how-reliable-is-your-jailbreak-judge-calibration-and-adversarial-robustness-of-automated-asr-scoring) （9.0/10）
   evidence：评估越狱攻击成功率自动评判器的可靠性
17. [RAS: Measuring LLM Safety Through Refusal Alignment](/202606/25/2606.25750v1-ras-measuring-llm-safety-through-refusal-alignment) （9.0/10）
   evidence：通过拒绝对齐评估LLM安全性，涉及越狱提示
18. [On-Policy Self-Distillation with Sampled Demonstrations Reduces Output Diversity](/202606/25/2606.26091v1-on-policy-self-distillation-with-sampled-demonstrations-reduces-output-diversity) （9.0/10）
   evidence：基于采样的在线策略自蒸馏

## 速读区
1. [Deeper is Not Always Better: Mitigating the Alignment Tax via Confident Layer Decoding](/202606/25/2606.21906v1-deeper-is-not-always-better-mitigating-the-alignment-tax-via-confident-layer-decoding) （8.0/10）
   evidence：无训练的自信心引导层选择实现高效解码
2. [Bias-Controlled Primal-Dual Natural Actor-Critic: Optimal Rates for Constrained Multi-Objective Average-Reward RL](/202606/25/2606.25012v1-bias-controlled-primal-dual-natural-actor-critic-optimal-rates-for-constrained-multi-objective-average-reward-rl) （8.0/10）
   evidence：带安全约束的多目标强化学习的偏差控制
3. [Efficient and Trainable Language Model Test-Time Scaling via Local Branch Routing](/202606/25/2606.25354v1-efficient-and-trainable-language-model-test-time-scaling-via-local-branch-routing) （8.0/10）
   evidence：通过局部分支路由提升测试时推理效率
4. [Brevity is the Soul of Inference Efficiency: Inducing Concision in VLMs via Data Curation](/202606/25/2606.25432v1-brevity-is-the-soul-of-inference-efficiency-inducing-concision-in-vlms-via-data-curation) （8.0/10）
   evidence：通过数据精简提升推理效率
5. [FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Calibrated Warm-up and Self-Distillation](/202606/25/2606.26006v1-force-efficient-vla-reinforcement-fine-tuning-via-value-calibrated-warm-up-and-self-distillation) （8.0/10）
   evidence：VLA强化微调中的自蒸馏，值校准预热
6. [CalVerT: Augmenting Agents with Calibrated Verifier Telemetry Improves Action and Learning in Knowledge-Intensive Tasks](/202606/25/2606.21777v1-calvert-augmenting-agents-with-calibrated-verifier-telemetry-improves-action-and-learning-in-knowledge-intensive-tasks) （7.0/10）
   evidence：通过校准验证器遥测减少过度检索，提升推理效率
7. [PolicyTrim: Boosting Intrinsic Policy Efficiency of Vision-Language-Action Models](/202606/25/2606.22540v2-policytrim-boosting-intrinsic-policy-efficiency-of-vision-language-action-models) （7.0/10）
   evidence：提升视觉-语言-动作模型的策略效率
8. [Group-Graph Policy Optimization for Long-Horizon Agentic Reinforcement Learning](/202606/25/2606.22995v1-group-graph-policy-optimization-for-long-horizon-agentic-reinforcement-learning) （7.0/10）
   evidence：面向长期智能体RL的组图策略优化
9. [Weight-Space Geometry of Offline Reasoning Training](/202606/25/2606.23740v1-weight-space-geometry-of-offline-reasoning-training) （7.0/10）
   evidence：离线推理训练方法包括蒸馏
10. [Escaping the Self-Confirmation Trap: An Execute-Distill-Verify Paradigm for Agentic Experience Learning](/202606/25/2606.24428v1-escaping-the-self-confirmation-trap-an-execute-distill-verify-paradigm-for-agentic-experience-learning) （7.0/10）
   evidence：智能体经验学习中的执行-蒸馏-验证框架
11. [Structured Inference with Large Language Gibbs](/202606/25/2606.19264v1-structured-inference-with-large-language-gibbs) （6.0/10）
   evidence：利用LLM条件分布作为转移算子进行结构化推理
12. [Multi-Agent Transactive Memory](/202606/25/2606.19911v1-multi-agent-transactive-memory) （6.0/10）
   evidence：异质智能体种群间的知识共享
13. [Modularized Reinforcement Learning on LLMs: From MDP Creation to Exploration and Learning](/202606/25/2606.21943v1-modularized-reinforcement-learning-on-llms-from-mdp-creation-to-exploration-and-learning) （6.0/10）
   evidence：综述覆盖包括on-policy蒸馏在内的RL方法
14. [Uncertainty Quantification for Computer-Use Agents: A Benchmark across Vision-Language Models and GUI Grounding Datasets](/202606/25/2606.25760v1-uncertainty-quantification-for-computer-use-agents-a-benchmark-across-vision-language-models-and-gui-grounding-datasets) （6.0/10）
   evidence：不确定性量化安全基准智能体

---
使用键盘方向键可在日报/论文之间快速切换。
