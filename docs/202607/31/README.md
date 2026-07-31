# 日报 · 2026-07-31

- 生成时间：2026-07-31 22:20:22 UTC
- 当次推荐总数：24
- 精读区：10
- 速读区：14

## 今日简报（AI）
今日24篇论文，精读10篇，聚焦AI安全与对齐前沿。最值得看：GPT-Red用自博弈实现规模化红队测试，FAVA以权限图为智能体提供证据化授权。建议普通读者重点关注多智能体系统的恶意传播防护与规范基础设施。

## 精读区
1. [GPT-Red: Automated Red Teaming via Self-Play at Scale](/202607/31/2607.26115v1-gpt-red-automated-red-teaming-via-self-play-at-scale) （9.0/10）
   evidence：通过自博弈训练自动化红队智能体，用于发现提示注入攻击并对抗训练防御
2. [FAVA: Formal Authorization for Verified Agents with Evidence-Backed Permission Graphs](/202607/31/2607.27267v1-fava-formal-authorization-for-verified-agents-with-evidence-backed-permission-graphs) （9.0/10）
   evidence：面向可验证LLM智能体的形式化授权框架，直接面向智能体安全
3. [RoguePrompt: Dual-Layer Encoding for Self-Reconstruction to Circumvent LLM Moderation](/202607/31/2607.27373v1-rogueprompt-dual-layer-encoding-for-self-reconstruction-to-circumvent-llm-moderation) （9.0/10）
   evidence：通过提示词逃逸绕过LLM审核的越狱攻击
4. [Beyond the Best Teacher: Expanding and Compressing the Reasoning Solution Manifold](/202607/31/2607.27770v1-beyond-the-best-teacher-expanding-and-compressing-the-reasoning-solution-manifold) （9.0/10）
   evidence：提出多教师策略蒸馏的扩展-压缩框架，将RL策略视为局部探测
5. [Not All Tokens Deserve Equal Credit: Counterfactual Sensitivity Credit Reallocation for Long-CoT Reasoning](/202607/31/2607.27888v1-not-all-tokens-deserve-equal-credit-counterfactual-sensitivity-credit-reallocation-for-long-cot-reasoning) （9.0/10）
   evidence：面向长思维链推理的在线策略自蒸馏，通过非特权策略与特权自教师之间的前向KL提供密集监督
6. [One Anchor for All: Unified Multilingual and Multimodal Safety Alignment for LVLMs](/202607/31/2607.27917v1-one-anchor-for-all-unified-multilingual-and-multimodal-safety-alignment-for-lvlms) （9.0/10）
   evidence：神经元级安全对齐，统一防御多语言多模态大型视觉语言模型的复合攻击
7. [From Scoring to Acting: Outcome-Verified Comparative Self-Distillation for LLM Agents](/202607/31/2607.27937v1-from-scoring-to-acting-outcome-verified-comparative-self-distillation-for-llm-agents) （9.0/10）
   evidence：直接提出结果验证比较自蒸馏，属于LLM智能体的on-policy自蒸馏方法
8. [Contrastive Reinforced Policy Optimization via Privileged Self-Distillation](/202607/31/2607.28026v1-contrastive-reinforced-policy-optimization-via-privileged-self-distillation) （9.0/10）
   evidence：直接提出基于在线自蒸馏的对比强化策略优化方法
9. [Group-Reflective Self-Distillation for Agentic Reinforcement Learning](/202607/31/2607.28076v1-group-reflective-self-distillation-for-agentic-reinforcement-learning) （9.0/10）
   evidence：利用策略自身验证轨迹进行自蒸馏，用于智能体强化学习
10. [$β$-OPSD: Deriving with Policy Optimization, Training with Self-Distillation](/202607/31/2607.28582v1--opsd-deriving-with-policy-optimization-training-with-self-distillation) （9.0/10）
   evidence：将在线自蒸馏推导为β权重的策略优化族，用于推理语言模型

## 速读区
1. [Rethinking Classifier-Free Guidance in On-Policy Diffusion Distillation](/202607/31/2607.24731v2-rethinking-classifier-free-guidance-in-on-policy-diffusion-distillation) （8.0/10）
   evidence：在线扩散蒸馏，分析无分类器指导与速度匹配的交互
2. [The Missing Layer: Specification Infrastructure for AI Oversight](/202607/31/2607.24866v1-the-missing-layer-specification-infrastructure-for-ai-oversight) （8.0/10）
   evidence：面向智能体系统的监督基础设施，涉及智能体安全与评估
