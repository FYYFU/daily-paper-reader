# 日报 · 2026-07-07

- 生成时间：2026-07-07 21:05:44 UTC
- 当次推荐总数：31
- 精读区：17
- 速读区：14

## 今日简报（AI）
今天聚焦策略蒸馏与安全越狱两大方向，精读两篇满分论文、速读三篇高质研究。  
最值得看的是理论前沿：Reward-Gated及Multi-Turn两种在线策略蒸馏方法，以及速读中LLM越狱攻击与扩散重排序器。  
建议优先精读满分论文理解核心机制，再速读8分论文拓展应用思路。

## 精读区
1. [Reward-Gated On-Policy Distillation](/202607/07/2607.04037v1-reward-gated-on-policy-distillation) （10.0/10）
   evidence：使用验证器反馈的奖励门控在线策略蒸馏
2. [Multi-Turn On-Policy Distillation with Prefix Replay](/202607/07/2607.04763v1-multi-turn-on-policy-distillation-with-prefix-replay) （10.0/10）
   evidence：提出ReOPD用于多轮在策略蒸馏
3. [Weak-to-Strong Generalization via Direct On-Policy Distillation](/202607/07/2607.05394v1-weak-to-strong-generalization-via-direct-on-policy-distillation) （10.0/10）
   evidence：直接在线蒸馏，弱到强泛化，策略蒸馏
4. [UI-MOPD: Multi-Platform On-Policy Distillation for Continual GUI Agent Learning](/202607/07/2607.04425v1-ui-mopd-multi-platform-on-policy-distillation-for-continual-gui-agent-learning) （9.5/10）
   evidence：多平台on-policy蒸馏用于GUI智能体
5. [Message Passing Enables Efficient Reasoning](/202607/07/2607.01077v1-message-passing-enables-efficient-reasoning) （9.0/10）
   evidence：消息传递实现LLM中的高效推理
6. [Diffusion-GR2: Diffusion Generative Reasoning Re-ranker](/202607/07/2607.01170v1-diffusion-gr2-diffusion-generative-reasoning-re-ranker) （9.0/10）
   evidence：利用块扩散语言模型并行推理，加速重排序，同时保持准确性
7. [Safety Testing LLM Agents at Scale: From Risk Discovery to Evidence-Grounded Verification](/202607/07/2607.01793v2-safety-testing-llm-agents-at-scale-from-risk-discovery-to-evidence-grounded-verification) （9.0/10）
   evidence：LLM智能体安全测试，风险发现，基于证据的验证
8. [DemoPSD: Disagreement-Modulated Policy Self-Distillation](/202607/07/2607.02502v2-demopsd-disagreement-modulated-policy-self-distillation) （9.0/10）
   evidence：提出基于分歧调制的策略自蒸馏方法
9. [Not All Refusals Are Equal: How Safety Alignment Fails Cybersecurity at Scale](/202607/07/2607.02714v1-not-all-refusals-are-equal-how-safety-alignment-fails-cybersecurity-at-scale) （9.0/10）
   evidence：研究大语言模型安全对齐失败和越狱（消融）问题
10. [Oyster-II: Reinforcement Learning for Constructive Safety Alignment in Large Language Models](/202607/07/2607.02914v1-oyster-ii-reinforcement-learning-for-constructive-safety-alignment-in-large-language-models) （9.0/10）
   evidence：直接使用强化学习进行大语言模型安全对齐
11. [Incentivizing Vision Language Models to Search for Long Video Question Answering](/202607/07/2607.02959v1-incentivizing-vision-language-models-to-search-for-long-video-question-answering) （9.0/10）
   evidence：使用强化学习后训练进行长视频多轮检索问答
12. [Overloading Large Vision-Language Models for Jailbreaking](/202607/07/2607.02961v1-overloading-large-vision-language-models-for-jailbreaking) （9.0/10）
   evidence：对大型视觉语言模型的越狱攻击
13. [Swarm-Driven Multi-Agent Reasoning for Smart City Security](/202607/07/2607.03628v1-swarm-driven-multi-agent-reasoning-for-smart-city-security) （9.0/10）
   evidence：提出基于LLM的多智能体群体推理框架用于智能城市安全分析
14. [BrownoutMoE: Structure-Aware Expert Grouping for Efficient and Accurate LLM Web-based Services](/202607/07/2607.04164v1-brownoutmoe-structure-aware-expert-grouping-for-efficient-and-accurate-llm-web-based-services) （9.0/10）
   evidence：通过专家分组优化MoE大模型的推理效率
15. [Trust Region Policy Distillation](/202607/07/2607.04751v1-trust-region-policy-distillation) （9.0/10）
   evidence：在线策略蒸馏稳定化
16. [Rethinking On-Policy Self-Distillation for Thinking Models](/202607/07/2607.05184v1-rethinking-on-policy-self-distillation-for-thinking-models) （9.0/10）
   evidence：明确研究针对思维模型的在线策略自蒸馏
