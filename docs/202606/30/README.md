# 日报 · 2026-06-30

- 生成时间：2026-06-30 22:30:43 UTC
- 当次推荐总数：34
- 精读区：20
- 速读区：14

## 今日简报（AI）
1) 今日在线策略蒸馏领域双星闪耀，两篇满分论文分别提出熵引导监督（SEAD）与特权隐式流（PHF）方法，刷新同策略自蒸馏效率。  
2) 最值得深挖的方向：在线自蒸馏的监督信号设计（SEAD）与隐式知识传递（PHF）；速读中ReM-MoA的推理记忆扩展与进度优势后训练同样值得关注。  
3) 建议优先精读SEAD与PHF理解蒸馏核心，再结合ReM-MoA探索智能体扩展，并关注RL奖励黑客的修正价值学习方法。

## 精读区
1. [SEAD: Competence-Aware On-Policy Distillation via Entropy-Guided Supervision](/202606/30/2606.28562v1-sead-competence-aware-on-policy-distillation-via-entropy-guided-supervision) （10.0/10）
   evidence：提出能力感知的在线策略蒸馏方法，使用熵引导监督
2. [PHF: Privileged Hidden Flow for On-Policy Self-Distillation](/202606/30/2606.29340v1-phf-privileged-hidden-flow-for-on-policy-self-distillation) （10.0/10）
   evidence：在线策略自蒸馏，融入特权隐藏流
3. [UCOB: Learning to Utilize and Evolve Agentic Skills via Credit-Aware On-Policy Bidirectional Self-Distillation](/202606/30/2606.29502v1-ucob-learning-to-utilize-and-evolve-agentic-skills-via-credit-aware-on-policy-bidirectional-self-distillation) （10.0/10）
   evidence：面向智能体技能的在线策略双向自蒸馏
4. [MOPD: Multi-Teacher On-Policy Distillation for Capability Integration in LLM Post-Training](/202606/30/2606.30406v1-mopd-multi-teacher-on-policy-distillation-for-capability-integration-in-llm-post-training) （10.0/10）
   evidence：用于LLM后训练的多教师在线策略蒸馏，结合RL教师
5. [Agent Safety Is Action Alignment](/202606/30/2606.28739v1-agent-safety-is-action-alignment) （9.0/10）
   evidence：论证智能体安全是行为对齐而非内容安全
6. [Divergence-based Safety Measure for Large Language Models via Rational Inattention](/202606/30/2606.29081v1-divergence-based-safety-measure-for-large-language-models-via-rational-inattention) （9.0/10）
   evidence：基于散度的LLM攻击下安全度量
7. [Breaking the Rounding Trap: Securing LLMs against Quantization-Conditioned Backdoors](/202606/30/2606.29239v1-breaking-the-rounding-trap-securing-llms-against-quantization-conditioned-backdoors) （9.0/10）
   evidence：针对量化条件后门攻击的防御方法
8. [Process Advantage Signal Shaping: A Paradigm-Agnostic Middleware for Process-Supervised RL in LLM Reasoners](/202606/30/2606.29296v1-process-advantage-signal-shaping-a-paradigm-agnostic-middleware-for-process-supervised-rl-in-llm-reasoners) （9.0/10）
   evidence：明确提及在策略蒸馏KL信号用于过程监督强化学习
9. [When LLMs Develop Languages: Symbolic Communication for Efficient Multi-Agent Reasoning](/202606/30/2606.29354v1-when-llms-develop-languages-symbolic-communication-for-efficient-multi-agent-reasoning) （9.0/10）
   evidence：通过符号语言实现高效多智能体推理
10. [CRAFT: Counterfactual Credit Assignment from Free Sibling Rollouts for Self-Distilled Agentic Reinforcement Learning](/202606/30/2606.29476v1-craft-counterfactual-credit-assignment-from-free-sibling-rollouts-for-self-distilled-agentic-reinforcement-learning) （9.0/10）
   evidence：面向自蒸馏体强化学习的反事实信用分配
