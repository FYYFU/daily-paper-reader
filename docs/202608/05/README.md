# 日报 · 2026-08-05

- 生成时间：2026-08-05 21:56:23 UTC
- 当次推荐总数：27
- 精读区：13
- 速读区：14

## 今日简报（AI）
今日精读13篇、速读14篇，共27篇论文，聚焦LLM智能体与强化学习前沿。最值得关注两篇满分研究：弱到强在线策略蒸馏（10.0）与LTL形式监控器失效边界（10.0），揭示安全与训练效率关键突破。建议普通读者优先浏览LLM智能体安全监控及知识蒸馏方向的实用结论。

## 精读区
1. [Weak-to-Strong On-Policy Distillation](/202608/05/2607.26246v2-weak-to-strong-on-policy-distillation) （10.0/10）
   evidence：弱到强在线策略蒸馏
2. [Why Formal Monitors Fail: Attack Distribution Entropy as a Coverage Bound for LTL-Based LLM Agent Safety](/202608/05/2608.01388v1-why-formal-monitors-fail-attack-distribution-entropy-as-a-coverage-bound-for-ltl-based-llm-agent-safety) （10.0/10）
   evidence：面向LLM智能体的形式化运行时安全监控器，攻击覆盖率理论界
3. [SMOPD: Multi-Reward Reinforcement Learning via Specialize-and-Merge Online Policy Distillation](/202608/05/2608.03092v1-smopd-multi-reward-reinforcement-learning-via-specialize-and-merge-online-policy-distillation) （10.0/10）
   evidence：面向多奖励RL的在线策略蒸馏
4. [Language-Specialized Multi-Teacher On-Policy Distillation for Multilingual LLM-Based ASR](/202608/05/2608.03610v1-language-specialized-multi-teacher-on-policy-distillation-for-multilingual-llm-based-asr) （10.0/10）
   evidence：提出语言专化多教师在线策略蒸馏，是on-policy distillation的直接应用
5. [When Teachers Mislead: Spurious-Signal-Aware On-Policy Distillation](/202608/05/2608.03632v1-when-teachers-mislead-spurious-signal-aware-on-policy-distillation) （10.0/10）
   evidence：识别在线策略蒸馏中的虚假监督信号并提出SA-OPD以缓解其影响
6. [CausalOPD: First-Wrong-Step Supervision for Distilling Causal Chain Reasoning](/202608/05/2608.03673v1-causalopd-first-wrong-step-supervision-for-distilling-causal-chain-reasoning) （10.0/10）
   evidence：面向因果链推理的首错步骤监督在线策略蒸馏
7. [SERL-SQL: Selective Hindsight Distillation for Text-to-SQL Reinforcement Agentic Learning](/202608/05/2608.00485v2-serl-sql-selective-hindsight-distillation-for-text-to-sql-reinforcement-agentic-learning) （9.0/10）
   evidence：师生蒸馏，在策略SQL轨迹，GRPO优势重加权
8. [Distill What the Student Can See: Fisher-Projected On-Policy Distillation for Vision-Language Models](/202608/05/2608.01263v1-distill-what-the-student-can-see-fisher-projected-on-policy-distillation-for-vision-language-models) （9.0/10）
   evidence：面向视觉语言模型的Fisher投影在线蒸馏，依据学生可见性调整蒸馏目标
9. [Remember-R1: Mitigating Long-Context Visual Forgetting through Reinforcement Learning](/202608/05/2608.01314v1-remember-r1-mitigating-long-context-visual-forgetting-through-reinforcement-learning) （9.0/10）
   evidence：面向多模态大模型长上下文的强化学习，缓解长链推理中的视觉遗忘
10. [LongCat Sparse Attention: Taming the Lightning via Streaming-aware Hierarchical Cross-Layer Indexing](/202608/05/2608.01662v1-longcat-sparse-attention-taming-the-lightning-via-streaming-aware-hierarchical-cross-layer-indexing) （9.0/10）
   evidence：面向长上下文推理效率的软硬件协同稀疏注意力方法
11. [Moving the Safety Barrier: Dynamic Routing Adaptive Alignment Against White-Box Attacks](/202608/05/2608.02674v1-moving-the-safety-barrier-dynamic-routing-adaptive-alignment-against-white-box-attacks) （9.0/10）
   evidence：面向白盒攻击的动态路由自适应对齐安全防御
12. [ICO: Enhancing Semantic-Shift Jailbreaks via Iterative Context Optimization](/202608/05/2608.03210v1-ico-enhancing-semantic-shift-jailbreaks-via-iterative-context-optimization) （9.0/10）
   evidence：通过迭代上下文优化增强语义偏移越狱攻击
13. [TurnSight: Turn-Level Hindsight Self-Distillation for Tool-Integrated Reasoning](/202608/05/2608.04007v1-turnsight-turn-level-hindsight-self-distillation-for-tool-integrated-reasoning) （9.0/10）
   evidence：面向工具集成推理的回合级事后自蒸馏

