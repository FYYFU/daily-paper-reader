# 日报 · 2026-06-13

- 生成时间：2026-06-13 20:54:38 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日更新23篇论文，精读9篇，重点聚焦行为安全评估的表征层面失效机制与推理模型的分层KV缓存预算分配。最值得关注的两篇高分精读分别从表征视角反思安全评估盲区，以及通过层次化解码时缓存分配优化推理效率。建议普通读者优先精读这两篇高分论文，速读中关于长周期LLM Agent引导监控等方向也值得延伸关注。

## 精读区
1. [When Behavioral Safety Evaluation Fails: A Representation-Level Perspective](/202606/13/2606.08044v1-when-behavioral-safety-evaluation-fails-a-representation-level-perspective) （9.0/10）
   evidence：LLM表示层面的安全评估方法
2. [ReasonAlloc: Hierarchical Decoding-Time KV Cache Budget Allocation for Reasoning Models](/202606/13/2606.11164v1-reasonalloc-hierarchical-decoding-time-kv-cache-budget-allocation-for-reasoning-models) （9.0/10）
   evidence：面向高效推理的分层KV缓存分配
3. [The Role of Feedback Alignment in Self-Distillation](/202606/13/2606.11173v1-the-role-of-feedback-alignment-in-self-distillation) （9.0/10）
   evidence：自蒸馏：教师-学生框架下的知识蒸馏
4. [Acoda: Adversarial Code Obfuscation for Defending against LLM-based Analysis](/202606/13/2606.11755v1-acoda-adversarial-code-obfuscation-for-defending-against-llm-based-analysis) （9.0/10）
   evidence：针对基于LLM分析的对抗代码混淆防御
5. [Grammar-Constrained Decoding Can Jailbreak LLMs into Generating Malicious Code](/202606/13/2606.11817v1-grammar-constrained-decoding-can-jailbreak-llms-into-generating-malicious-code) （9.0/10）
   evidence：通过语法约束解码实现的越狱攻击
6. [Semantic Quorum Assurance: Collective Certification for Non-Deterministic AI Infrastructure](/202606/13/2606.08021v1-semantic-quorum-assurance-collective-certification-for-non-deterministic-ai-infrastructure) （8.0/10）
   evidence：自主操作中的智能体安全
7. [From Holistic Evaluation to Structured Criteria: Rubrics Across the Evolving LLM Landscape](/202606/13/2606.08625v1-from-holistic-evaluation-to-structured-criteria-rubrics-across-the-evolving-llm-landscape) （8.0/10）
   evidence：用于LLM评估和安全对齐的评量标准框架
8. [Agent Skill Evaluation and Evolution: Frameworks and Benchmarks](/202606/13/2606.11435v1-agent-skill-evaluation-and-evolution-frameworks-and-benchmarks) （8.0/10）
   evidence：综述了轨迹蒸馏和强化学习在技能演化中的应用
9. [Dummy Backdoor as a Defense: Removing Unknown Backdoors via Shared Internal Mechanisms for Generative LLMs](/202606/13/2606.11648v1-dummy-backdoor-as-a-defense-removing-unknown-backdoors-via-shared-internal-mechanisms-for-generative-llms) （8.0/10）
   evidence：大语言模型后门攻击防御

## 速读区
1. [Q-Delta: Beyond Key-Value Associative State Evolution](/202606/13/2606.08804v1-q-delta-beyond-key-value-associative-state-evolution) （8.0/10）
   evidence：用于高效线性注意力推理的查询感知delta规则
2. [HIPIF: Hierarchical Planning and Information Folding for Long-Horizon LLM Agent Learning](/202606/13/2606.10507v1-hipif-hierarchical-planning-and-information-folding-for-long-horizon-llm-agent-learning) （8.0/10）
   evidence：长视界LLM智能体学习，通过分层RL解决长上下文干扰
