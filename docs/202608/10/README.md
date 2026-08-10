# 日报 · 2026-08-10

- 生成时间：2026-08-10 21:14:42 UTC
- 当次推荐总数：15
- 精读区：8
- 速读区：7

## 今日简报（AI）
今日精读聚焦扩散语言模型高效蒸馏（OPTD）与推理模型自蒸馏（DASH），两篇均获9.0高分；速读另覆盖手术多模态视觉token化、搜索Agent策略与长序列并行加速。最值得关注的是“一致性引导自适应压缩”和“散度自适应监督时域”这两个优化训练策略，分别面向少步生成与推理模型。普通读者可跟进这两类蒸馏技术的后续应用，或按需浏览速读中的长上下文与多模态方向。

## 精读区
1. [OPTD: On-Policy Transition Distillation with Consistency-Guided Adaptive Compression for Few-Step Diffusion Language Models](/202608/10/2608.02942v1-optd-on-policy-transition-distillation-with-consistency-guided-adaptive-compression-for-few-step-diffusion-language-models) （9.0/10）
   evidence：面向扩散语言模型的在线策略蒸馏
2. [DASH: Divergence-Adaptive Supervision Horizons for On-Policy Self-Distillation of Reasoning Models](/202608/10/2608.06243v2-dash-divergence-adaptive-supervision-horizons-for-on-policy-self-distillation-of-reasoning-models) （9.0/10）
   evidence：在线自蒸馏与自适应监督视野
3. [Simple-OPD: Demystifying Warm-up for On-policy Distillation](/202608/10/2608.06802v1-simple-opd-demystifying-warm-up-for-on-policy-distillation) （9.0/10）
   evidence：同策略蒸馏中的预热教师-学生分析
4. [HarnessSafe: Evaluating Safety Across Persistent Carriers in Agent Harnesses](/202608/10/2608.06984v1-harnesssafe-evaluating-safety-across-persistent-carriers-in-agent-harnesses) （9.0/10）
   evidence：针对智能体持久载体安全风险的基准评估
5. [MemOPD: On-Policy Distillation through Memory State Alignment for Long-Horizon Agents](/202608/10/2608.07068v1-memopd-on-policy-distillation-through-memory-state-alignment-for-long-horizon-agents) （9.0/10）
   evidence：面向长时程智能体的在线策略蒸馏与记忆状态对齐方法
6. [Exploring and Bridging Knowledge Holes in Unlearned Multimodal Large Language Models](/202608/10/2608.01849v1-exploring-and-bridging-knowledge-holes-in-unlearned-multimodal-large-language-models) （8.0/10）
   evidence：构建基准探测未学习多模态大模型的知识空洞，与安全基准和模型安全评估相关。
7. [SynChain: Inducing Computer-Use Agent Systems to Construct Their Own Attack Chains](/202608/10/2608.06862v1-synchain-inducing-computer-use-agent-systems-to-construct-their-own-attack-chains) （8.0/10）
   evidence：计算机使用智能体的自合成攻击链
8. [Agent Memory Distillation: Empowering Small LLM Agents with Hierarchical Teacher Memory](/202608/10/2608.07169v1-agent-memory-distillation-empowering-small-llm-agents-with-hierarchical-teacher-memory) （8.0/10）
   evidence：面向小型LLM代理的师生记忆蒸馏

## 速读区
1. [Slot2Text: Object-Centric Visual Tokenization for Efficient and Spatially Traceable Surgical MLLMs](/202608/10/2608.01473v1-slot2text-object-centric-visual-tokenization-for-efficient-and-spatially-traceable-surgical-mllms) （7.0/10）
   evidence：物件中心视觉分词提升推理效率
2. [Contextual Information Policy Optimization for Search Agents](/202608/10/2608.06128v1-contextual-information-policy-optimization-for-search-agents) （7.0/10）
   evidence：面向搜索智能体的强化学习，使检索后推理基于外部证据
3. [StateFlow: Sequence Pipeline Parallelism for Long-Context Modeling with Linear Recurrence](/202608/10/2608.06838v1-stateflow-sequence-pipeline-parallelism-for-long-context-modeling-with-linear-recurrence) （7.0/10）
   evidence：长上下文训练并行系统，为长输入序列RL训练提供基础设施支撑
4. [An AI4AI Framework for Visual Token Pruning](/202608/10/2608.07193v1-an-ai4ai-framework-for-visual-token-pruning) （7.0/10）
   evidence：面向视觉token剪枝的AI4AI框架，利用LLM自动设计剪枝算法以降低多模态推理开销
5. [Trajectory-Relative Hindsight Distillation for Agentic Reinforcement Learning](/202608/10/2608.07371v1-trajectory-relative-hindsight-distillation-for-agentic-reinforcement-learning) （7.0/10）
   evidence：智能体强化学习中的轨迹相对事后蒸馏框架
6. [History Matters: Meta-policy Delegation with Heterogeneous Multi-agent Reinforcement Learning](/202608/10/2608.03833v1-history-matters-meta-policy-delegation-with-heterogeneous-multi-agent-reinforcement-learning) （6.0/10）
   evidence：基于MARL的异构智能体任务委派，与智能体集群协同执行相关
7. [The Optimizer Is the Agent: Reasoning-Driven Search across Prompts, Programs, and ML Workflows](/202608/10/2608.06714v1-the-optimizer-is-the-agent-reasoning-driven-search-across-prompts-programs-and-ml-workflows) （6.0/10）
   evidence：自主使用工具的智能体进行推理驱动的优化

---
使用键盘方向键可在日报/论文之间快速切换。
