# 日报 · 2026-08-07

- 生成时间：2026-08-07 21:50:29 UTC
- 当次推荐总数：31
- 精读区：17
- 速读区：14

## 今日简报（AI）
今日共读31篇论文，其中精读17篇、速读14篇，重点覆盖视觉语言模型与智能体强化学习。

最值得关注的两篇满分精读：一篇提出“Fisher投影的On-Policy蒸馏”，另一篇提出“观测校准的自蒸馏”，均聚焦提升VLM/智能体训练效率与稳定性。

建议优先精读上述两篇满分论文，并结合速读中“预算感知的Text-to-SQL规划”一文，思考蒸馏与决策规划的交叉应用。

## 精读区
1. [Distill What the Student Can See: Fisher-Projected On-Policy Distillation for Vision-Language Models](/202608/07/2608.01263v2-distill-what-the-student-can-see-fisher-projected-on-policy-distillation-for-vision-language-models) （10.0/10）
   evidence：面向视觉-语言模型的在线策略蒸馏，对齐师生分布
2. [Agentic Reinforcement Learning with Observation-Calibrated Self-Distillation](/202608/07/2608.04788v1-agentic-reinforcement-learning-with-observation-calibrated-self-distillation) （10.0/10）
   evidence：面向智能体的on-policy自蒸馏，并通过观测校准解决混淆
3. [On-Policy Delta Distillation for Multilingual Math Reasoning](/202608/07/2608.05802v1-on-policy-delta-distillation-for-multilingual-math-reasoning) （10.0/10）
   evidence：面向多语言数学推理的在线策略蒸馏（OPD）
4. [DASH: Divergence-Adaptive Supervision Horizons for On-Policy Self-Distillation of Reasoning Models](/202608/07/2608.06243v1-dash-divergence-adaptive-supervision-horizons-for-on-policy-self-distillation-of-reasoning-models) （10.0/10）
   evidence：针对推理模型的on-policy自蒸馏方法，提出自适应散度监督视界
5. [On-Policy Self-Distillation without Any Supervision](/202608/07/2608.06296v1-on-policy-self-distillation-without-any-supervision) （10.0/10）
   evidence：仅用模型自身生成实现无监督在线策略自蒸馏
6. [Compliance2LoRA: Personalizable On-Demand Safety Alignment on Arbitrary Policy Subsets via Hypernetwork-Generated LoRA Adapters](/202608/07/2607.27594v3-compliance2lora-personalizable-on-demand-safety-alignment-on-arbitrary-policy-subsets-via-hypernetwork-generated-lora-adapters) （9.0/10）
   evidence：通过超网络生成LoRA适配器实现个性化按需安全对齐
7. [Invisible Ink Threats: Adversarial Goals Behind Legitimate Tasks in Computer-Use Agents](/202608/07/2608.02018v2-invisible-ink-threats-adversarial-goals-behind-legitimate-tasks-in-computer-use-agents) （9.0/10）
   evidence：计算机使用智能体面临间接提示注入等智能体安全威胁
8. [Instruction-Conditioned Exploration for Reinforcement Learning with Self-Distillation to an Unconditioned Policy](/202608/07/2608.02087v2-instruction-conditioned-exploration-for-reinforcement-learning-with-self-distillation-to-an-unconditioned-policy) （9.0/10）
   evidence：在RL训练中通过自蒸馏到无条件策略，提升LLM探索多样性
9. [$S^3$: Improving Agent Safety through Multi-Stage Defense](/202608/07/2608.02683v1-s3-improving-agent-safety-through-multi-stage-defense) （9.0/10）
   evidence：面向LLM智能体安全的多阶段防御与可组合的阶段特异性安全技能
10. [Stateful Governance for Concurrent Agentic Systems](/202608/07/2608.02764v1-stateful-governance-for-concurrent-agentic-systems) （9.0/10）
   evidence：聚焦并发智能体系统的治理与安全
11. [LatentGuard: Efficient and Inspectable Latent Reasoning for LLM Safeguards](/202608/07/2608.03838v1-latentguard-efficient-and-inspectable-latent-reasoning-for-llm-safeguards) （9.0/10）
   evidence：用于LLM安全审核的潜在推理防护模型，兼顾效率与可检查性
12. [Not Every Divergence Should Be Suppressed: Counterfactual Recoverability in On-Policy Distillation](/202608/07/2608.04408v1-not-every-divergence-should-be-suppressed-counterfactual-recoverability-in-on-policy-distillation) （9.0/10）
   evidence：在在线策略蒸馏中引入反事实可恢复性概念
13. [Agent Against Agent: An Agentic System for Automatic Prompt Injection Red Teaming](/202608/07/2608.05108v1-agent-against-agent-an-agentic-system-for-automatic-prompt-injection-red-teaming) （9.0/10）
   evidence：面向提示注入的自动化红队测试，符合红队与安全需求
14. [PromptShield Home: Ambient Multimodal Prompt Injection Defense for Smart-Home Agents](/202608/07/2608.05495v1-promptshield-home-ambient-multimodal-prompt-injection-defense-for-smart-home-agents) （9.0/10）
   evidence：面向智能家居智能体的环境多模态提示注入防御基准
