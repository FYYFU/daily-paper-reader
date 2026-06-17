# 日报 · 2026-06-17

- 生成时间：2026-06-17 22:21:01 UTC
- 当次推荐总数：27
- 精读区：13
- 速读区：14

## 今日简报（AI）
今日共27篇论文，精读13篇，满分聚焦于LLM智能体防护墙的DoS攻击原理与多轮智能体的课程级策略蒸馏。最值得关注两大方向：一是从防护到攻击的视角转换，揭示LLM Agent安全漏洞；二是通过策略蒸馏提升多轮交互的协同效率。建议普通读者优先阅读这两篇10分论文，理解前沿攻防场景与优化架构，并留意本文的风险评估与高效推理方法。

## 精读区
1. [From Shield to Target: Denial-of-Service Attacks on LLM-Based Agent Guardrails](/202606/17/2606.14517v2-from-shield-to-target-denial-of-service-attacks-on-llm-based-agent-guardrails) （10.0/10）
   evidence：对基于LLM的智能体护栏的拒绝服务攻击，涉及越狱防御
2. [On-Policy Distillation with Curriculum Turn-level Guidance for Multi-turn Agents](/202606/17/2606.15912v1-on-policy-distillation-with-curriculum-turn-level-guidance-for-multi-turn-agents) （10.0/10）
   evidence：多轮智能体上的策略蒸馏方法
3. [OmniOPSD: Rationale-Privileged On-Policy Self-Distillation for Affective Computing](/202606/17/2606.15920v1-omniopsd-rationale-privileged-on-policy-self-distillation-for-affective-computing) （10.0/10）
   evidence：多模态大语言模型上的在线策略自蒸馏
4. [Learning from the Self-future: On-policy Self-distillation for dLLMs](/202606/17/2606.18195v1-learning-from-the-self-future-on-policy-self-distillation-for-dllms) （10.0/10）
   evidence：面向扩散LLM的在线自蒸馏
5. [Dense Supervision, Sparse Updates: On the Sparsity and Geometry of On-Policy Distillation](/202606/17/2606.13657v2-dense-supervision-sparse-updates-on-the-sparsity-and-geometry-of-on-policy-distillation) （9.0/10）
   evidence：分析了在策略蒸馏的稀疏性与几何结构
6. [OSGuard: A Benchmark for Safety in Computer-Use Agents](/202606/17/2606.15034v1-osguard-a-benchmark-for-safety-in-computer-use-agents) （9.0/10）
   evidence：计算机使用智能体的安全基准
7. [SPARK: Spatial Policy-driven Adaptive Reinforcement learning for Knowledge distillation](/202606/17/2606.15243v1-spark-spatial-policy-driven-adaptive-reinforcement-learning-for-knowledge-distillation) （9.0/10）
   evidence：基于强化学习的自适应知识蒸馏，使用策略网络
8. [ReQAT: Achieving Full-Precision Reasoning Accuracy with 4-bit Floating-Point Quantization-Aware Training](/202606/17/2606.15682v1-reqat-achieving-full-precision-reasoning-accuracy-with-4-bit-floating-point-quantization-aware-training) （9.0/10）
   evidence：4位量化提升推理效率
9. [GAS-Leak-LLM: Genetic Algorithm-Based Suffix Optimization for Black-Box LLM Jailbreaking](/202606/17/2606.15788v1-gas-leak-llm-genetic-algorithm-based-suffix-optimization-for-black-box-llm-jailbreaking) （9.0/10）
   evidence：基于遗传算法的黑盒LLM越狱攻击
10. [Adaptive and Explicit safe: Triggering Latent Safety Awareness in Large Reasoning Models](/202606/17/2606.16808v1-adaptive-and-explicit-safe-triggering-latent-safety-awareness-in-large-reasoning-models) （9.0/10）
   evidence：触发大型推理模型的潜在安全意识以防御越狱攻击
11. [OPD-Evolver: Cultivating Holistic Agent Evolver via On-Policy Distillation](/202606/17/2606.17628v1-opd-evolver-cultivating-holistic-agent-evolver-via-on-policy-distillation) （9.0/10）
   evidence：基于同策略自蒸馏的智能体进化框架
12. [SuCo: Sufficiency-guided Continuous Adaptive Reasoning](/202606/17/2606.17687v1-suco-sufficiency-guided-continuous-adaptive-reasoning) （9.0/10）
   evidence：提出最小充分CoT和连续自适应推理，减少推理token，提升效率
13. [Zone of Proximal Policy Optimization: Teacher in Prompts, Not Gradients](/202606/17/2606.18216v1-zone-of-proximal-policy-optimization-teacher-in-prompts-not-gradients) （9.0/10）
   evidence：修改on-policy策略梯度的师生RL框架