17. [CompactionRL: Reinforcement Learning with Context Compaction for Long-Horizon Agents](/202607/07/2607.05378v1-compactionrl-reinforcement-learning-with-context-compaction-for-long-horizon-agents) （9.0/10）
   evidence：基于上下文压缩的强化学习用于长时程智能体

## 速读区
1. [Beyond the Prompt: Jailbreaking Function-Calling LLMs via Simulated Moderation Traces](/202607/07/2607.00481v1-beyond-the-prompt-jailbreaking-function-calling-llms-via-simulated-moderation-traces) （8.0/10）
   evidence：通过模拟审查轨迹攻击函数调用LLM的越狱方法
2. [Diffusion-GR2: Diffusion Generative Reasoning Re-ranker](/202607/07/2607.01170v2-diffusion-gr2-diffusion-generative-reasoning-re-ranker) （8.0/10）
   evidence：生成式推理重排序器，推理速度，块扩散语言模型
3. [CONTRA: Red-Teaming Configurations of Personalizable Agents](/202607/07/2607.03220v1-contra-red-teaming-configurations-of-personalizable-agents) （8.0/10）
   evidence：提出LLM辅助树搜索算法用于智能体配置的红队测试
4. [Agentic-SecPBFT: Agentic AI-Driven Proactive Security Framework for Wireless PBFT Consensus in Mobile Ad-Hoc Networks](/202607/07/2607.03269v1-agentic-secpbft-agentic-ai-driven-proactive-security-framework-for-wireless-pbft-consensus-in-mobile-ad-hoc-networks) （8.0/10）
   evidence：采用多智能体深度Q网络（MADQN）学习防御策略，保护PBFT共识免受攻击
5. [CritiqueDriveVLM: From Verifier-Guided Reinforcement Learning to Latent Thought Distillation for Autonomous Driving](/202607/07/2607.04179v1-critiquedrivevlm-from-verifier-guided-reinforcement-learning-to-latent-thought-distillation-for-autonomous-driving) （8.0/10）
   evidence：自动驾驶中基于强化学习的潜在思维蒸馏
6. [Quantize the Target, Quantize the Drafter: Efficient Inference with Qwen3.5-4B](/202607/07/2607.04244v1-quantize-the-target-quantize-the-drafter-efficient-inference-with-qwen35-4b) （8.0/10）
   evidence：结合量化与推测解码实现低延迟推理
7. [Nemotron-Labs-3-Puzzle-75B-A9B: Compressing Hybrid MoE LLMs](/202607/07/2607.04371v1-nemotron-labs-3-puzzle-75b-a9b-compressing-hybrid-moe-llms) （8.0/10）
   evidence：压缩混合专家大模型用于超长上下文部署，结合强化学习与蒸馏
8. [When RAG Meets Query Planning: Logical Query Trees for Resolving Exploratory Reasoning Problems](/202607/07/2607.00508v2-when-rag-meets-query-planning-logical-query-trees-for-resolving-exploratory-reasoning-problems) （7.0/10）
   evidence：提出PlanRAG用于探究性推理，通过查询规划减少检索噪声，提高推理效率
9. [Towards Robustness against Typographic Attack with Training-free Concept Localization](/202607/07/2607.02494v1-towards-robustness-against-typographic-attack-with-training-free-concept-localization) （7.0/10）
   evidence：针对CLIP模型印刷攻击的防御机制
10. [Amortising Bayesian Experimental Design for Sequential Information Gathering in LLMs](/202607/07/2607.03426v1-amortising-bayesian-experimental-design-for-sequential-information-gathering-in-llms) （7.0/10）
   evidence：通过RL将贝叶斯实验设计摊销到LLM策略中实现高效推理
11. [ACPO: Agent-Chained Policy Optimization for Multi-Agent Reinforcement Learning](/202607/07/2606.30072v1-acpo-agent-chained-policy-optimization-for-multi-agent-reinforcement-learning) （6.0/10）
   evidence：面向多智能体强化学习的智能体链策略优化
12. [Spectral Rewiring for Exploration, Purification, and Model Merging](/202607/07/2607.03065v1-spectral-rewiring-for-exploration-purification-and-model-merging) （6.0/10）
   evidence：通过谱重连提升推理性能
13. [ACPO: Adaptive Credit Policy Optimization via Fine-Grained Surrogate Entropy](/202607/07/2607.03126v1-acpo-adaptive-credit-policy-optimization-via-fine-grained-surrogate-entropy) （6.0/10）
   evidence：提出ACPO进行token级信用分配，提升LLM的RL推理效率
14. [RSPO: Reward-Swap Policy Optimization for Multi-Turn LLM Agents](/202607/07/2607.04713v1-rspo-reward-swap-policy-optimization-for-multi-turn-llm-agents) （6.0/10）
   evidence：针对多轮LLM的RL策略优化，与长上下文RL训练相关

---
使用键盘方向键可在日报/论文之间快速切换。
