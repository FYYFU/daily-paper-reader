# 日报 · 2026-07-09

- 生成时间：2026-07-09 22:02:17 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日共处理23篇论文，精读9篇、速读14篇，重点关注两项高分研究。最值得精读的是《Weak-to-Strong Generalization via Direct On-Policy Distillation》与《CritiqueDriveVLM: From Verifier-Guided Reinforcement Learning to Latent Thought Distillation for Autonomous Driving》，分别聚焦弱到强泛化蒸馏与自动驾驶批判性推理。建议优先阅读这两篇，并关注速读列表中关于MoE压缩、RAG知识库攻击及思维链一致性审计的新进展。

## 精读区
1. [Weak-to-Strong Generalization via Direct On-Policy Distillation](/202607/09/2607.05394v2-weak-to-strong-generalization-via-direct-on-policy-distillation) （10.0/10）
   evidence：直接在线策略蒸馏用于RL中弱到强泛化
2. [CritiqueDriveVLM: From Verifier-Guided Reinforcement Learning to Latent Thought Distillation for Autonomous Driving](/202607/09/2607.04179v1-critiquedrivevlm-from-verifier-guided-reinforcement-learning-to-latent-thought-distillation-for-autonomous-driving) （9.0/10）
   evidence：结合强化学习与蒸馏技术用于自动驾驶，核心为潜思蒸馏
3. [A Few Teacher Steps Go a Long Way: Cost-Efficient On-Policy Data Augmentation for Agent Post-Training](/202607/09/2607.04574v1-a-few-teacher-steps-go-a-long-way-cost-efficient-on-policy-data-augmentation-for-agent-post-training) （9.0/10）
   evidence：教师学生框架强化学习蒸馏；利用教师步骤的在线数据增强
4. [Trust Region Policy Distillation](/202607/09/2607.04751v1-trust-region-policy-distillation) （9.0/10）
   evidence：直接针对在线策略蒸馏提出信任区域策略蒸馏方法
5. [CompactionRL: Reinforcement Learning with Context Compaction for Long-Horizon Agents](/202607/09/2607.05378v1-compactionrl-reinforcement-learning-with-context-compaction-for-long-horizon-agents) （9.0/10）
   evidence：利用上下文压缩实现长时程智能体的强化学习训练
6. [Behavior Leverage Imbalance in Multi-Teacher On-Policy Distillation](/202607/09/2607.07050v1-behavior-leverage-imbalance-in-multi-teacher-on-policy-distillation) （9.0/10）
   evidence：多教师策略蒸馏中的行为偏差
7. [Operational Reframing and Approval-Framed Delegation in Multi-Agent LLM Safety](/202607/09/2607.07097v1-operational-reframing-and-approval-framed-delegation-in-multi-agent-llm-safety) （9.0/10）
   evidence：多智能体大模型安全，安全基准，红队测试
8. [ORCAID: Oblique Rule-Based Continuous-Action Interpretation for Deep RL Policies](/202607/09/2607.07235v1-orcaid-oblique-rule-based-continuous-action-interpretation-for-deep-rl-policies) （9.0/10）
   evidence：从深度强化学习智能体中蒸馏可解释的规则策略，与策略蒸馏直接相关
9. [Institutional Red-Teaming: Deployment Rules, Not Just Models, Causally Shape Multi-Agent AI Safety](/202607/09/2607.07695v1-institutional-red-teaming-deployment-rules-not-just-models-causally-shape-multi-agent-ai-safety) （9.0/10）
   evidence：多智能体AI安全的机构红队测试方法

## 速读区
1. [Nemotron-Labs-3-Puzzle-75B-A9B: Compressing Hybrid MoE LLMs](/202607/09/2607.04371v2-nemotron-labs-3-puzzle-75b-a9b-compressing-hybrid-moe-llms) （8.0/10）
   evidence：知识蒸馏与强化学习用于MoE模型压缩
