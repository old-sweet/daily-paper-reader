<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-14
- 运行时间：2026-08-14 21:10:07 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：7
- 速读区：10

### 今日简报（AI）
今日17篇论文聚焦硬件演化与形式化规范生成，精读重点为“可执行契约细化”驱动RTL更新与GR(1)规范学习。最值得关注的是9.0分硬件演化工作，结合证明引导的RTL更新实现自动化设计；同时，LLM生成规范的能力评测（7.0分）值得参考。建议读者优先精读高分硬件论文，并尝试用GR(1)学习方法简化时序规范编写。
- 详情：[/202608/14/README](/202608/14/README)

### 精读区论文标签
1. [Spec-Driven Hardware Evolution via Executable Contract Refinement and Proof-Guided RTL Update](/202608/14/2608.12684v1-spec-driven-hardware-evolution-via-executable-contract-refinement-and-proof-guided-rtl-update)  
   标签：评分：9.0/10、query:llm-hw-fv
   evidence：基于LLM的规范驱动硬件演化，包含可执行合约精炼与证明引导RTL更新
2. [Learning GR(1) Specifications from Traces](/202608/14/2608.06546v1-learning-gr1-specifications-from-traces)  
   标签：评分：8.0/10、query:ml-verify
   evidence：基于SAT搜索从轨迹中学习GR(1)规范，用于硬件验证与综合
3. [HINT: Toward an Executable Hardware-Intent Representation Layer for LLM-Driven RTL Generation](/202608/14/2608.07625v1-hint-toward-an-executable-hardware-intent-representation-layer-for-llm-driven-rtl-generation)  
   标签：评分：8.0/10、query:llm-hw-fv
   evidence：面向LLM驱动RTL生成的可执行硬件意图层，支持预RTL检查与契约符合性验证。
4. [NetlistBench: Evaluating LLM Reliability in SPICE Netlist Recognition and Manipulation](/202608/14/2608.12197v1-netlistbench-evaluating-llm-reliability-in-spice-netlist-recognition-and-manipulation)  
   标签：评分：8.0/10、query:llm-hw-fv
   evidence：评估LLM在SPICE网表任务（含等价性判断）可靠性的基准，用于硬件设计
5. [GateTruth: Auditing the Rigor of RTL Design Benchmarks via Mutation Testing](/202608/14/2608.12635v1-gatetruth-auditing-the-rigor-of-rtl-design-benchmarks-via-mutation-testing)  
   标签：评分：8.0/10、query:llm-hw-fv
   evidence：利用变异测试审计面向LLM的RTL设计基准，直接涉及LLM的RTL验证
6. [Synchronous Observers Revisited for Runtime Verification of Lustre Using STL](/202608/14/2608.12693v1-synchronous-observers-revisited-for-runtime-verification-of-lustre-using-stl)  
   标签：评分：8.0/10、query:fsh
   evidence：将STL编译为Lustre同步观察器的运行时验证技术，适用于硬件设计中的同步数据流语言。
7. [Can Formal Specifications Be Synthesized from Tests Alone?](/202608/14/2608.13240v1-can-formal-specifications-be-synthesized-from-tests-alone)  
   标签：评分：8.0/10、query:llm-hw-fv
   evidence：用LLM从测试与执行轨迹合成形式规格，并用有界模型检验验证，对LLM辅助形式验证具有可迁移性

### 速读区论文标签
1. [Circuit-Based Program Verification: Sequential Circuits as an Intermediate Representation for Verifying C Programs](/202608/14/2608.07397v1-circuit-based-program-verification-sequential-circuits-as-an-intermediate-representation-for-verifying-c-programs)  
   标签：评分：7.0/10、query:fsh
   evidence：将C程序转换为时序电路并使用硬件模型检验器，桥接软硬件形式验证
2. [How Powerful are LLMs in Generating Formal Program Specifications?](/202608/14/2608.13077v1-how-powerful-are-llms-in-generating-formal-program-specifications)  
   标签：评分：7.0/10、query:llm-hw-fv
   evidence：LLM生成形式化程序规约，直接适用于RTL断言/属性生成
3. [Directed Neuro-Symbolic Stochastic Execution for Verification of Distributed Parallel AI Programs](/202608/14/2608.07947v1-directed-neuro-symbolic-stochastic-execution-for-verification-of-distributed-parallel-ai-programs)  
   标签：评分：6.0/10、query:fsh
   evidence：结合LLM引导的符号执行与模糊测试进行形式验证，方法可迁移至硬件验证
4. [Synthesizing Behavioural Models of CPS Using Automata Learning and Statistical Machine Learning](/202608/14/2608.08214v1-synthesizing-behavioural-models-of-cps-using-automata-learning-and-statistical-machine-learning)  
   标签：评分：6.0/10、query:ml-verify
   evidence：结合自动机学习与统计机器学习综合行为模型以支持形式验证
5. [TCS-BENCH: Benchmarking State-of-the-Art Generative AI Theoretical Computer Science Research Ability](/202608/14/2608.09538v1-tcs-bench-benchmarking-state-of-the-art-generative-ai-theoretical-computer-science-research-ability)  
   标签：评分：6.0/10、query:llm-hw-fv
   evidence：面向理论计算机科学的LLM定理证明基准，可迁移到LLM辅助硬件验证
6. [TCS-BENCH: Benchmarking State-of-the-Art Generative AI Theoretical Computer Science Research Ability](/202608/14/2608.09538v2-tcs-bench-benchmarking-state-of-the-art-generative-ai-theoretical-computer-science-research-ability)  
   标签：评分：6.0/10、query:llm-hw-fv
   evidence：面向理论计算机科学的LLM定理证明基准，可迁移到LLM辅助硬件验证
7. [A Pragmatic Guide to Building Conservative Discrete Abstractions of Cyber-Physical Systems](/202608/14/2608.10254v1-a-pragmatic-guide-to-building-conservative-discrete-abstractions-of-cyber-physical-systems)  
   标签：评分：6.0/10、query:fsh
   evidence：面向符号模型检测的保守离散抽象，可迁移至硬件验证
8. [SynAct: A Reasoning-Acting Large Language Model Agent for Adaptive Synthesis Optimization](/202608/14/2608.12751v1-synact-a-reasoning-acting-large-language-model-agent-for-adaptive-synthesis-optimization)  
   标签：评分：6.0/10、query:ml-verify
   evidence：自适应综合优化的LLM智能体，展示了AI引导的EDA工具命令选择，可借鉴到验证工具的智能选择与改进
9. [PROVE-RT: Generating Mechanized Theorem Prover Scripts for Real-Time Systems using LLMs](/202608/14/2608.12762v1-prove-rt-generating-mechanized-theorem-prover-scripts-for-real-time-systems-using-llms)  
   标签：评分：6.0/10、query:llm-hw-fv
   evidence：使用大语言模型辅助生成机械化定理证明脚本，可迁移至硬件定理证明
10. [Computing Fixed Points using Dependency Oracles](/202608/14/2608.13020v1-computing-fixed-points-using-dependency-oracles)  
   标签：评分：6.0/10、query:fsh
   evidence：面向验证的不动点算法，可迁移至硬件抽象解释


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
