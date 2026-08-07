<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- [日报中心](/daily/README)

- 最新运行日期：2026-08-07
- 运行时间：2026-08-07 02:16:31 UTC
- 运行状态：成功
- 本次总论文数：24
- 精读区：10
- 速读区：14

### 今日简报（AI）
今日精读聚焦在线策略蒸馏，两篇满分论文均针对发散处理与校准提出新方法；速读则覆盖LLM安全表面形式敏感性、智能体记忆管理与自蒸馏奖励塑形。最值得关注的是《Not Every Divergence Should Be Suppressed》与《SPOT》，它们共同挑战了传统蒸馏中“抑制所有发散”的假设，并引入可恢复性与稀疏探针校准。建议普通读者优先浏览这两篇精读，再结合速读中的LLM安全研究，理解当前对齐与蒸馏的交叉趋势。
- 详情：[/202608/07/README](/202608/07/README)

### 精读区论文标签
1. [Not Every Divergence Should Be Suppressed: Counterfactual Recoverability in On-Policy Distillation](/202608/07/2608.04408v1-not-every-divergence-should-be-suppressed-counterfactual-recoverability-in-on-policy-distillation)  
   标签：评分：10.0/10、query:opd
   evidence：直接针对同策略蒸馏；提出反事实可恢复性来判断错误前缀是否可纠正。
2. [SPOT: Sparse Probing and Outcome Calibration for On-Policy Distillation](/202608/07/2608.04419v1-spot-sparse-probing-and-outcome-calibration-for-on-policy-distillation)  
   标签：评分：10.0/10、query:opd
   evidence：SPOT：面向在策略蒸馏的稀疏探测与结果校准
3. [Item Response Theory for AI Safety](/202608/07/2608.05086v1-item-response-theory-for-ai-safety)  
   标签：评分：10.0/10、query:ai-safety
   evidence：对多项安全基准开展项目反应理论分析
4. [Instruction-Conditioned Exploration for Reinforcement Learning with Self-Distillation to an Unconditioned Policy](/202608/07/2608.02087v2-instruction-conditioned-exploration-for-reinforcement-learning-with-self-distillation-to-an-unconditioned-policy)  
   标签：评分：9.0/10、query:opd
   evidence：强化学习中的自蒸馏与探索
5. [$S^3$: Improving Agent Safety through Multi-Stage Defense](/202608/07/2608.02683v1-s3-improving-agent-safety-through-multi-stage-defense)  
   标签：评分：9.0/10、query:ai-safety
   evidence：面向LLM智能体安全的多阶段防御
6. [Breadcrumbing Search Agents](/202608/07/2608.04565v1-breadcrumbing-search-agents)  
   标签：评分：9.0/10、query:ai-safety
   evidence：搜索智能体的提示注入与目标劫持安全风险
7. [Fewer Tokens, Smaller Cache: Reward-Coordinated Efficient Reasoning](/202608/07/2608.04771v1-fewer-tokens-smaller-cache-reward-coordinated-efficient-reasoning)  
   标签：评分：9.0/10、query:eff-reason
   evidence：直接针对高效推理，用过程奖励引导KV缓存压缩
