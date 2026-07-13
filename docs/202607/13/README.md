# 日报 · 2026-07-13

- 生成时间：2026-07-13 21:23:38 UTC
- 当次推荐总数：23
- 精读区：9
- 速读区：14

## 今日简报（AI）
今日9篇精读、14篇速读，重点聚焦多机器人自适应团队与RLVP路径惩罚策略。最值得关注的方向：多机器人跨环境团队协作，以及RLVP基于路径惩罚与结果奖励的强化学习方法。建议下一步关注LLM与智能体记忆压缩（率失真视角）及主动记忆智能体在长周期任务中的应用。

## 精读区
1. [Multi-Robot Open Adaptive Teaming Across Unseen Environments, Partners, and Scales](/202607/13/2607.04972v1-multi-robot-open-adaptive-teaming-across-unseen-environments-partners-and-scales) （9.0/10）
   evidence：多机器人开放自适应团队与动态协调
2. [RLVP: Penalize the Path, Reward the Outcome](/202607/13/2607.07435v1-rlvp-penalize-the-path-reward-the-outcome) （9.0/10）
   evidence：提出RLVP方法，惩罚不安全路径并奖励结果，直接关注RL中的智能体安全性
3. [Beware What You Autocomplete: Forensic Attribution of Backdoored Code Completions](/202607/13/2607.08011v1-beware-what-you-autocomplete-forensic-attribution-of-backdoored-code-completions) （9.0/10）
   evidence：对带后门的代码补全进行取证归因，研究LLM的后门攻击
4. [MORES: Mobile Reasoning-as-a-Service via Distributed LLM Inference-Time Scaling](/202607/13/2607.08116v1-mores-mobile-reasoning-as-a-service-via-distributed-llm-inference-time-scaling) （9.0/10）
   evidence：提出MORES，通过分布式LLM推理时缩放提升移动端推理效率
5. [Mach-Mind-4-Flash Technical Report](/202607/13/2607.09375v1-mach-mind-4-flash-technical-report) （9.0/10）
   evidence：统一RL/OPD训练基础设施，包含动态多教师调度
6. [Agora: Enhancing LLM Agent Reasoning Via Auction-Based Task Allocation](/202607/13/2607.09600v1-agora-enhancing-llm-agent-reasoning-via-auction-based-task-allocation) （9.0/10）
   evidence：基于拍卖的任务分配用于LLM智能体集群推理
7. [MILES: Modular Instruction Memory with Learnable Selection for Self-Improving LLM Reasoning](/202607/13/2607.06974v1-miles-modular-instruction-memory-with-learnable-selection-for-self-improving-llm-reasoning) （8.0/10）
   evidence：通过模块化记忆与可学习选择实现高效推理
8. [Token-Flow Firewall: Semantic Runtime Auditing for Persistent AI Agents](/202607/13/2607.08395v1-token-flow-firewall-semantic-runtime-auditing-for-persistent-ai-agents) （8.0/10）
   evidence：持久化AI代理运行时防御
9. [Multimodal Reward Hacking in Reinforcement Learning](/202607/13/2607.09492v1-multimodal-reward-hacking-in-reinforcement-learning) （8.0/10）
   evidence：研究多模态大语言模型强化学习中的奖励破解这一安全问题

## 速读区
1. [What to Keep, What to Forget: A Rate--Distortion View of Memory Compaction in LLMs and Agents](/202607/13/2607.08032v1-what-to-keep-what-to-forget-a-rate--distortion-view-of-memory-compaction-in-llms-and-agents) （8.0/10）
   evidence：统一了LLM推理中的记忆压缩方法以提升效率
2. [Remember When It Matters: Proactive Memory Agent for Long-Horizon Agents](/202607/13/2607.08716v1-remember-when-it-matters-proactive-memory-agent-for-long-horizon-agents) （8.0/10）
   evidence：主动记忆智能体解决长视野任务中的行为状态衰退
3. [MOSAIC: Adaptive Inter-layer Composition for Efficient Heterogeneous Vision-Language Models](/202607/13/2607.09029v1-mosaic-adaptive-inter-layer-composition-for-efficient-heterogeneous-vision-language-models) （8.0/10）
   evidence：面向高效异构VLM架构的硬件感知搜索方法
