# 日报 · 2026-07-18

- 生成时间：2026-07-18 20:59:00 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日日报精读9篇、速读14篇，重点聚焦大模型技术报告与策略蒸馏方法。最值得关注《Mach-Mind-4-Flash Technical Report》和《Demystifying On-Policy Distillation》，前者为最新模型技术报告，后者深入剖析策略蒸馏中的角色与调控。建议优先精读这两篇满分论文，以掌握前沿模型架构与蒸馏机制。

## 精读区
1. [Mach-Mind-4-Flash Technical Report](/202607/18/2607.09375v1-mach-mind-4-flash-technical-report) （10.0/10）
   evidence：统一的RL/OPD训练基础设施和动态多教师调度
2. [Demystifying On-Policy Distillation: Roles, Pathologies, and Regulations](/202607/18/2607.13399v1-demystifying-on-policy-distillation-roles-pathologies-and-regulations) （10.0/10）
   evidence：系统研究在线策略蒸馏的角色、病理与调控
3. [SEED: Self-Evolving On-Policy Distillation for Agentic Reinforcement Learning](/202607/18/2607.14777v1-seed-self-evolving-on-policy-distillation-for-agentic-reinforcement-learning) （10.0/10）
   evidence：自进化在线策略蒸馏用于智能体强化学习
4. [LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget](/202607/18/2607.14952v1-longstraw-long-context-rl-beyond-2m-tokens-under-a-fixed-gpu-budget) （10.0/10）
   evidence：面向百万令牌强化学习方法，在固定GPU预算下支持长上下文RL训练
5. [ARMOR: Stabilizing On-Policy LLM RL with Off-Policy Anchor Samples](/202607/18/2607.10481v1-armor-stabilizing-on-policy-llm-rl-with-off-policy-anchor-samples) （9.0/10）
   evidence：在线策略LLM强化学习稳定化，使用离线锚样本，类似于蒸馏
6. [Non-vacuous Generalization Bounds for Reinforcement Learning with Verifiable Rewards](/202607/18/2607.14506v1-non-vacuous-generalization-bounds-for-reinforcement-learning-with-verifiable-rewards) （9.0/10）
   evidence：将on-policy蒸馏与RLVR微调结合
7. [MedFailBench: A Clinician-Built Open-Source Benchmark for Medical AI Safety Boundary Inspection](/202607/18/2607.15166v1-medfailbench-a-clinician-built-open-source-benchmark-for-medical-ai-safety-boundary-inspection) （9.0/10）
   evidence：医学AI安全基准，包含失效图谱和严重性标注
8. [When Words Are Safe But Actions Kill: Probing Physical Danger Beyond Text Safety in Hidden-State Risk Space](/202607/18/2607.15218v1-when-words-are-safe-but-actions-kill-probing-physical-danger-beyond-text-safety-in-hidden-state-risk-space) （9.0/10）
   evidence：探测LLM智能体中的物理危险，显示与文本安全的可分离性，提出PRISM探针检测物理危险
9. [To Answer or to Abstain: Mitigating Search-Agent Hallucinations via Abstention-Aware Reinforcement Learning](/202607/18/2607.10738v1-to-answer-or-to-abstain-mitigating-search-agent-hallucinations-via-abstention-aware-reinforcement-learning) （8.0/10）
   evidence：在线策略强化学习用于减轻智能体幻觉，涉及智能体安全

## 速读区
1. [Stop Thinking, Start Looking: Efficient Post-Training for Multimodal Document Question Answering via Reasoning-Free Alignment](/202607/18/2607.14682v1-stop-thinking-start-looking-efficient-post-training-for-multimodal-document-question-answering-via-reasoning-free-alignment) （8.0/10）
   evidence：提出无推理对齐方法，绕过中间推理步骤，降低推理成本
