# 日报 · 2026-08-09

- 生成时间：2026-08-09 20:41:58 UTC
- 当次推荐总数：15
- 精读区：9
- 速读区：6

## 今日简报（AI）
今日15篇论文聚焦AI模型优化，9篇精读、6篇速读，其中两篇扩散语言模型策略蒸馏工作获满分推荐。最值得关注的是OPTD与SPOT，均以一致性引导和稀疏校准提升少步扩散模型蒸馏效率，显著拉开梯队差距。建议优先研读两篇满分论文，速读可留意技能蒸馏与多智能体路径规划的实操价值。

## 精读区
1. [OPTD: On-Policy Transition Distillation with Consistency-Guided Adaptive Compression for Few-Step Diffusion Language Models](/202608/09/2608.02942v1-optd-on-policy-transition-distillation-with-consistency-guided-adaptive-compression-for-few-step-diffusion-language-models) （10.0/10）
   evidence：用于少步扩散语言模型的在策略过渡蒸馏
2. [SPOT: Sparse Probing and Outcome Calibration for On-Policy Distillation](/202608/09/2608.04419v1-spot-sparse-probing-and-outcome-calibration-for-on-policy-distillation) （10.0/10）
   evidence：研究on-policy distillation的稀疏探测与结果校准方法
3. [Benign Alone, Harmful Together: Exploiting Experience Composition in Self-Evolving LLM Agents](/202608/09/2608.01759v1-benign-alone-harmful-together-exploiting-experience-composition-in-self-evolving-llm-agents) （9.0/10）
   evidence：针对自进化LLM智能体的安全攻击，与越狱攻击/红队测试要求直接对应
4. [Look Ahead Before You Distill: Future Trajectory Validation of Teacher Guidance for Agentic On-Policy Distillation](/202608/09/2608.01953v2-look-ahead-before-you-distill-future-trajectory-validation-of-teacher-guidance-for-agentic-on-policy-distillation) （9.0/10）
   evidence：基于未来轨迹桥的智能体on-policy蒸馏
5. [Privileged, but Biased: How PI-Conditioned Teachers Break Self-Distillation](/202608/09/2608.04794v1-privileged-but-biased-how-pi-conditioned-teachers-break-self-distillation) （9.0/10）
   evidence：研究自蒸馏作为强化学习的替代方案，并揭示困难任务上的失效
6. [When Privileged Guidance Misaligns: State-Matched Routing and Contextualized Self-Distillation for Multi-Turn Agents](/202608/09/2608.05219v1-when-privileged-guidance-misaligns-state-matched-routing-and-contextualized-self-distillation-for-multi-turn-agents) （9.0/10）
   evidence：针对多轮智能体的特权在线策略蒸馏问题，提出状态匹配路由和情境化自蒸馏
7. [Permission Denied: Policy-Graded Evaluation of Coding Agents in Hardened Environments](/202608/09/2608.02670v1-permission-denied-policy-graded-evaluation-of-coding-agents-in-hardened-environments) （8.0/10）
   evidence：硬化安全策略下的智能体安全评估
8. [From Sports to Safety: Benchmarking Proactive Risk Inference in MLLMs](/202608/09/2608.05560v1-from-sports-to-safety-benchmarking-proactive-risk-inference-in-mllms) （8.0/10）
   evidence：提出面向MLLM的主动风险推理安全基准，属于安全基准类需求
9. [What Current AI Benchmarks Leave Unmeasured: Modality, Search, Citations, and Implications (for Safety Evaluations)](/202608/09/2608.06202v1-what-current-ai-benchmarks-leave-unmeasured-modality-search-citations-and-implications-for-safety-evaluations) （8.0/10）
   evidence：审计安全基准的假设，讨论对安全评估的影响

## 速读区
1. [Search2Skill: Skill Distillation Beyond Knowledge Boundaries Via Rubric-Based Reinforcement Learning](/202608/09/2608.05245v1-search2skill-skill-distillation-beyond-knowledge-boundaries-via-rubric-based-reinforcement-learning) （7.0/10）
   evidence：基于强化学习的技能蒸馏
2. [Search-Aided Joint Agent-Environment Reinforcement Learning for Robust Lifelong Multi-Agent Path Finding with Rotations](/202608/09/2608.05588v1-search-aided-joint-agent-environment-reinforcement-learning-for-robust-lifelong-multi-agent-path-finding-with-rotations) （7.0/10）
   evidence：面向鲁棒终身多智能体路径规划的安全约束强化学习
3. [SkillTrace: Traversing a Query-Skill Graph for Composable LLM Agents](/202608/09/2608.02356v1-skilltrace-traversing-a-query-skill-graph-for-composable-llm-agents) （6.0/10）
   evidence：面向复杂任务执行的LLM智能体技能组合图谱
4. [SkillTrace: Traversing a Query-Skill Graph for Composable LLM Agents](/202608/09/2608.02356v2-skilltrace-traversing-a-query-skill-graph-for-composable-llm-agents) （6.0/10）
   evidence：面向可组合大语言模型智能体的查询-技能图遍历，支持复杂任务分解
5. [EvoHarness-RL: Learning Self-Evolving Runtime Harness for Long-Horizon LLM Agents](/202608/09/2608.05446v1-evoharness-rl-learning-self-evolving-runtime-harness-for-long-horizon-llm-agents) （6.0/10）
   evidence：面向长时程智能体的RL运行时框架学习，支持工具调用和复杂任务执行
6. [EnvACE: Internalizing Environment Dynamics via World Rehearsal for Agentic Reinforcement Learning](/202608/09/2608.06197v1-envace-internalizing-environment-dynamics-via-world-rehearsal-for-agentic-reinforcement-learning) （6.0/10）
   evidence：面向长程工具使用智能体的强化学习训练，采用世界预演替代外部环境交互，与长输入序列RL训练相关

---
使用键盘方向键可在日报/论文之间快速切换。
