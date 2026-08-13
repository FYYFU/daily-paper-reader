# 日报 · 2026-08-13

- 生成时间：2026-08-13 21:33:22 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日共处理23篇论文，精读9篇、速读14篇，重点聚焦自蒸馏与多语言安全评测。最值得关注的是满分论文《On-Policy Self-Distillation without Any Supervision》与《SurakshaEval》印地语安全基准，分别揭示了无监督自蒸馏新路径与多语言LLM的评测缺口。建议普通读者优先浏览这两篇的结论，并留意扩散模型蒸馏与LLM推理效率的速读成果。

## 精读区
1. [On-Policy Self-Distillation without Any Supervision](/202608/13/2608.06296v2-on-policy-self-distillation-without-any-supervision) （10.0/10）
   evidence：无监督在线策略自蒸馏
2. [SurakshaEval: An Indic Safety Benchmark for Multilingual LLMs](/202608/13/2608.07862v1-surakshaeval-an-indic-safety-benchmark-for-multilingual-llms) （9.0/10）
   evidence：面向多语言LLM的印度语安全基准，包含通用及地区特定不安全提示
3. [Measuring the Wrong Thing: Internal Harmfulness Scores Anti-Rank Successful Jailbreaks](/202608/13/2608.09624v1-measuring-the-wrong-thing-internal-harmfulness-scores-anti-rank-successful-jailbreaks) （9.0/10）
   evidence：审计内部危害性评分与成功越狱的关系
4. [Learning to Persuade Exposes How Easily LLMs Abandon Correct Beliefs](/202608/13/2608.11624v1-learning-to-persuade-exposes-how-easily-llms-abandon-correct-beliefs) （9.0/10）
   evidence：通过对抗RL训练说服者，单次虚假论证即可让LLM正确率崩溃，属于越狱攻击
5. [REOPD: Reliability-Adaptive Reward Extrapolation for On-Policy Distillation](/202608/13/2608.11698v1-reopd-reliability-adaptive-reward-extrapolation-for-on-policy-distillation) （9.0/10）
   evidence：提出面向策略蒸馏的奖励外推方法
6. [Making Your LLMs More Objective: Stabilizing LLM Safety Behavior Across Traits with Trait-Invariant Safety Tuning](/202608/13/2608.11705v1-making-your-llms-more-objective-stabilizing-llm-safety-behavior-across-traits-with-trait-invariant-safety-tuning) （9.0/10）
   evidence：通过特质不变安全调优稳定LLM跨特质安全行为
7. [Towards Understanding On-Policy Distillation through the Lens of Test-Time Scaling](/202608/13/2608.11829v1-towards-understanding-on-policy-distillation-through-the-lens-of-test-time-scaling) （9.0/10）
   evidence：通过测试时缩放研究LLM推理中的在线策略蒸馏
8. [Rethinking Agent Security as a Networking Problem](/202608/13/2608.12172v1-rethinking-agent-security-as-a-networking-problem) （9.0/10）
   evidence：AI智能体安全与提示注入问题，提出基于网络的安全新方案，超越以智能体为中心的防御
9. [Distributed Team Orchestration via Supervisor Networks: Convergence, Optimality, and Resilience](/202608/13/2608.09256v1-distributed-team-orchestration-via-supervisor-networks-convergence-optimality-and-resilience) （8.0/10）
   evidence：提出面向多智能体集群的分布式团队编排算法

## 速读区
1. [STEP-OPD: Rethinking Output Targets and Internal Dynamics in On-Policy Distillation for Diffusion Models](/202608/13/2608.04887v1-step-opd-rethinking-output-targets-and-internal-dynamics-in-on-policy-distillation-for-diffusion-models) （8.0/10）
   evidence：面向扩散模型的在线策略蒸馏框架，直接对应OPD主题
2. [Towards Efficient Reasoning in LLM-Based Recommender Systems via Model Merging](/202608/13/2608.10447v1-towards-efficient-reasoning-in-llm-based-recommender-systems-via-model-merging) （8.0/10）
   evidence：通过模型合并实现高效推理