3. [Bootstrapped Monitoring: Leveraging Transparent Reasoning to Oversee Stronger AI Agents](/202606/13/2606.11998v1-bootstrapped-monitoring-leveraging-transparent-reasoning-to-oversee-stronger-ai-agents) （8.0/10）
   evidence：引导式监控协议用于智能体安全监督
4. [ALIGNBEAM : Inference-Time Alignment Transfer via Cross-Vocabulary Logit Mixing](/202606/13/2606.12342v1-alignbeam--inference-time-alignment-transfer-via-cross-vocabulary-logit-mixing) （8.0/10）
   evidence：推理时安全防御对抗越狱攻击
5. [AdMem: Advanced Memory for Task-solving Agents](/202606/13/2606.06787v1-admem-advanced-memory-for-task-solving-agents) （7.0/10）
   evidence：用于任务求解智能体的多智能体记忆框架
6. [The Easy, the Hard, and the Learnable: Confidence and Difficulty-Adaptive Policy Optimization for LLM Reasoning](/202606/13/2606.07950v1-the-easy-the-hard-and-the-learnable-confidence-and-difficulty-adaptive-policy-optimization-for-llm-reasoning) （7.0/10）
   evidence：置信度与难度自适应策略优化提高LLM推理效率
7. [DICE: Entropy-Regularized Equilibrium Selection for Stable Multi-Agent LLM Coordination](/202606/13/2606.08068v1-dice-entropy-regularized-equilibrium-selection-for-stable-multi-agent-llm-coordination) （7.0/10）
   evidence：通过均衡选择实现多智能体LLM稳定协调
8. [RiskNet: A large-scale dataset of AI risk incidents from news with alignment and multi-dimensional annotations](/202606/13/2606.08376v1-risknet-a-large-scale-dataset-of-ai-risk-incidents-from-news-with-alignment-and-multi-dimensional-annotations) （7.0/10）
   evidence：AI风险事件数据集用于安全评估
9. [Game-Theoretic Multi-Agent Control for Robust Contextual Reasoning in LLMs](/202606/13/2606.10322v1-game-theoretic-multi-agent-control-for-robust-contextual-reasoning-in-llms) （7.0/10）
   evidence：针对提示注入和上下文中毒的多智能体防御
10. [Beyond Uniform Token-Level Trust Region in LLM Reinforcement Learning](/202606/13/2606.10968v1-beyond-uniform-token-level-trust-region-in-llm-reinforcement-learning) （7.0/10）
   evidence：超越均匀token级信任区域，提升LLM RL效率
11. [TRACE: A Unified Rollout Budget Allocation Framework for Efficient Agentic Reinforcement Learning](/202606/13/2606.11119v1-trace-a-unified-rollout-budget-allocation-framework-for-efficient-agentic-reinforcement-learning) （7.0/10）
   evidence：为提升推理效率而设计的回滚预算分配框架
12. [Reformulate LLM Reinforcement Learning for Efficient Training under Black-box Discrepancy](/202606/13/2606.08779v2-reformulate-llm-reinforcement-learning-for-efficient-training-under-black-box-discrepancy) （6.0/10）
   evidence：在训练-推理偏差下提升LLM强化学习训练效率
13. [Inference-Time Conformal Reasoning with Valid Factuality Control for Large Language Models](/202606/13/2606.08831v1-inference-time-conformal-reasoning-with-valid-factuality-control-for-large-language-models) （6.0/10）
   evidence：推理时事实性控制增强LLM安全性
14. [MARCH: Model-Assisted Reinforcement Learning for the Perceptive Control of Humanoids over Sparse Footholds](/202606/13/2606.10288v1-march-model-assisted-reinforcement-learning-for-the-perceptive-control-of-humanoids-over-sparse-footholds) （6.0/10）
   evidence：强化学习中的教师-学生蒸馏用于运动控制

---
使用键盘方向键可在日报/论文之间快速切换。
