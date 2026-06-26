# 日报 · 2026-06-26

- 生成时间：2026-06-26 21:12:03 UTC
- 当次推荐总数：27
- 精读区：13
- 速读区：14

## 今日简报（AI）
今日精读27篇论文，聚焦LLM蒸馏位置偏差与长程智能体安全治理两大核心问题。

最值得关注的是《On the Position Bias of On-Policy Distillation》揭露了策略内蒸馏的位置偏差陷阱，以及《Governance Decay》发现长对话中智能体安全约束会悄然消失。

建议普通读者优先精读这两篇高分论文，重点理解位置偏差对模型能力的影响，以及构建长程对话安全机制的必要性。

## 精读区
1. [On the Position Bias of On-Policy Distillation](/202606/26/2606.22600v2-on-the-position-bias-of-on-policy-distillation) （10.0/10）
   evidence：直接研究强化学习中的策略蒸馏
2. [Governance Decay: How Context Compaction Silently Erases Safety Constraints in Long-Horizon LLM Agents](/202606/26/2606.22528v1-governance-decay-how-context-compaction-silently-erases-safety-constraints-in-long-horizon-llm-agents) （9.0/10）
   evidence：针对长程LLM智能体的安全基准测试
3. [PolicyTrim: Boosting Intrinsic Policy Efficiency of Vision-Language-Action Models](/202606/26/2606.22540v2-policytrim-boosting-intrinsic-policy-efficiency-of-vision-language-action-models) （9.0/10）
   evidence：VLA模型策略效率，减少推理步骤
4. [Beyond Trajectory Imitation: Strategy-Guided Policy Optimization for LLM Reasoning](/202606/26/2606.24064v1-beyond-trajectory-imitation-strategy-guided-policy-optimization-for-llm-reasoning) （9.0/10）
   evidence：面向LLM推理的策略蒸馏方法
5. [PolicyAlign: Direct Policy-Based Safety Alignment for Large Language Models](/202606/26/2606.25442v1-policyalign-direct-policy-based-safety-alignment-for-large-language-models) （9.0/10）
   evidence：基于在线策略自蒸馏的安全对齐
6. [RAS: Measuring LLM Safety Through Refusal Alignment](/202606/26/2606.25750v1-ras-measuring-llm-safety-through-refusal-alignment) （9.0/10）
   evidence：通过内部拒绝方向衡量LLM安全，针对越狱提示
7. [On-Policy Self-Distillation with Sampled Demonstrations Reduces Output Diversity](/202606/26/2606.26091v1-on-policy-self-distillation-with-sampled-demonstrations-reduces-output-diversity) （9.0/10）
   evidence：在线自我蒸馏降低输出多样性
8. [Verifying Intent and Harm: A Unified Defense Against LLM-Generated Threats](/202606/26/2606.26377v1-verifying-intent-and-harm-a-unified-defense-against-llm-generated-threats) （9.0/10）
   evidence：针对越狱攻击的联合防御框架
9. [Adversarial Diffusion Across Modalities: A Fusion Survey of Attacks, Defenses, and Evaluation for Text, Vision, and Vision-Language Models](/202606/26/2606.26566v1-adversarial-diffusion-across-modalities-a-fusion-survey-of-attacks-defenses-and-evaluation-for-text-vision-and-vision-language-models) （9.0/10）
   evidence：包含越狱攻击与防御的综述
10. [Autoformalization of Agent Instructions into Policy-as-Code](/202606/26/2606.26649v1-autoformalization-of-agent-instructions-into-policy-as-code) （9.0/10）
   evidence：智能体安全与形式化策略执行
11. [OPID: On-Policy Skill Distillation for Agentic Reinforcement Learning](/202606/26/2606.26790v1-opid-on-policy-skill-distillation-for-agentic-reinforcement-learning) （9.0/10）
   evidence：面向智能体RL的on-policy自我蒸馏
12. [MIRROR: Novelty-Constrained Memory-Guided MCTS Red-Teaming for Agentic RAG](/202606/26/2606.26793v1-mirror-novelty-constrained-memory-guided-mcts-red-teaming-for-agentic-rag) （9.0/10）
   evidence：面向Agent RAG系统的红队测试框架
13. [ForesightSafety-VLA: A Unified Diagnostic Safety Benchmark for Vision-Language-Action Models](/202606/26/2606.27079v1-foresightsafety-vla-a-unified-diagnostic-safety-benchmark-for-vision-language-action-models) （9.0/10）
   evidence：提出面向VLA模型的安全基准