3. [SafeFlow: Semantic Information-Flow Control for Blocking Malicious Propagation in Multi-Agent Systems](/202607/31/2607.25255v2-safeflow-semantic-information-flow-control-for-blocking-malicious-propagation-in-multi-agent-systems) （8.0/10）
   evidence：多智能体安全防御，阻断恶意传播
4. [Bridging Inference-Time Scaling and Episodic Memory with Action-Centric Graphs](/202607/31/2607.27415v1-bridging-inference-time-scaling-and-episodic-memory-with-action-centric-graphs) （8.0/10）
   evidence：针对智能体推理时扩展的低效问题，提出基于动作图的情节记忆
5. [Compliance2LoRA: On-Demand Safety Alignment on Arbitrary Policy Subsets via Hypernetwork-Generated LoRA Adapters](/202607/31/2607.27594v1-compliance2lora-on-demand-safety-alignment-on-arbitrary-policy-subsets-via-hypernetwork-generated-lora-adapters) （8.0/10）
   evidence：通过超网络生成LoRA适配器实现任意策略子集的按需安全对齐
6. [AttriMem: Attribution-Guided Process Feedback for Agent Memory Learning](/202607/31/2607.21106v1-attrimem-attribution-guided-process-feedback-for-agent-memory-learning) （7.0/10）
   evidence：用强化学习学习智能体记忆策略，并利用过程反馈，支持长上下文
7. [From RLVR to RLSVR: Task Transformation Induces Self-Verifiable Rewards for Open-Ended LLM Self-Improvement](/202607/31/2607.23802v1-from-rlvr-to-rlsvr-task-transformation-induces-self-verifiable-rewards-for-open-ended-llm-self-improvement) （7.0/10）
   evidence：通过可自验证奖励替代LLM评测者，降低推理成本
8. [Asymmetric Collapse in Model Merging: When Refusal Over- writes Recognition](/202607/31/2607.27240v1-asymmetric-collapse-in-model-merging-when-refusal-over--writes-recognition) （7.0/10）
   evidence：模型合并保留越狱拒绝但覆盖识别能力，影响安全评测与防御
9. [SKIMIX: Multi-Agent Harness-Time Scaling with Skill Mixture for Dynamic Harness Engineering](/202607/31/2607.27994v1-skimix-multi-agent-harness-time-scaling-with-skill-mixture-for-dynamic-harness-engineering) （7.0/10）
   evidence：多智能体框架，具备动态技能路由与演化，契合智能体集群主题
10. [Hierarchical Multilevel Monte Carlo for Order-Optimal Neural Actor-Critic in Average-Reward CMDPs](/202607/31/2607.28390v1-hierarchical-multilevel-monte-carlo-for-order-optimal-neural-actor-critic-in-average-reward-cmdps) （7.0/10）
   evidence：面向安全关键强化学习的约束MDP与神经actor-critic
11. [PATS: Policy-Aware Training Scaffolding for Agentic Reinforcement Learning](/202607/31/2607.21419v2-pats-policy-aware-training-scaffolding-for-agentic-reinforcement-learning) （6.0/10）
   evidence：基于最新策略回滚构建训练支架，与on-policy蒸馏主题相关
12. [Nanbeige4.2-3B: Unlocking Agentic Capabilities in a Compact Mode](/202607/31/2607.22083v1-nanbeige42-3b-unlocking-agentic-capabilities-in-a-compact-mode) （6.0/10）
   evidence：紧凑智能体模型与参数高效架构兼顾推理能力，契合高效推理模型需求
13. [Nanbeige4.2-3B: Unlocking Agentic Capabilities in a Compact Model](/202607/31/2607.22083v2-nanbeige42-3b-unlocking-agentic-capabilities-in-a-compact-model) （6.0/10）
   evidence：3B参数紧凑模型结合RL流水线提升推理效率与智能体能力
14. [GLST: Defending Confidence-Driven V2X Collaborative Perception Against Stealthy Multi-Attacker Feature Injection](/202607/31/2607.23059v1-glst-defending-confidence-driven-v2x-collaborative-perception-against-stealthy-multi-attacker-feature-injection) （6.0/10）
   evidence：针对协同感知中隐秘特征注入攻击的防御机制

---
使用键盘方向键可在日报/论文之间快速切换。
