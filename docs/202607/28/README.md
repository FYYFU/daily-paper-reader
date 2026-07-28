# 日报 · 2026-07-28

- 生成时间：2026-07-28 21:00:20 UTC
- 当次推荐总数：24
- 精读区：10
- 速读区：14

## 今日简报（AI）
今日精读聚焦于多模态大模型的自蒸馏与扩散蒸馏中的无分类器指导，两篇满分论文揭示了前沿改进方向。  
最值得关注的是《RP-OPSD》提出的分辨率特权在线自蒸馏，以及重新思考无分类器引导在扩散蒸馏中的作用。  
建议研究者深入研读这两篇满分工作，同时可速读速读列表中的混合自我蒸馏等补充成果以拓展思路。

## 精读区
1. [RP-OPSD: Resolution-Privileged On-Policy Self-Distillation for Multimodal Large Language Models](/202607/28/2607.24447v1-rp-opsd-resolution-privileged-on-policy-self-distillation-for-multimodal-large-language-models) （10.0/10）
   evidence：利用分辨率特权进行多模态大语言模型的在线自蒸馏
2. [Rethinking Classifier-Free Guidance in On-Policy Diffusion Distillation](/202607/28/2607.24731v1-rethinking-classifier-free-guidance-in-on-policy-diffusion-distillation) （10.0/10）
   evidence：扩散模型中的在线蒸馏与无分类器引导
3. [H$^2$SD: Hybrid Hindsight Self-Distillation](/202607/28/2607.18955v3-h2sd-hybrid-hindsight-self-distillation) （9.0/10）
   evidence：用于可验证奖励强化学习的混合事后自蒸馏
4. [SLPO: Scaling Latent Reasoning via a Surrogate Policy](/202607/28/2607.19691v2-slpo-scaling-latent-reasoning-via-a-surrogate-policy) （9.0/10）
   evidence：使用替代策略扩展潜在推理
5. [OpenSkillRisk: Benchmarking Agent Safety When Using Real-World Risky Third-Party Skills](/202607/28/2607.20121v2-openskillrisk-benchmarking-agent-safety-when-using-real-world-risky-third-party-skills) （9.0/10）
   evidence：针对使用第三方技能时智能体安全性的基准测试
6. [Mask2Shield: Strengthening LLM Safety against Neuron-Pruning Attacks](/202607/28/2607.23015v1-mask2shield-strengthening-llm-safety-against-neuron-pruning-attacks) （9.0/10）
   evidence：使用掩码前向对齐增强LLM安全，抵御神经元剪枝攻击
7. [Self-Boosting Vision-Language Models with Noisy Student On-Policy Self-Distillation](/202607/28/2607.23125v1-self-boosting-vision-language-models-with-noisy-student-on-policy-self-distillation) （9.0/10）
   evidence：针对视觉语言模型的在线策略自蒸馏方法
8. [Do LLMs Know Their Vulnerable Scenarios?](/202607/28/2607.23496v1-do-llms-know-their-vulnerable-scenarios) （9.0/10）
   evidence：分析大语言模型中的越狱场景并提出归因框架
9. [Bridging Reinforcement Learning and Optimal Control via Feasible Action Mapping](/202607/28/2607.23930v1-bridging-reinforcement-learning-and-optimal-control-via-feasible-action-mapping) （9.0/10）
   evidence：通过可行动作映射实现强化学习中的安全约束
10. [Explainable Reinforcement Learning via Physics-Aware Policy Distillation](/202607/28/2607.24672v1-explainable-reinforcement-learning-via-physics-aware-policy-distillation) （9.0/10）
   evidence：基于物理感知特征进行策略蒸馏以实现可解释强化学习

## 速读区
1. [H$^2$SD: Hybrid Hindsight Self-Distillation](/202607/28/2607.18955v4-h2sd-hybrid-hindsight-self-distillation) （8.0/10）
   evidence：混合事后自蒸馏用于语言模型RLVR
