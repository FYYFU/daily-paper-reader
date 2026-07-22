# 日报 · 2026-07-22

- 生成时间：2026-07-22 21:52:22 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日精读两篇满分论文，聚焦策略蒸馏的新突破；速读三篇八分工作分别探讨约束推理、反馈蒸馏失效及激活控制。  
最值得关注的两个方向：CADENCE通过覆盖自适应策略缩小推理差距，对比策略蒸馏则从对比学习视角优化推理痕迹。  
建议优先精读这两篇10分论文，并留意速读中关于突破LLM“自我循环”的激活控制方法。

## 精读区
1. [CADENCE: Closing the Reasoning Gap via Coverage-Adaptive On-Policy Distillation](/202607/22/2607.16955v1-cadence-closing-the-reasoning-gap-via-coverage-adaptive-on-policy-distillation) （10.0/10）
   evidence：覆盖自适应on-policy蒸馏用于推理任务
2. [Contrastive On-Policy Distillation](/202607/22/2607.19046v1-contrastive-on-policy-distillation) （10.0/10）
   evidence：面向语言模型的对比式同策略蒸馏
3. [Refusal is Not Safety! Benchmarking Latent Safety Risks of LLM-Driven Content Humorization](/202607/22/2607.15977v1-refusal-is-not-safety-benchmarking-latent-safety-risks-of-llm-driven-content-humorization) （9.0/10）
   evidence：安全风险，越狱，拒绝机制，基准测试
4. [Distilled Reinforcement Learning for LLM Post-training](/202607/22/2607.17247v1-distilled-reinforcement-learning-for-llm-post-training) （9.0/10）
   evidence：直接针对LLM后训练中的on-policy蒸馏与强化学习
5. [WAR: Workload-Aware Rollouts for Synchronous Agentic Reinforcement Learning](/202607/22/2607.17299v1-war-workload-aware-rollouts-for-synchronous-agentic-reinforcement-learning) （9.0/10）
   evidence：同步智能体强化学习的工作负载感知rollout生成
6. [SciHazard: A Benchmark for Measuring Scientific Safety Risks with Decomposed Harm Scoring](/202607/22/2607.18665v1-scihazard-a-benchmark-for-measuring-scientific-safety-risks-with-decomposed-harm-scoring) （9.0/10）
   evidence：科学安全风险基准
7. [H$^2$SD: Hybrid Hindsight Self-Distillation](/202607/22/2607.18955v1-h2sd-hybrid-hindsight-self-distillation) （9.0/10）
   evidence：在线策略蒸馏，混合后见之明自蒸馏
8. [Self-State Attacks on Self-Hosted AI Agents: How Far Can OS Defenses Go?](/202607/22/2607.17986v1-self-state-attacks-on-self-hosted-ai-agents-how-far-can-os-defenses-go) （8.0/10）
   evidence：自状态攻击直接涉及代理安全
9. [Hazard or Anomaly? Evaluating VLMs for Understanding Dangers and Discrepancies](/202607/22/2607.18325v1-hazard-or-anomaly-evaluating-vlms-for-understanding-dangers-and-discrepancies) （8.0/10）
   evidence：评估VLM区分危险与异常的能力，构建安全基准

## 速读区
1. [Constraint-Anchored Reasoning Traces](/202607/22/2607.16727v1-constraint-anchored-reasoning-traces) （8.0/10）
   evidence：通过约束锚定推理迹提高推理效率
2. [Why Does Feedback-Augmented Self-Distillation Fail to Improve Retrieval-Interleaved Search Agents?](/202607/22/2607.17558v1-why-does-feedback-augmented-self-distillation-fail-to-improve-retrieval-interleaved-search-agents) （8.0/10）
   evidence：on-policy自蒸馏在智能体搜索中的失败分析
3. [Can We Break LLMs Out of Self-Loops? Fine-Grained Reasoning Control with Activation Steering](/202607/22/2607.18100v1-can-we-break-llms-out-of-self-loops-fine-grained-reasoning-control-with-activation-steering) （8.0/10）
   evidence：打破推理自我循环以节约token预算；激活导向方法
4. [Copy Less, Ground More: Overcoming Repetitive Copying in Long-Context Reasoning via Evidence-Aware Reinforcement Learning](/202607/22/2607.19345v1-copy-less-ground-more-overcoming-repetitive-copying-in-long-context-reasoning-via-evidence-aware-reinforcement-learning) （8.0/10）
   evidence：长上下文推理的强化学习训练
5. [RECON: Benchmarking Agent Memory for Compositional Reasoning over Long Contexts](/202607/22/2607.16716v1-recon-benchmarking-agent-memory-for-compositional-reasoning-over-long-contexts) （7.0/10）
   evidence：长上下文组合推理的基准，与长上下文强化学习评估相关
6. [RELIC: Revealed Principles for Learning Interpretable Composable Skills in Multi-Agent Planning](/202607/22/2607.16745v1-relic-revealed-principles-for-learning-interpretable-composable-skills-in-multi-agent-planning) （7.0/10）
   evidence：多智能体技能学习与私有LLM搜索实现可组合技能
7. [Beyond Semantic Equivalence: Logical Graphs for LLM Uncertainty Quantification](/202607/22/2607.16868v1-beyond-semantic-equivalence-logical-graphs-for-llm-uncertainty-quantification) （7.0/10）
   evidence：面向安全敏感场景的大模型不确定性量化
8. [MADA-RL: Multi-Agent Debate-Aware Reinforcement Learning for Parameter-Efficient Reasoning in Compact Models](/202607/22/2607.18006v1-mada-rl-multi-agent-debate-aware-reinforcement-learning-for-parameter-efficient-reasoning-in-compact-models) （7.0/10）
   evidence：参数高效推理，紧凑模型，辩论感知学习
9. [DAIS: Dependency-Aware Intermediate QA Supervision for Complex Reasoning](/202607/22/2607.19088v1-dais-dependency-aware-intermediate-qa-supervision-for-complex-reasoning) （7.0/10）
   evidence：从教师推理过程提炼中间QA监督用于复杂推理
10. [Agents in the Wild: Where Research Meets Deployment](/202607/22/2607.19336v1-agents-in-the-wild-where-research-meets-deployment) （7.0/10）
   evidence：讨论了LLM智能体部署中的安全挑战
11. [Policy-Conditioned Constrained Decoding for Column-Level Access Control in Text-to-SQL](/202607/22/2607.12341v1-policy-conditioned-constrained-decoding-for-column-level-access-control-in-text-to-sql) （6.0/10）
   evidence：Text-to-SQL中面向列级访问控制的策略约束解码
12. [Memory as a Controlled Process: Learned Adaptive Memory Management for LLM Agents](/202607/22/2607.13591v1-memory-as-a-controlled-process-learned-adaptive-memory-management-for-llm-agents) （6.0/10）
   evidence：LLM智能体的自适应记忆管理，对智能体集群协调有用
13. [Value-Aware Prediction for Robust Multi-Agent Coordination Under Communication Loss](/202607/22/2607.17914v1-value-aware-prediction-for-robust-multi-agent-coordination-under-communication-loss) （6.0/10）
   evidence：提出了通信丢失下的价值感知预测方法，与智能体集群的鲁棒性相关
14. [Search-on-Graph-R1: Training Large Language Models to Search Knowledge Graphs with Reinforcement Learning](/202607/22/2607.18481v1-search-on-graph-r1-training-large-language-models-to-search-knowledge-graphs-with-reinforcement-learning) （6.0/10）
   evidence：使用教师-学生框架和RL进行知识图谱问答，类似蒸馏

---
使用键盘方向键可在日报/论文之间快速切换。