8. [Agentic Reinforcement Learning with Observation-Calibrated Self-Distillation](/202608/07/2608.04788v1-agentic-reinforcement-learning-with-observation-calibrated-self-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：聚焦于基于同策略自蒸馏的LLM智能体强化学习，处理token级监督信号的密度问题。
9. [Agent Against Agent: An Agentic System for Automatic Prompt Injection Red Teaming](/202608/07/2608.05108v1-agent-against-agent-an-agentic-system-for-automatic-prompt-injection-red-teaming)  
   标签：评分：9.0/10、query:ai-safety
   evidence：自动提示注入红队测试系统，直接面向红队测试与智能体安全
10. [OPD-V: Visual On-Policy Self-Distillation with Modality Balance](/202608/07/2608.05131v1-opd-v-visual-on-policy-self-distillation-with-modality-balance)  
   标签：评分：9.0/10、query:opd
   evidence：面向多模态大模型的视觉on-policy自蒸馏，解决模态不平衡

### 速读区论文标签
1. [Single Canonical Prompts Underestimate LLM Safety's Surface-Form Sensitivity](/202608/07/2608.02665v1-single-canonical-prompts-underestimate-llm-safetys-surface-form-sensitivity)  
   标签：评分：8.0/10、query:ai-safety
   evidence：安全基准忠实性与表面形式敏感性
2. [Verifiable Memory: Learning Unified Memory Management with Local and Global Verifiers for Large Language Model Agents](/202608/07/2608.03137v1-verifiable-memory-learning-unified-memory-management-with-local-and-global-verifiers-for-large-language-model-agents)  
   标签：评分：8.0/10、query:l-context-rl
   evidence：面向长程交互LLM智能体的可验证记忆管理
3. [Agentic Reinforcement Learning with Self-Distilled Reward Shaping](/202608/07/2608.03223v1-agentic-reinforcement-learning-with-self-distilled-reward-shaping)  
   标签：评分：8.0/10、query:opd
   evidence：用自蒸馏奖励塑形为智能体RL提供更稠密监督
4. [TaskPress: Query-Agnostic KV Cache Compression via Task-Guided Pruning](/202608/07/2608.03276v1-taskpress-query-agnostic-kv-cache-compression-via-task-guided-pruning)  
   标签：评分：8.0/10、query:eff-reason
   evidence：KV缓存压缩，长上下文推理效率，查询无关
5. [LatentGuard: Efficient and Inspectable Latent Reasoning for LLM Safeguards](/202608/07/2608.03838v1-latentguard-efficient-and-inspectable-latent-reasoning-for-llm-safeguards)  
   标签：评分：8.0/10、query:ai-safety
   evidence：提出高效可检查的安全防护框架，用连续潜在推理支持安全审查
6. [Training-Free Hashing-Based Attention via Binary Principal Components](/202608/07/2608.04405v1-training-free-hashing-based-attention-via-binary-principal-components)  
   标签：评分：8.0/10、query:eff-reason
   evidence：长上下文注意力效率，无训练稀疏注意力
7. [Self-Improving Large Language Models via Progressive Experience Evolution](/202608/07/2608.02139v2-self-improving-large-language-models-via-progressive-experience-evolution)  
   标签：评分：7.0/10、query:opd
   evidence：通过经验蒸馏将交互轨迹内化为模型能力
8. [SkillTrace: Traversing a Query-Skill Graph for Composable LLM Agents](/202608/07/2608.02356v2-skilltrace-traversing-a-query-skill-graph-for-composable-llm-agents)  
   标签：评分：7.0/10、query:agent-swarm
   evidence：面向LLM智能体的图式技能组合方法，与智能体集群/工具调用主题相关
9. [BAP-SQL: Budget-Aware Observation Planning for Agentic Text-to-SQL](/202608/07/2608.02876v1-bap-sql-budget-aware-observation-planning-for-agentic-text-to-sql)  
   标签：评分：7.0/10、query:eff-reason
   evidence：预算感知的观测规划在智能体文本到SQL中减少token使用
10. [PI-Mem: Pushing Long-Context Reasoning to 3.6M Tokens with Parallel-Iterative Memory](/202608/07/2608.03048v1-pi-mem-pushing-long-context-reasoning-to-36m-tokens-with-parallel-iterative-memory)  
   标签：评分：7.0/10、query:eff-reason
   evidence：并行迭代记忆机制并行处理所有块并迭代精炼共享记忆，实现3.6M tokens长上下文推理
11. [D$^2$F-ReAG: Dynamic Decomposition and Filtering for Multi-Hop Reasoning-Augmented Generation](/202608/07/2608.04444v1-d2f-reag-dynamic-decomposition-and-filtering-for-multi-hop-reasoning-augmented-generation)  
   标签：评分：7.0/10、query:eff-reason
   evidence：面向多跳RAG的动态分解与过滤提升效率
12. [HPFA: Hypergraph-Based Paired Failure Attribution for LLM Reasoning](/202608/07/2608.02026v1-hpfa-hypergraph-based-paired-failure-attribution-for-llm-reasoning)  
   标签：评分：6.0/10、query:eff-reason
   evidence：基于超图的LLM推理失败根因高效定位
13. [ReflectRL: Learning from Golden Negative Trajectories via Reflective-to-Direct Reasoning](/202608/07/2608.03972v1-reflectrl-learning-from-golden-negative-trajectories-via-reflective-to-direct-reasoning)  
   标签：评分：6.0/10、query:opd
   evidence：利用专家失败轨迹进行反思式on-policy训练，属于教师-学生式框架
14. [MemoryCPT: An End-to-End Agent Memory Framework for Cost-Performance Trade-off](/202608/07/2608.04843v1-memorycpt-an-end-to-end-agent-memory-framework-for-cost-performance-trade-off)  
   标签：评分：6.0/10、query:eff-reason
   evidence：减少推理成本的智能体记忆框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