2. [Knowledge Base Poisoning Attacks and Defense for Policy-Aware LLM-RAG Framework](/202607/09/2607.04379v1-knowledge-base-poisoning-attacks-and-defense-for-policy-aware-llm-rag-framework) （8.0/10）
   evidence：越狱攻击与防御；针对LLM-RAG的知识库投毒攻击与防御
3. [Reasoning Consistency Scanning: A Framework for Auditing Chain-of-Thought Validity in AI Safety Evaluations](/202607/09/2607.07229v1-reasoning-consistency-scanning-a-framework-for-auditing-chain-of-thought-validity-in-ai-safety-evaluations) （8.0/10）
   evidence：AI安全评估审计框架
4. [Safe Reinforcement Learning using Ideas from Model Predictive Control](/202607/09/2607.07252v1-safe-reinforcement-learning-using-ideas-from-model-predictive-control) （8.0/10）
   evidence：强化学习中的智能体安全性；结合MPC形式化安全保证的安全RL
5. [From Atomic Actions to Standard Operating Procedures: Iterative Tool Optimization for Self-Evolving LLM Agents](/202607/09/2607.07321v1-from-atomic-actions-to-standard-operating-procedures-iterative-tool-optimization-for-self-evolving-llm-agents) （8.0/10）
   evidence：智能体工具优化与自演化框架
6. [Incentivizing Vision Language Models to Search for Long Video Question Answering](/202607/09/2607.02959v1-incentivizing-vision-language-models-to-search-for-long-video-question-answering) （7.0/10）
   evidence：RL后训练用于长视频问答，契合长上下文RL训练
7. [Look Before You Leap: Distilling Tree Search into Action Evaluation for Frozen VLA Models](/202607/09/2607.03751v1-look-before-you-leap-distilling-tree-search-into-action-evaluation-for-frozen-vla-models) （7.0/10）
   evidence：将树搜索蒸馏为动作评估
8. [STAPO: Selective Trajectory-Aware Policy Optimization for LLM Agent Training](/202607/09/2607.04963v1-stapo-selective-trajectory-aware-policy-optimization-for-llm-agent-training) （7.0/10）
   evidence：针对长时程LLM智能体训练中的轨迹忽略问题的强化学习方法
9. [Adaptive Inference Batching using Policy Gradients](/202607/09/2607.05272v1-adaptive-inference-batching-using-policy-gradients) （7.0/10）
   evidence：人工智能中的推理效率；基于强化学习的自适应批处理提升推理服务吞吐量
10. [Information Gain-based Rollout Policy Optimization: An Adaptive Tree-Structured Rollout Approach for Multi-Turn LLM Agents](/202607/09/2607.06223v1-information-gain-based-rollout-policy-optimization-an-adaptive-tree-structured-rollout-approach-for-multi-turn-llm-agents) （7.0/10）
   evidence：基于信息增益的展开优化，提升多轮大模型智能体推理效率
11. [Reward Granularity in RLVR: Comparing Process and Outcome Reward Structures for Mathematical Reasoning in Small Language Models](/202607/09/2607.02869v1-reward-granularity-in-rlvr-comparing-process-and-outcome-reward-structures-for-mathematical-reasoning-in-small-language-models) （6.0/10）
   evidence：RL奖励结构比较以提升小语言模型推理效率
12. [KARMA: Knowledge graph-based Automated Reasoning Materialization and Alignment](/202607/09/2607.03166v1-karma-knowledge-graph-based-automated-reasoning-materialization-and-alignment) （6.0/10）
   evidence：基于知识图谱的自动化推理方法提升对比候选生成效率
13. [Akashic: A Low-Overhead LLM Inference Service with MemAttention](/202607/09/2607.05708v1-akashic-a-low-overhead-llm-inference-service-with-memattention) （6.0/10）
   evidence：低开销长上下文推理内存系统
14. [Gimitest: A Comprehensive Tool for Testing Reinforcement Learning Policies](/202607/09/2607.07029v1-gimitest-a-comprehensive-tool-for-testing-reinforcement-learning-policies) （6.0/10）
   evidence：用于测试RL策略安全性和鲁棒性的综合工具

---
使用键盘方向键可在日报/论文之间快速切换。