2. [DataShield: Uncovering Risky Fine-Tuning Data Across LLMs Through Consensus Subspace Alignment](/202607/18/2607.15081v1-datashield-uncovering-risky-fine-tuning-data-across-llms-through-consensus-subspace-alignment) （8.0/10）
   evidence：识别导致LLM安全退化的高风险微调数据
3. [AgentAbstain: Do LLM Agents Know When Not to Act?](/202607/18/2607.10059v1-agentabstain-do-llm-agents-know-when-not-to-act) （7.0/10）
   evidence：智能体放弃行动的框架，处理意外行动的安全风险
4. [SCOPE-RL: Optimizing Reasoning Paths Before and After Success](/202607/18/2607.11506v2-scope-rl-optimizing-reasoning-paths-before-and-after-success) （7.0/10）
   evidence：在成功前后优化推理路径，使用过程奖励提升效率
5. [TRACE: Turn-level Reward Assignment via Credit Estimation for Long-Horizon Agents](/202607/18/2607.13988v1-trace-turn-level-reward-assignment-via-credit-estimation-for-long-horizon-agents) （7.0/10）
   evidence：面向长视界智能体强化学习的信用分配
6. [Deep Interaction: An Efficient Human-AI Interaction Method for Large Reasoning Models](/202607/18/2607.14049v1-deep-interaction-an-efficient-human-ai-interaction-method-for-large-reasoning-models) （7.0/10）
   evidence：用于纠正大型推理模型中推理错误的高效人机交互方法
7. [ToolAnchor: Anchoring Counterfactual Context to Boost Agentic Tool-use Capability](/202607/18/2607.14145v1-toolanchor-anchoring-counterfactual-context-to-boost-agentic-tool-use-capability) （7.0/10）
   evidence：通过教师模型的反事实锚上下文提升智能体工具使用能力，与智能体集群相关
8. [MemoHarness: Agent Harnesses That Learn from Experience](/202607/18/2607.14159v1-memoharness-agent-harnesses-that-learn-from-experience) （7.0/10）
   evidence：在代理框架优化中使用蒸馏压缩经验为全局模式
9. [Reachability-Aware Pretraining for Efficient Target-Oriented Path Exploration in Temporal Knowledge Graph Reasoning](/202607/18/2607.14886v1-reachability-aware-pretraining-for-efficient-target-oriented-path-exploration-in-temporal-knowledge-graph-reasoning) （7.0/10）
   evidence：用于时序知识图谱推理中高效RL探索的可达性感知预训练
10. [NIFA: Nonlinear IMC enhanced FPGA for efficient ML inference](/202607/18/2607.15123v1-nifa-nonlinear-imc-enhanced-fpga-for-efficient-ml-inference) （7.0/10）
   evidence：非线性存内计算FPGA架构，用于高效机器学习推理
11. [Beyond Success Rate: Cost-Aware Evaluation of Offensive and Defensive Security Agents](/202607/18/2607.15263v1-beyond-success-rate-cost-aware-evaluation-of-offensive-and-defensive-security-agents) （7.0/10）
   evidence：安全智能体的成本感知评估，涉及智能体安全与红队测试
12. [Looped State-Space Language Models with Adaptive Exit-State Selection](/202607/18/2607.10110v1-looped-state-space-language-models-with-adaptive-exit-state-selection) （6.0/10）
   evidence：循环状态空间模型通过增加计算深度提升推理能力
13. [A Distributed Framework for Compiling and Reasoning with d-DNNF](/202607/18/2607.13642v1-a-distributed-framework-for-compiling-and-reasoning-with-d-dnnf) （6.0/10）
   evidence：分布式知识编译框架，实现高效逻辑推理
14. [RoboTTT: Context Scaling for Robot Policies](/202607/18/2607.15275v1-robottt-context-scaling-for-robot-policies) （6.0/10）
   evidence：将机器人策略的视动上下文扩展到8000时间步

---
使用键盘方向键可在日报/论文之间快速切换。