## 速读区
1. [DEFENGRAPH: Knowledge Graph-Enhanced LLMs for Blue Team Cyber Defense](/202606/26/2606.21059v1-defengraph-knowledge-graph-enhanced-llms-for-blue-team-cyber-defense) （8.0/10）
   evidence：利用知识图谱的网络安全防御助手
2. [AgentLens: Interpretable Safety Steering via Mechanistic Subspaces for Multi-Turn Coding Agent](/202606/26/2606.22673v1-agentlens-interpretable-safety-steering-via-mechanistic-subspaces-for-multi-turn-coding-agent) （8.0/10）
   evidence：多轮编码智能体的可解释安全引导
3. [SPIRAL: Learning to Search and Aggregate](/202606/26/2606.23595v1-spiral-learning-to-search-and-aggregate) （8.0/10）
   evidence：通过并行和聚合推理实现推理效率的强化学习方法
4. [Reasoning as Attractor Dynamics: Latent Memory Retrieval via Gibbs-Weighted Energy Minimization](/202606/26/2606.24543v1-reasoning-as-attractor-dynamics-latent-memory-retrieval-via-gibbs-weighted-energy-minimization) （8.0/10）
   evidence：基于能量的高效推理路径选择
5. [FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Calibrated Warm-up and Self-Distillation](/202606/26/2606.26006v1-force-efficient-vla-reinforcement-fine-tuning-via-value-calibrated-warm-up-and-self-distillation) （8.0/10）
   evidence：在线策略 rollout 与自蒸馏用于强化学习微调
6. [Jailbreaking for the Average Jane: Choosing Optimal Jailbreaks via Bandit Algorithms for Automatically Enhanced Queries](/202606/26/2606.26936v1-jailbreaking-for-the-average-jane-choosing-optimal-jailbreaks-via-bandit-algorithms-for-automatically-enhanced-queries) （8.0/10）
   evidence：提出基于bandit的越狱攻击选择
7. [PolicyTrim: Boosting Intrinsic Policy Efficiency of Vision-Language-Action Models](/202606/26/2606.22540v1-policytrim-boosting-intrinsic-policy-efficiency-of-vision-language-action-models) （7.0/10）
   evidence：策略效率与推理效率
8. [A Stackelberg Framework for Resource-Aware LLM Agents: Learning, Repair, and Conditional Guarantees](/202606/26/2606.23026v1-a-stackelberg-framework-for-resource-aware-llm-agents-learning-repair-and-conditional-guarantees) （7.0/10）
   evidence：在预算下优化上下文和工具使用的资源感知LLM智能体
9. [TOPS: First-Principles Visual Token Pruning via Constructing Token Optimal Preservation Sets for Efficient MLLM Inference](/202606/26/2606.27161v1-tops-first-principles-visual-token-pruning-via-constructing-token-optimal-preservation-sets-for-efficient-mllm-inference) （7.0/10）
   evidence：视觉token剪枝用于高效多模态大语言模型推理
10. [Resource-Aware Neuro-Symbolic Reasoning for Local Small Language Models](/202606/26/2606.27281v1-resource-aware-neuro-symbolic-reasoning-for-local-small-language-models) （7.0/10）
   evidence：为本地小模型设计的神经符号推理管线，减少重复采样，提高效率
11. [Uncertainty-Aware Reward Modeling for Stable RLHF](/202606/26/2606.19818v1-uncertainty-aware-reward-modeling-for-stable-rlhf) （6.0/10）
   evidence：不确定性感知的奖励建模用于稳定RLHF，减少奖励黑客
12. [Hierarchical Control in Multi-Agent Games: LLM-based Planning and RL Execution](/202606/26/2606.20014v1-hierarchical-control-in-multi-agent-games-llm-based-planning-and-rl-execution) （6.0/10）
   evidence：提出基于LLM的多智能体团队层次化协调架构
13. [Learning What Not to Forget: Long-Horizon Agent Memory from a Few Kilobytes of Learning](/202606/26/2606.20954v1-learning-what-not-to-forget-long-horizon-agent-memory-from-a-few-kilobytes-of-learning) （6.0/10）
   evidence：长时智能体记忆管理以应对长上下文
14. [Federated Temporal Attention Intelligence for Cyber-Resilient IoMT: Lightweight Digital Twins and PPO-Driven Honeypot Deception](/202606/26/2606.21422v1-federated-temporal-attention-intelligence-for-cyber-resilient-iomt-lightweight-digital-twins-and-ppo-driven-honeypot-deception) （6.0/10）
   evidence：提出LDT-FRL框架，采用PPO驱动的蜜罐欺骗机制用于IoMT网络安全防御

---
使用键盘方向键可在日报/论文之间快速切换。