11. [Coverage-Driven KV Cache Eviction for Efficient and Improved Inference of LLM](/202606/30/2606.29563v1-coverage-driven-kv-cache-eviction-for-efficient-and-improved-inference-of-llm) （9.0/10）
   evidence：通过KV缓存驱逐实现高效推理
12. [The Joint Effect of Quantization and Sampling Temperature on LLM Safety Alignment: A Factorial Analysis](/202606/30/2606.29581v1-the-joint-effect-of-quantization-and-sampling-temperature-on-llm-safety-alignment-a-factorial-analysis) （9.0/10）
   evidence：量化和温度对LLM安全性的联合影响分析
13. [An Empirical Evaluation of Prompt Injection Vulnerabilities in Large Language Models Across Multilingual and Obfuscated Attack Scenarios](/202606/30/2606.29602v1-an-empirical-evaluation-of-prompt-injection-vulnerabilities-in-large-language-models-across-multilingual-and-obfuscated-attack-scenarios) （9.0/10）
   evidence：多语言和混淆攻击场景下提示注入漏洞的实证评估
14. [Safety from Honesty in a Disinterested AI Predictor](/202606/30/2606.29657v1-safety-from-honesty-in-a-disinterested-ai-predictor) （9.0/10）
   evidence：提出基于诚实与认识语境化的AI预测器安全论证
15. [ARKD: Adaptive Reinforcement Learning-Guided Bidirectional KL Divergence Distillation for Text Generation](/202606/30/2606.29869v1-arkd-adaptive-reinforcement-learning-guided-bidirectional-kl-divergence-distillation-for-text-generation) （9.0/10）
   evidence：强化学习引导的双向KL散度蒸馏用于文本生成
16. [SafePyramid: A Hierarchical Benchmark for In-context Policy Guardrailing](/202606/30/2606.29887v1-safepyramid-a-hierarchical-benchmark-for-in-context-policy-guardrailing) （9.0/10）
   evidence：面向上下文策略防护的基准，包含10个领域1000轮多轮对话
17. [Building Multi-Task Agentic LLMs via Two-Phase Distillation](/202606/30/2606.30044v1-building-multi-task-agentic-llms-via-two-phase-distillation) （9.0/10）
   evidence：两阶段蒸馏框架，分析on-policy与off-policy蒸馏在多任务场景下的表现
18. [Defending Against Harmful Supervision Hidden in Benign Samples](/202606/30/2606.30263v1-defending-against-harmful-supervision-hidden-in-benign-samples) （9.0/10）
   evidence：通过隐藏有害监督的嵌有攻击及防御方法
19. [DRIFT: Difficulty Routing Self-DIstillation with Rhythm-Gated Exploration and Success BuFfer Training](/202606/30/2606.30345v1-drift-difficulty-routing-self-distillation-with-rhythm-gated-exploration-and-success-buffer-training) （9.0/10）
   evidence：针对大语言模型的自蒸馏框架，包含难度路由与节奏门控
20. [DOPD: Dual On-policy Distillation](/202606/30/2606.30626v1-dopd-dual-on-policy-distillation) （9.0/10）
   evidence：双在线策略蒸馏方法

## 速读区
1. [ReM-MoA: Reasoning Memory Sustains Mixture-of-Agents Scaling](/202606/30/2606.24437v1-rem-moa-reasoning-memory-sustains-mixture-of-agents-scaling) （8.0/10）
   evidence：记忆增强的混合智能体框架，实现持续的推理扩展
2. [Neglected Free Lunch from Post-training: Progress Advantage for LLM Agents](/202606/30/2606.26080v1-neglected-free-lunch-from-post-training-progress-advantage-for-llm-agents) （8.0/10）
   evidence：利用RL策略与参考策略的对数概率比作为进度优势，类似于在线自蒸馏
