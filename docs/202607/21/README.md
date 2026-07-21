# 日报 · 2026-07-21

- 生成时间：2026-07-21 21:41:50 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
1) 今日重点精读两篇满分论文，聚焦扩散语言模型的策略蒸馏与多轮推理的协同优化。  
2) 最值得关注的方向是Trace-Based和CADENCE分别提出的掩码扩散模型蒸馏框架及自适应推理差距闭合方法。  
3) 建议优先精读这两篇10分论文，速读中LOTAPO的自生成过程奖励机制对多步搜索推理有较好参考价值。

## 精读区
1. [Trace-Based On-Policy Distillation for Masked Diffusion Language Models](/202607/21/2607.16872v1-trace-based-on-policy-distillation-for-masked-diffusion-language-models) （10.0/10）
   evidence：基于轨迹的在线策略蒸馏用于扩散语言模型
2. [CADENCE: Closing the Reasoning Gap via Coverage-Adaptive On-Policy Distillation](/202607/21/2607.16955v1-cadence-closing-the-reasoning-gap-via-coverage-adaptive-on-policy-distillation) （10.0/10）
   evidence：CADENCE直接针对推理任务中的在线策略知识蒸馏
3. [Distilled Reinforcement Learning for LLM Post-training](/202607/21/2607.17247v1-distilled-reinforcement-learning-for-llm-post-training) （10.0/10）
   evidence：提出蒸馏强化学习，将教师监督融入RL目标，解决on-policy蒸馏的局限性
4. [LLM-as-a-Coach: Experiential Learning for Non-Verifiable Tasks](/202607/21/2607.18110v1-llm-as-a-coach-experiential-learning-for-non-verifiable-tasks) （10.0/10）
   evidence：教师-学生框架中的在线上下文蒸馏
5. [How Jailbreak Attacks Inform Safety Alignment: A Defender-Centric, Shapley-Based Evaluation of Jailbreak Contributions](/202607/21/2607.17152v1-how-jailbreak-attacks-inform-safety-alignment-a-defender-centric-shapley-based-evaluation-of-jailbreak-contributions) （9.0/10）
   evidence：越狱攻击安全评估
6. [Between Safe Boundaries: Exploiting Temporal Consistency for Jailbreaking Text-To-Video Generation Models](/202607/21/2607.17279v1-between-safe-boundaries-exploiting-temporal-consistency-for-jailbreaking-text-to-video-generation-models) （9.0/10）
   evidence：对文本到视频模型的越狱攻击
7. [A Dual-Hypothesis Reasoning Framework for LLM Guardrails](/202607/21/2607.17575v1-a-dual-hypothesis-reasoning-framework-for-llm-guardrails) （9.0/10）
   evidence：双假设推理用于LLM安全护栏
8. [Dynamic Defense Profiling Enables Cognitive Jailbreak of Text-to-Image Models](/202607/21/2607.17779v1-dynamic-defense-profiling-enables-cognitive-jailbreak-of-text-to-image-models) （9.0/10）
   evidence：针对文生图模型的认知越狱框架
9. [Certifiable Safe Model-Based Reinforcement Learning with Control-Affine Dynamics Approximation](/202607/21/2607.16501v1-certifiable-safe-model-based-reinforcement-learning-with-control-affine-dynamics-approximation) （8.0/10）
   evidence：可认证安全的模型强化学习方法

## 速读区
1. [LOTAPO: Leave-One-Turn Attribution for Self-Generated Process Rewards in Multi-Turn Search Reasoning](/202607/21/2607.13501v2-lotapo-leave-one-turn-attribution-for-self-generated-process-rewards-in-multi-turn-search-reasoning) （8.0/10）
   evidence：多轮搜索推理中自生成过程奖励
2. [Refusal is Not Safety! Benchmarking Latent Safety Risks of LLM-Driven Content Humorization](/202607/21/2607.15977v1-refusal-is-not-safety-benchmarking-latent-safety-risks-of-llm-driven-content-humorization) （8.0/10）
   evidence：LLM幽默化内容的安全风险基准