15. [Hijacking Robots with a Piece of Paper: A Systematic Study of Physical Prompt Injection in VLM-Controlled Robots](/202608/07/2608.05715v1-hijacking-robots-with-a-piece-of-paper-a-systematic-study-of-physical-prompt-injection-in-vlm-controlled-robots) （9.0/10）
   evidence：针对VLM控制机器人的物理提示注入攻击及基准
16. [AgentOPSD: Recursive Self-Distillation for Agentic Reinforcement Learning](/202608/07/2608.05987v1-agentopsd-recursive-self-distillation-for-agentic-reinforcement-learning) （9.0/10）
   evidence：递归自蒸馏用于智能体强化学习
17. [RP-OPSD: Reasoning-Pivot-Guided On-Policy Self-Distillation for Multilingual Reasoning Transfer](/202608/07/2608.06347v1-rp-opsd-reasoning-pivot-guided-on-policy-self-distillation-for-multilingual-reasoning-transfer) （9.0/10）
   evidence：面向多语言推理迁移的pivot引导on-policy自蒸馏

## 速读区
1. [Opt.Gear Technical Report](/202608/07/2608.01034v2-optgear-technical-report) （8.0/10）
   evidence：通过混合架构减少KV缓存，实现长上下文下的高效端侧推理
2. [Single Canonical Prompts Underestimate LLM Safety's Surface-Form Sensitivity](/202608/07/2608.02665v1-single-canonical-prompts-underestimate-llm-safetys-surface-form-sensitivity) （8.0/10）
   evidence：安全基准：单一规范形式的评分对保持语义的表层改写高度敏感
3. [BAP-SQL: Budget-Aware Observation Planning for Agentic Text-to-SQL](/202608/07/2608.02876v1-bap-sql-budget-aware-observation-planning-for-agentic-text-to-sql) （8.0/10）
   evidence：面向智能体文本转SQL的预算感知观测规划，在少token下提升成功率
4. [PI-Mem: Pushing Long-Context Reasoning to 3.6M Tokens with Parallel-Iterative Memory](/202608/07/2608.03048v1-pi-mem-pushing-long-context-reasoning-to-36m-tokens-with-parallel-iterative-memory) （8.0/10）
   evidence：并行迭代记忆提升长上下文推理效率
5. [TaskPress: Query-Agnostic KV Cache Compression via Task-Guided Pruning](/202608/07/2608.03276v1-taskpress-query-agnostic-kv-cache-compression-via-task-guided-pruning) （8.0/10）
   evidence：面向长上下文高效推理的任务感知KV缓存压缩
6. [TabDPT-Turbo: Efficient In-Context Learning for Tabular Prediction](/202608/07/2608.01400v1-tabdpt-turbo-efficient-in-context-learning-for-tabular-prediction) （7.0/10）
   evidence：面向表格预测的高效上下文学习，速度提升数个数量级
7. [Self-Improving Large Language Models via Progressive Experience Evolution](/202608/07/2608.02139v2-self-improving-large-language-models-via-progressive-experience-evolution) （7.0/10）
   evidence：利用经验蒸馏提升大模型自我改进，与策略蒸馏/知识蒸馏方法相关
8. [Agentic Reinforcement Learning with Self-Distilled Reward Shaping](/202608/07/2608.03223v1-agentic-reinforcement-learning-with-self-distilled-reward-shaping) （7.0/10）
   evidence：面向智能体强化学习的自蒸馏奖励塑形
9. [Hierarchical Graph Memory for LLM Agents with Path-level Localization and Rewrite](/202608/07/2608.05095v1-hierarchical-graph-memory-for-llm-agents-with-path-level-localization-and-rewrite) （7.0/10）
   evidence：通过层级图记忆与路径级改写降低检索成本，提升长程推理效率
10. [Chained Recursive Language Models for Multi-Iteration Reasoning](/202608/07/2608.05124v1-chained-recursive-language-models-for-multi-iteration-reasoning) （7.0/10）
   evidence：面向长上下文多轮推理的链式递归推断架构，提升推理效率
11. [Native Multilingual Chain-of-Thought Reasoning in Low-Resource Southeast Asian Languages](/202608/07/2608.00533v1-native-multilingual-chain-of-thought-reasoning-in-low-resource-southeast-asian-languages) （6.0/10）
   evidence：对推理轨迹进行跨语言蒸馏，与知识蒸馏方法相关
12. [Reusing Rollouts under Policy Lag: Prefix-Normalized Policy Optimization for LLM Reinforcement Learning](/202608/07/2608.01418v1-reusing-rollouts-under-policy-lag-prefix-normalized-policy-optimization-for-llm-reinforcement-learning) （6.0/10）
   evidence：复用RL采样的离策略修正，可适用于策略蒸馏训练
13. [SkillTrace: Traversing a Query-Skill Graph for Composable LLM Agents](/202608/07/2608.02356v2-skilltrace-traversing-a-query-skill-graph-for-composable-llm-agents) （6.0/10）
   evidence：LLM智能体的技能组合与复杂任务分解
14. [RoMeRL: Balancing Feedback Coverage and the Memory-Reward Trap in Self-Evolving Agent Memory via Reduced-Order Utility States](/202608/07/2608.02508v1-romerl-balancing-feedback-coverage-and-the-memory-reward-trap-in-self-evolving-agent-memory-via-reduced-order-utility-states) （6.0/10）
   evidence：用降阶记忆状态处理长交互历史的RL问题，与长上下文RL相关

---
使用键盘方向键可在日报/论文之间快速切换。