3. [ThinkRetrieve: Retrieval-Augmented Reasoning Traces for Test-Time Scaling](/202608/13/2608.10928v1-thinkretrieve-retrieval-augmented-reasoning-traces-for-test-time-scaling) （8.0/10）
   evidence：通过检索增强推理轨迹改善测试时扩展的效率
4. [Scheduling Mixed RL Rollouts Beyond Prefix Locality](/202608/13/2608.11152v1-scheduling-mixed-rl-rollouts-beyond-prefix-locality) （8.0/10）
   evidence：通过调度混合RL回放提升推理效率
5. [LoongReflect: Boosting Long-Horizon Reflection in Search Agents via Global Perspective Distillation](/202608/13/2608.11967v1-loongreflect-boosting-long-horizon-reflection-in-search-agents-via-global-perspective-distillation) （8.0/10）
   evidence：全局视角蒸馏，提升智能体反思能力
6. [Knowledge-Distilled End-to-End Reinforcement Learning for Smooth 6-DOF Thrust Control and Rapid Adaptation to Ocean Currents in Remotely Operated Vehicles](/202608/13/2608.08598v1-knowledge-distilled-end-to-end-reinforcement-learning-for-smooth-6-dof-thrust-control-and-rapid-adaptation-to-ocean-currents-in-remotely-operated-vehicles) （7.0/10）
   evidence：将知识蒸馏应用于端到端强化学习以实现平滑控制
7. [VLZip: Unified Visual and Textual Compression for Interleaved Long-Context Modeling](/202608/13/2608.08630v1-vlzip-unified-visual-and-textual-compression-for-interleaved-long-context-modeling) （7.0/10）
   evidence：统一视觉与文本压缩，提高长上下文建模的推理效率
8. [LLM Reasoning for Subjective Tasks: Failure Modes, Mitigation, and Dynamic Reasoning Routing](/202608/13/2608.08889v1-llm-reasoning-for-subjective-tasks-failure-modes-mitigation-and-dynamic-reasoning-routing) （7.0/10）
   evidence：通过动态推理路由缓解失败模式并降低推理开销
9. [From Relevance to Execution Utility: Reward-Aware Dynamic Execution Gating for Skill-Based LLM Agents](/202608/13/2608.09168v1-from-relevance-to-execution-utility-reward-aware-dynamic-execution-gating-for-skill-based-llm-agents) （7.0/10）
   evidence：通过预测技能执行效用避免高开销滚动，提升LLM智能体推理效率
10. [Is Per-Agent Policy Composition Safe? Rethinking Successor-Feature Transfer in Cooperative Multi-Agent Reinforcement Learning](/202608/13/2608.11658v1-is-per-agent-policy-composition-safe-rethinking-successor-feature-transfer-in-cooperative-multi-agent-reinforcement-learning) （7.0/10）
   evidence：研究协作多智能体强化学习中逐智能体策略组合的安全性
11. [EvoHarness-RL: Learning Self-Evolving Runtime Harness for Long-Horizon LLM Agents](/202608/13/2608.05446v1-evoharness-rl-learning-self-evolving-runtime-harness-for-long-horizon-llm-agents) （6.0/10）
   evidence：面向长时程LLM智能体的RL框架学习，涉及长上下文任务中的状态管理与策略学习
12. [Multi-Agent Reinforcement Learning via Agent-Specific Preference](/202608/13/2608.08604v1-multi-agent-reinforcement-learning-via-agent-specific-preference) （6.0/10）
   evidence：通过智能体特定偏好进行多智能体强化学习，与智能体集群协调相关
13. [Policy-as-logic for robust reasoning over rules](/202608/13/2608.11905v1-policy-as-logic-for-robust-reasoning-over-rules) （6.0/10）
   evidence：策略即逻辑方法在规则推理中减少约10倍词元使用并提升鲁棒性
14. [Retry, Switch, or Abstain? Learning Strategy-Aware Tool-Use Policies via Controlled Error Injection](/202608/13/2608.11977v1-retry-switch-or-abstain-learning-strategy-aware-tool-use-policies-via-controlled-error-injection) （6.0/10）
   evidence：工具使用的LLM智能体在受控错误注入下学习恢复策略

---
使用键盘方向键可在日报/论文之间快速切换。