2. [Learning as Reasoning Unfolds: Progressive Rollout Allocation for Efficient Reinforcement Learning](/202607/28/2607.22002v1-learning-as-reasoning-unfolds-progressive-rollout-allocation-for-efficient-reinforcement-learning) （8.0/10）
   evidence：通过渐进式生成分配提高LLM推理训练效率
3. [Not All LLM Reasoning is Visible in the Chain-of-Thought](/202607/28/2607.22925v1-not-all-llm-reasoning-is-visible-in-the-chain-of-thought) （8.0/10）
   evidence：LLM推理不可见性的安全隐患
4. [Distribution-Specific Curvature Control with Finite-Sample Guarantees for Open-Weight Safety](/202607/28/2607.22929v1-distribution-specific-curvature-control-with-finite-sample-guarantees-for-open-weight-safety) （8.0/10）
   evidence：通过曲率控制防止有害微调
5. [Kalypso: Relational LLM Serving](/202607/28/2607.23815v1-kalypso-relational-llm-serving) （8.0/10）
   evidence：关系型LLM服务，通过KV缓存重用提高推理效率
6. [Constrained Reinforcement Learning Using Successor Representations](/202607/28/2607.24057v1-constrained-reinforcement-learning-using-successor-representations) （8.0/10）
   evidence：使用后继表示进行带有安全约束的强化学习
7. [KAP: Bridging the Knowledge Selection-Runtime Consumption Gap in LLM Systems](/202607/28/2607.24260v1-kap-bridging-the-knowledge-selection-runtime-consumption-gap-in-llm-systems) （8.0/10）
   evidence：通过KV缓存减少实现高效推理
8. [CHMAS: A Coupled Hierarchical Framework for Multi-Agent Reinforcement Learning](/202607/28/2607.19555v1-chmas-a-coupled-hierarchical-framework-for-multi-agent-reinforcement-learning) （7.0/10）
   evidence：耦合分层多智能体框架，集中式战略规划与分布式执行
9. [SIREN (Luring LLMs onto the Rocks): PAIR-Driven Preference Manipulation in Web-RAG Recommenders](/202607/28/2607.21951v1-siren-luring-llms-onto-the-rocks-pair-driven-preference-manipulation-in-web-rag-recommenders) （7.0/10）
   evidence：利用越狱循环对抗操纵LLM推荐
10. [Progress-conditioned Group Policy Optimization for Long-Horizon Agentic Tasks](/202607/28/2607.22724v1-progress-conditioned-group-policy-optimization-for-long-horizon-agentic-tasks) （7.0/10）
   evidence：长程智能体任务的组策略优化
11. [ConsistencyGate: Preventing Memory Contamination in LLM Agents via Self-Consistency Admission Control](/202607/28/2607.22962v1-consistencygate-preventing-memory-contamination-in-llm-agents-via-self-consistency-admission-control) （7.0/10）
   evidence：防止记忆污染以保障智能体安全
12. [Diffusion-Guided Search via Exponential Tilting (DiffTilt): An Application to Falsification of Safety-Critical Systems](/202607/28/2607.23134v1-diffusion-guided-search-via-exponential-tilting-difftilt-an-application-to-falsification-of-safety-critical-systems) （7.0/10）
   evidence：使用扩散引导搜索的安全关键系统造假检测
13. [EviBack: Search-Agent Reinforcement Learning via Evidence-Constrained Teacher Backoff](/202607/28/2607.23955v1-eviback-search-agent-reinforcement-learning-via-evidence-constrained-teacher-backoff) （6.0/10）
   evidence：强化学习中的教师回退，师生框架
14. [From Proprietary to Open-Source: Bridging the Distribution Gap via Multi-Agent Protocol Distillation in Agentic Search](/202607/28/2607.24280v1-from-proprietary-to-open-source-bridging-the-distribution-gap-via-multi-agent-protocol-distillation-in-agentic-search) （6.0/10）
   evidence：在智能搜索中用于强化学习监督的蒸馏

---
使用键盘方向键可在日报/论文之间快速切换。