4. [CoDiMAD: Diffusion-Based Privileged Distillation for Communication-Free Multi-Robot Coordination](/202607/13/2607.09587v1-codimad-diffusion-based-privileged-distillation-for-communication-free-multi-robot-coordination) （8.0/10）
   evidence：基于扩散的特权蒸馏用于多机器人协调
5. [Progress- and Reliability-Oriented Group Policy Optimization for Agentic Reinforcement Learning](/202607/13/2607.04242v1-progress--and-reliability-oriented-group-policy-optimization-for-agentic-reinforcement-learning) （7.0/10）
   evidence：面向长视野智能体任务的分组策略优化
6. [MRMS: A Multi-Resolution Memory Substrate for Long-Lived AI Agents](/202607/13/2607.04617v1-mrms-a-multi-resolution-memory-substrate-for-long-lived-ai-agents) （7.0/10）
   evidence：多分辨率记忆基板，解决长上下文智能体的连续性
7. [Turning Off-Policy Tokens On-Policy: A Plug-in Approach for Improving LLM Alignment](/202607/13/2607.04728v1-turning-off-policy-tokens-on-policy-a-plug-in-approach-for-improving-llm-alignment) （7.0/10）
   evidence：通过拒绝采样将离策略令牌转换为在策略令牌，涉及在策略RL的核心问题
8. [StateFuse: Deterministic Conflict-Preserving Memory for Multi-Agent Systems](/202607/13/2607.05844v1-statefuse-deterministic-conflict-preserving-memory-for-multi-agent-systems) （7.0/10）
   evidence：面向多智能体系统的冲突感知记忆
9. [Information Gain-based Rollout Policy Optimization: An Adaptive Tree-Structured Rollout Approach for Multi-Turn LLM Agents](/202607/13/2607.06223v1-information-gain-based-rollout-policy-optimization-an-adaptive-tree-structured-rollout-approach-for-multi-turn-llm-agents) （7.0/10）
   evidence：提出IGRPO，基于信息增益高效分配回滚预算，提高推理效率
10. [SQuaD-SQL: Efficient Text-to-SQL with Small Language Models via LLM-Guided Knowledge Distillation](/202607/13/2607.08161v1-squad-sql-efficient-text-to-sql-with-small-language-models-via-llm-guided-knowledge-distillation) （7.0/10）
   evidence：利用LLM引导的知识蒸馏提升小模型的Text-to-SQL性能，提高推理效率
11. [Reachability-Preserving Bellman Operator for the Discounted Reach-Cost Value Function: Uniting Hamilton-Jacobi Reachability and Reinforcement Learning](/202607/13/2607.07893v1-reachability-preserving-bellman-operator-for-the-discounted-reach-cost-value-function-uniting-hamilton-jacobi-reachability-and-reinforcement-learning) （6.0/10）
   evidence：将HJ可达性（安全性）与RL统一
12. [Open-ended Multi-agent Autocurricula via Visual Inspection of Policies with Multi-modal LLMs](/202607/13/2607.08193v1-open-ended-multi-agent-autocurricula-via-visual-inspection-of-policies-with-multi-modal-llms) （6.0/10）
   evidence：通过策略视觉检查实现多智能体自主课程
13. [Compete Then Collaborate: Frontier AI Teachers Build a Verifiable Curriculum to Improve a Coding Student Beyond Imitation](/202607/13/2607.08255v1-compete-then-collaborate-frontier-ai-teachers-build-a-verifiable-curriculum-to-improve-a-coding-student-beyond-imitation) （6.0/10）
   evidence：多教师知识蒸馏与可验证课程
14. [Latent Memory Palace: Reasoning for Control as Autoregressive Variational Inference](/202607/13/2607.08724v1-latent-memory-palace-reasoning-for-control-as-autoregressive-variational-inference) （6.0/10）
   evidence：控制推理作为自回归变分推理

---
使用键盘方向键可在日报/论文之间快速切换。
