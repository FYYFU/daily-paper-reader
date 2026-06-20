# 日报 · 2026-06-20

- 生成时间：2026-06-20 21:23:42 UTC
- 当次推荐总数：16
- 精读区：9
- 速读区：7

## 今日简报（AI）
今日精选16篇论文，聚焦LLM安全与性能优化，两篇9分高分论文分别揭示智能体护栏的DoS攻击风险与on-policy自蒸馏新方法。最值得关注：LLM agent guardrails本身可能成为DoS攻击目标，以及利用未来自身预测提升小模型性能的自蒸馏技术。建议优先精读这两篇9分论文，并留意速读中跨领域泛化RL的长期智能体训练思路。

## 精读区
1. [From Shield to Target: Denial-of-Service Attacks on LLM-Based Agent Guardrails](/202606/20/2606.14517v2-from-shield-to-target-denial-of-service-attacks-on-llm-based-agent-guardrails) （9.0/10）
   evidence：针对基于LLM的智能体守卫的拒绝服务攻击，涉及越狱攻击与防御
2. [Learning from the Self-future: On-policy Self-distillation for dLLMs](/202606/20/2606.18195v1-learning-from-the-self-future-on-policy-self-distillation-for-dllms) （9.0/10）
   evidence：针对扩散LLM的在策略自蒸馏
3. [Skill-Guided Continuation Distillation for GUI Agents](/202606/20/2606.18890v1-skill-guided-continuation-distillation-for-gui-agents) （9.0/10）
   evidence：针对GUI智能体的在策略蒸馏，处理偏离轨迹状态
4. [Beyond Safe Data: Pretraining-Stage Alignment with Regular Safety Reflection](/202606/20/2606.19168v1-beyond-safe-data-pretraining-stage-alignment-with-regular-safety-reflection) （9.0/10）
   evidence：预训练阶段安全对齐，嵌入安全反思
5. [Rethinking Reward Supervision: Rubric-Conditioned Self-Distillation](/202606/20/2606.19327v1-rethinking-reward-supervision-rubric-conditioned-self-distillation) （9.0/10）
   evidence：基于评分标准的在线自蒸馏
6. [Efficiently Representing Algorithms With Chain-of-Thought Transformers](/202606/20/2606.19697v1-efficiently-representing-algorithms-with-chain-of-thought-transformers) （9.0/10）
   evidence：使用链式思维高效表示算法
7. [LLM agent safety, multi-turn red-teaming, jailbreak benchmarks, adversarial robustness, safety-critical systems](/202606/20/2606.20408v1-llm-agent-safety-multi-turn-red-teaming-jailbreak-benchmarks-adversarial-robustness-safety-critical-systems) （9.0/10）
   evidence：多轮红队攻击，越狱基准，安全关键系统
8. [Dynamic Rollout Editing for Reducing Overthinking in RL-Trained Reasoning Models](/202606/20/2606.17890v1-dynamic-rollout-editing-for-reducing-overthinking-in-rl-trained-reasoning-models) （8.0/10）
   evidence：减少RL训练推理模型中的过度思考
9. [A Variational Framework for LLM Generator-Regulator Games](/202606/20/2606.18424v1-a-variational-framework-for-llm-generator-regulator-games) （8.0/10）
   evidence：提出调节语言生成的变分框架，涵盖安全、欺骗检测和合规等场景。

## 速读区
1. [Rethinking the Role of Efficient Attention in Hybrid Architectures](/202606/20/2606.15378v1-rethinking-the-role-of-efficient-attention-in-hybrid-architectures) （7.0/10）
   evidence：高效注意力设计影响长上下文能力涌现速度
2. [EfficientRollout: System-Aware Self-Speculative Decoding for RL Rollouts](/202606/20/2606.18967v1-efficientrollout-system-aware-self-speculative-decoding-for-rl-rollouts) （7.0/10）
   evidence：通过推测解码加速RL rollout生成效率
3. [Connect the Dots: Training LLMs for Long-Lifecycle Agents with Cross-Domain Generalization Via Reinforcement Learning](/202606/20/2606.20002v1-connect-the-dots-training-llms-for-long-lifecycle-agents-with-cross-domain-generalization-via-reinforcement-learning) （7.0/10）
   evidence：长轨迹序列的RL训练
4. [Replay What Matters: Off-Policy Replay for Efficient LLM Reinforcement Unlearning](/202606/20/2606.15333v1-replay-what-matters-off-policy-replay-for-efficient-llm-reinforcement-unlearning) （6.0/10）
   evidence：通过离策略重放进行模型安全卸载
5. [Learning Red Agent Policy from Observations for Neurosymbolic Autonomous Cyber Agents](/202606/20/2606.18223v1-learning-red-agent-policy-from-observations-for-neurosymbolic-autonomous-cyber-agents) （6.0/10）
   evidence：通过学习红队策略提升网络防御代理安全
6. [Model-Free Reinforcement Learning Control for Resilient Cyber-Physical Systems](/202606/20/2606.19069v1-model-free-reinforcement-learning-control-for-resilient-cyber-physical-systems) （6.0/10）
   evidence：网络攻击下的强化学习控制鲁棒性
7. [Beyond Entropy: Learning from Token-Level Distributional Deviations for LLM Reasoning](/202606/20/2606.19771v1-beyond-entropy-learning-from-token-level-distributional-deviations-for-llm-reasoning) （6.0/10）
   evidence：通过分布偏差进行token级信用分配，与知识蒸馏概念相关

---
使用键盘方向键可在日报/论文之间快速切换。