## 速读区
1. [QPILOTS: Efficient Test-Time Q-Steering for Flow Policies](/202606/17/2606.14801v1-qpilots-efficient-test-time-q-steering-for-flow-policies) （8.0/10）
   evidence：提出测试时Q引导作为策略蒸馏的替代，直接讨论RL中的蒸馏技术
2. [Risk-Aware LLM Agents for Geospatial Data Retrieval: Design and Preliminary Adversarial Evaluation](/202606/17/2606.15077v1-risk-aware-llm-agents-for-geospatial-data-retrieval-design-and-preliminary-adversarial-evaluation) （8.0/10）
   evidence：包含Guardrail安全智能体和对抗评估的LLM框架
3. [DLWM: Diverse Latent World Models for Efficient Multimodal Reasoning](/202606/17/2606.15160v1-dlwm-diverse-latent-world-models-for-efficient-multimodal-reasoning) （8.0/10）
   evidence：提出多样潜在世界模型以实现高效多模态推理
4. [Defending against Adaptive Prompt Injection Attacks via Reasoning-enabled Task Alignment](/202606/17/2606.15441v1-defending-against-adaptive-prompt-injection-attacks-via-reasoning-enabled-task-alignment) （8.0/10）
   evidence：通过推理防御自适应提示注入攻击
5. [ToolMenuBench: Benchmarking Tool-Menu Filtering Strategies for Reliable and Efficient LLM Agents](/202606/17/2606.15508v1-toolmenubench-benchmarking-tool-menu-filtering-strategies-for-reliable-and-efficient-llm-agents) （8.0/10）
   evidence：提出了工具菜单过滤的安全基准
6. [Prefill/Decode-Aware Evaluation of LLM Inference on Emerging AI Accelerators](/202606/17/2606.17104v1-prefilldecode-aware-evaluation-of-llm-inference-on-emerging-ai-accelerators) （8.0/10）
   evidence：面向加速器的LLM推理效率分阶段评估
7. [Shattering the Autoregressive Curse: Dynamic Epistemic Entropy Orchestrated Erasable Reinforcement Learning for LLMs](/202606/17/2606.17735v1-shattering-the-autoregressive-curse-dynamic-epistemic-entropy-orchestrated-erasable-reinforcement-learning-for-llms) （8.0/10）
   evidence：面向LLM长程推理的强化学习
8. [Learning to Reason by Analogy via Retrieval-Augmented Reinforcement Fine-Tuning](/202606/17/2606.13680v1-learning-to-reason-by-analogy-via-retrieval-augmented-reinforcement-fine-tuning) （7.0/10）
   evidence：使用黄金相关性蒸馏训练检索器并通过RL微调策略模型
9. [Trust-Region Diffusion Policies for Massively Parallel On-Policy RL](/202606/17/2606.15260v1-trust-region-diffusion-policies-for-massively-parallel-on-policy-rl) （7.0/10）
   evidence：大规模并行on-policy RL中的扩散策略
10. [Securing Multi-Agent GIS Systems: Risk Evaluation and Prompt Hardening Optimization](/202606/17/2606.17092v1-securing-multi-agent-gis-systems-risk-evaluation-and-prompt-hardening-optimization) （7.0/10）
   evidence：多智能体GIS系统中的红队测试框架
11. [Beyond Uniform Token-Level Trust Region in LLM Reinforcement Learning](/202606/17/2606.10968v1-beyond-uniform-token-level-trust-region-in-llm-reinforcement-learning) （6.0/10）
   evidence：LLM强化学习中的非均匀信任区域
12. [Beyond Uniform Token-Level Trust Region in LLM Reinforcement Learning](/202606/17/2606.10968v2-beyond-uniform-token-level-trust-region-in-llm-reinforcement-learning) （6.0/10）
   evidence：LLM强化学习中的非均匀信任区域
13. [Graph-based Target Back-Propagation for Context Adaptation in Multi-LLM Agentic Systems](/202606/17/2606.14155v1-graph-based-target-back-propagation-for-context-adaptation-in-multi-llm-agentic-systems) （6.0/10）
   evidence：多LLM智能体上下文适应框架
14. [Elastic Queries Reinforcement Learning: Self-Aware Policy Execution for VLA Models](/202606/17/2606.14375v1-elastic-queries-reinforcement-learning-self-aware-policy-execution-for-vla-models) （6.0/10）
   evidence：弹性查询RL实现高效VLA推理

---
使用键盘方向键可在日报/论文之间快速切换。