3. [Token-Wise Latent Streaming from Slow Reasoners to Fast Planners for Dynamic Vision Language Navigation](/202607/21/2607.16806v1-token-wise-latent-streaming-from-slow-reasoners-to-fast-planners-for-dynamic-vision-language-navigation) （8.0/10）
   evidence：通过将慢推理器隐状态流式传输到快规划器实现高效推理
4. [LenGuard-GPC: Length Guarding with Guided-Prompt Consistency for Spatial Reasoning Reinforce Learning](/202607/21/2607.17243v1-lenguard-gpc-length-guarding-with-guided-prompt-consistency-for-spatial-reasoning-reinforce-learning) （8.0/10）
   evidence：针对长视觉上下文空间推理的RL密集奖励框架
5. [Salience Induction against Multi-Hop RAG Agents: Threat and Defense](/202607/21/2607.17535v1-salience-induction-against-multi-hop-rag-agents-threat-and-defense) （8.0/10）
   evidence：在RAG智能体上发现显著性诱导这一新型攻击面
6. [Why Does Feedback-Augmented Self-Distillation Fail to Improve Retrieval-Interleaved Search Agents?](/202607/21/2607.17558v1-why-does-feedback-augmented-self-distillation-fail-to-improve-retrieval-interleaved-search-agents) （8.0/10）
   evidence：分析on-policy自蒸馏在智能体任务中的失败原因
7. [C$^2$KV: Compressed and Composable KV Cache Reuse for Efficient LLM Inference](/202607/21/2607.17715v1-c2kv-compressed-and-composable-kv-cache-reuse-for-efficient-llm-inference) （8.0/10）
   evidence：KV缓存压缩与重用实现高效LLM推理
8. [ToolAtlas: Learning Once, Reusing Everywhere with Tool-Side Memory](/202607/21/2607.11126v1-toolatlas-learning-once-reusing-everywhere-with-tool-side-memory) （7.0/10）
   evidence：ToolAtlas为LLM智能体提供工具侧记忆，支持类似集群的工具复用
9. [Extending LLM Context via Associative Recurrent Memory](/202607/21/2607.11614v1-extending-llm-context-via-associative-recurrent-memory) （7.0/10）
   evidence：ARMT实现常数量记忆缩放，提高长上下文LLM推理效率
10. [Process Reward Informed Tree Rollout for Effective Multi-Turn RL](/202607/21/2607.15610v1-process-reward-informed-tree-rollout-for-effective-multi-turn-rl) （7.0/10）
   evidence：针对长视界智能体任务的RL树搜索自适应展开
11. [When to Plan: Learning to Select Between Reactive Control and Deliberative Planning](/202607/21/2607.16421v1-when-to-plan-learning-to-select-between-reactive-control-and-deliberative-planning) （7.0/10）
   evidence：学习在快速反应策略与慢速深思规划间选择以优化推理效率
12. [Lomekwi: Resource-Bounded Tool Discovery in LLM Agents](/202607/21/2607.16961v1-lomekwi-resource-bounded-tool-discovery-in-llm-agents) （7.0/10）
   evidence：LLM agent的工具发现框架
13. [MXSens: Sensitivity-Aware Mixed-Precision Quantization for Efficient LLM Inference](/202607/21/2607.17733v1-mxsens-sensitivity-aware-mixed-precision-quantization-for-efficient-llm-inference) （6.0/10）
   evidence：通过混合精度量化实现高效LLM推理
14. [PPL-Factory: Task-Aware and Budget-Aware Data Selection from Language Modeling to Reasoning](/202607/21/2607.18199v1-ppl-factory-task-aware-and-budget-aware-data-selection-from-language-modeling-to-reasoning) （6.0/10）
   evidence：PPL-Factory选择信息性样本用于高效推理微调

---
使用键盘方向键可在日报/论文之间快速切换。