## 速读区
1. [$Σ$-Mem: An Online Reliability Memory for LLM-based Multi-Agent Systems](/202608/05/2607.27958v1--mem-an-online-reliability-memory-for-llm-based-multi-agent-systems) （8.0/10）
   evidence：面向LLM多智能体系统的在线可靠性记忆，支撑智能体集群长期协作
2. [Distilling Knowledge from Large Language Models into Lightweight Reinforcement Learning Agents for Autonomous Cyber Operations](/202608/05/2607.28826v1-distilling-knowledge-from-large-language-models-into-lightweight-reinforcement-learning-agents-for-autonomous-cyber-operations) （8.0/10）
   evidence：将LLM知识蒸馏到轻量级强化学习智能体
3. [HetGPS: Scalable Graph Multi-Agent Reinforcement Learning with Physics-Anchored Adaptive Safety for EV Charging](/202608/05/2608.00679v1-hetgps-scalable-graph-multi-agent-reinforcement-learning-with-physics-anchored-adaptive-safety-for-ev-charging) （8.0/10）
   evidence：多智能体强化学习安全干预、物理锚定自适应安全
4. [The Boy Who Cried Wolf: Adversarial Misclassification of Safe Inputs as Unsafe in Multimodal Guardrails](/202608/05/2608.01373v1-the-boy-who-cried-wolf-adversarial-misclassification-of-safe-inputs-as-unsafe-in-multimodal-guardrails) （8.0/10）
   evidence：提出不安全语义蒸馏攻击，使护栏模型对良性输入产生误拒
5. [Shared Prefixes, Better Credit: Adaptive Routing for Multi-Agent Reasoning](/202608/05/2608.02291v1-shared-prefixes-better-credit-adaptive-routing-for-multi-agent-reasoning) （8.0/10）
   evidence：基于共享前缀信用分配的高效自适应多智能体推理
6. [Cross-Benchmark Generalization in Long-Horizon Agents](/202608/05/2608.00181v1-cross-benchmark-generalization-in-long-horizon-agents) （7.0/10）
   evidence：长时程智能体任务的强化学习训练，跨基准泛化。
7. [Personalizing Large Language Model Agents with Small Policy Models](/202608/05/2608.00215v1-personalizing-large-language-model-agents-with-small-policy-models) （7.0/10）
   evidence：面向LLM智能体的可调用工具与执行策略个性化，与智能体集群任务执行相关
8. [Gram-Space: Structure-Preserving Codebook Compression for Memory-Efficient Neuro-Symbolic AI](/202608/05/2608.01528v1-gram-space-structure-preserving-codebook-compression-for-memory-efficient-neuro-symbolic-ai) （7.0/10）
   evidence：面向记忆高效神经符号推理的结构保持压缩
9. [IACM-RL: Intent-Aware Context Management and Reinforcement Learning for Complex Tool Invocation under Dynamic Intent Fluctuations](/202608/05/2608.02110v1-iacm-rl-intent-aware-context-management-and-reinforcement-learning-for-complex-tool-invocation-under-dynamic-intent-fluctuations) （7.0/10）
   evidence：面向长时程工具调用的上下文管理与强化学习，应对动态意图波动
10. [SkillTrace: Traversing a Query-Skill Graph for Composable LLM Agents](/202608/05/2608.02356v2-skilltrace-traversing-a-query-skill-graph-for-composable-llm-agents) （7.0/10）
   evidence：可组合智能体，通过技能图完成复杂任务分解与执行
11. [CascadeLUT: Information-Ordered Streaming Inference for Bandwidth-Constrained FPGAs](/202608/05/2608.00720v1-cascadelut-information-ordered-streaming-inference-for-bandwidth-constrained-fpgas) （6.0/10）
   evidence：在带宽受限FPGA上的推理效率优化，流式推理。
12. [RING: Retrieval-Internalized Generation for Continual Large-Scale Knowledge Injection](/202608/05/2608.01630v1-ring-retrieval-internalized-generation-for-continual-large-scale-knowledge-injection) （6.0/10）
   evidence：通过检索内化和强化学习训练降低推理时延，面向推理效率
13. [Beyond On-Policy Exploration: Integrating External Policy Rollouts for Reinforcement Learning in Diffusion Language Models](/202608/05/2608.01717v1-beyond-on-policy-exploration-integrating-external-policy-rollouts-for-reinforcement-learning-in-diffusion-language-models) （6.0/10）
   evidence：在策略RL中利用外部策略轨迹作为类似蒸馏的监督
14. [PI-Mem: Pushing Long-Context Reasoning to 3.6M Tokens with Parallel-Iterative Memory](/202608/05/2608.03048v1-pi-mem-pushing-long-context-reasoning-to-36m-tokens-with-parallel-iterative-memory) （6.0/10）
   evidence：长上下文推理的并行迭代记忆机制，可服务长序列RL训练

---
使用键盘方向键可在日报/论文之间快速切换。