3. [Modification-Considering Value Learning for Reward Hacking Mitigation in RL](/202606/30/2606.28955v1-modification-considering-value-learning-for-reward-hacking-mitigation-in-rl) （8.0/10）
   evidence：基于修正考虑的价值学习以缓解强化学习中的奖励黑客问题
4. [Bad company corrupts good morals: Understanding and Measuring Narrative-Induced Moral Reasoning Degradation in LLMs](/202606/30/2606.28981v1-bad-company-corrupts-good-morals-understanding-and-measuring-narrative-induced-moral-reasoning-degradation-in-llms) （8.0/10）
   evidence：叙事诱导的大语言模型道德推理退化
5. [Memory as an Attack Surface in LLM Agents: A Study on Multiple-Choice Question Answering](/202606/30/2606.29030v1-memory-as-an-attack-surface-in-llm-agents-a-study-on-multiple-choice-question-answering) （8.0/10）
   evidence：记忆作为LLM智能体的攻击面
6. [ThinkProbe: Beyond Accuracy -- Structural Profiling of Open-Ended LLM Reasoning Traces via Non-Generative Thought Graphs](/202606/30/2606.29067v1-thinkprobe-beyond-accuracy----structural-profiling-of-open-ended-llm-reasoning-traces-via-non-generative-thought-graphs) （8.0/10）
   evidence：推理痕迹的结构化分析，包含效率维度
7. [Behavior Uncloning: Distilling Mode Redirection into Policy Weights without Inference-Time Steering](/202606/30/2606.29201v1-behavior-uncloning-distilling-mode-redirection-into-policy-weights-without-inference-time-steering) （8.0/10）
   evidence：将模式重定向信号蒸馏到策略权重中以避免不安全行为
8. [Understanding Evaluation Illusion in Diffusion Large Language Models](/202606/30/2606.29228v1-understanding-evaluation-illusion-in-diffusion-large-language-models) （8.0/10）
   evidence：对扩散大语言模型高效解码策略的评估
9. [Toward Secure and Reliable PDDL Formalization of Large Language Models with Planner-in-the-Loop Feedback](/202606/30/2606.29700v1-toward-secure-and-reliable-pddl-formalization-of-large-language-models-with-planner-in-the-loop-feedback) （7.0/10）
   evidence：面向安全PDDL形式化的基准和规划器可验证可执行性
10. [KbSD: Knowledge Boundary aware Self-Distillation for Behavioral Calibration in Agentic Search](/202606/30/2606.29863v1-kbsd-knowledge-boundary-aware-self-distillation-for-behavioral-calibration-in-agentic-search) （7.0/10）
   evidence：智能体搜索中基于知识边界的自蒸馏框架
11. [A Physics-Grounded Benchmark for Multi-Agent Dynamics in World Models](/202606/30/2606.28757v1-a-physics-grounded-benchmark-for-multi-agent-dynamics-in-world-models) （6.0/10）
   evidence：针对世界模型中安全关键多智能体动力学的基准
12. [HyphaeDB: A Living Knowledge Topology for Agent-First Memory](/202606/30/2606.28781v1-hyphaedb-a-living-knowledge-topology-for-agent-first-memory) （6.0/10）
   evidence：面向多智能体的原生记忆基础设施，支持知识传播
13. [PS-PPO: Prefix-Sampling PPO for Critic-Free RLHF](/202606/30/2606.29758v1-ps-ppo-prefix-sampling-ppo-for-critic-free-rlhf) （6.0/10）
   evidence：通过前缀采样提高RLHF计算效率，降低长推理轨迹成本
14. [Dynamo: Dynamic Skill-Tool Evolution for Vision-Language Agents](/202606/30/2606.30185v1-dynamo-dynamic-skill-tool-evolution-for-vision-language-agents) （6.0/10）
   evidence：无需训练的视觉推理技能与工具进化，提升推理效率

---
使用键盘方向键可在日报/论文之间快速切换。
