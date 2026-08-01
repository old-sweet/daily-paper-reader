<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-01
- 运行时间：2026-08-01 21:24:28 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：8
- 速读区：9

### 今日简报（AI）
今日共处理17篇论文，精读8篇、速读9篇，聚焦硬件设计与验证自动化。最值得关注的是两项9.0分工作：Verilog设计流程的LLM基准测试，以及基于Agent的RTL验证覆盖收敛工具GoGoTB。建议普通读者从这两篇入手，了解AI在芯片前端设计与验证中的最新实用进展。
- 详情：[/202608/01/README](/202608/01/README)

### 精读区论文标签
1. [Benchmarking LLMs for Verilog Design Flows](/202608/01/2607.22759v1-benchmarking-llms-for-verilog-design-flows)  
   标签：评分：9.0/10、query:llm-hw-fv
   evidence：对LLM生成的Verilog RTL进行形式等价验证、波形分析与AST修复，是LLM进行RTL验证的核心工作。
2. [GoGoTB: Agentic RTL Verification with Specification-Grounded Coverage Closure](/202608/01/2607.26181v1-gogotb-agentic-rtl-verification-with-specification-grounded-coverage-closure)  
   标签：评分：9.0/10、query:llm-hw-fv
   evidence：使用LLMs进行智能体RTL验证，并通过规范约束的覆盖收敛保障验证完整性
3. [CircuitProver: Agentic Lean 4 Theorem Proving with Reusable Circuit Proof Library for Hardware Verification](/202608/01/2607.27259v1-circuitprover-agentic-lean-4-theorem-proving-with-reusable-circuit-proof-library-for-hardware-verification)  
   标签：评分：9.0/10、query:llm-hw-fv
   evidence：面向硬件验证的LLM智能体Lean 4定理证明
4. [CHARGE: Leveraging CWE Hierarchies for Hardware Security SystemVerilog Assertion Generation](/202608/01/2607.27776v1-charge-leveraging-cwe-hierarchies-for-hardware-security-systemverilog-assertion-generation)  
   标签：评分：9.0/10、query:llm-hw-fv
   evidence：CHARGE利用大语言模型为未验证的RTL模块生成安全断言，直接面向基于LLM的硬件形式验证。
5. [Specula: Scaling formal specifications for autonomous model checking of system code](/202608/01/2607.25333v1-specula-scaling-formal-specifications-for-autonomous-model-checking-of-system-code)  
   标签：评分：8.0/10、query:llm-hw-fv
   evidence：基于LLM的智能体自动生成TLA+规约并对系统代码进行模型检测，展示了LLM驱动形式验证的可行性
6. [Granite: A Modular Methodology for Foundational Verification of Hardware-Software Leakage Contracts](/202608/01/2607.27480v1-granite-a-modular-methodology-for-foundational-verification-of-hardware-software-leakage-contracts)  
   标签：评分：8.0/10、query:fsh
   evidence：基于ISA契约的RTL处理器模块化验证
7. [Certified Sequential Sweep Without Unrolling](/202608/01/2607.27498v1-certified-sequential-sweep-without-unrolling)  
   标签：评分：8.0/10、query:fsh
   evidence：基于IC3的时序等价性检查，使用仿真生成候选不变式
8. [LimICE: Integrating LLM into ICE Framework for Efficient Loop Invariant Inference](/202608/01/2607.27606v1-limice-integrating-llm-into-ice-framework-for-efficient-loop-invariant-inference)  
   标签：评分：8.0/10、query:llm-hw-fv
   evidence：将 LLM 集成到 ICE 框架进行循环不变量推断，是形式验证核心任务

### 速读区论文标签
1. [Kairos: Generating Tick-Indexed Proof Obligations for Synchronous Temporal Contracts](/202608/01/2607.23178v1-kairos-generating-tick-indexed-proof-obligations-for-synchronous-temporal-contracts)  
   标签：评分：7.0/10、query:fsh
   evidence：基于同步时序契约的证明义务生成，适用于数字电路形式验证
2. [Formally Verified Synthesizable Floating-Point Data Types in ARCH HDL](/202608/01/2607.23715v1-formally-verified-synthesizable-floating-point-data-types-in-arch-hdl)  
   标签：评分：7.0/10、query:llm-hw-fv
   evidence：针对面向LLM生成的硬件描述语言验证浮点数据类型
3. [DeepNC: A Fast GNN-based Pre-Verification Surrogate for TSN Configuration](/202608/01/2607.24398v1-deepnc-a-fast-gnn-based-pre-verification-surrogate-for-tsn-configuration)  
   标签：评分：7.0/10、query:ml-verify
   evidence：基于GNN的代理模型加速TSN配置的形式验证
4. [A Fresh Look at Best Inductive Loop Invariant Synthesis for Bit-Vector Relations](/202608/01/2607.26386v1-a-fresh-look-at-best-inductive-loop-invariant-synthesis-for-bit-vector-relations)  
   标签：评分：7.0/10、query:fsh
   evidence：面向位向量程序的高效归纳不变量合成方法可迁移至硬件形式验证
5. [BlueprintRepair: Typed Local Edits for Failed Lean Proof Blueprints](/202608/01/2607.28110v1-blueprintrepair-typed-local-edits-for-failed-lean-proof-blueprints)  
   标签：评分：7.0/10、query:llm-hw-fv
   evidence：基于LLM的Lean证明蓝图修复，直接涉及LLM辅助定理证明，是硬件设计验证的关键环节
6. [KaPilot: LLM-Assisted Generation of Kani Specifications for Unsafe Rust Verification](/202608/01/2607.21957v1-kapilot-llm-assisted-generation-of-kani-specifications-for-unsafe-rust-verification)  
   标签：评分：6.0/10、query:llm-hw-fv
   evidence：利用LLM自动生成Kani形式验证规范，可迁移至硬件形式验证
7. [ADVERSARIAL: And-Inverter Graph-Assisted Hardware Trojan Detection At Scale](/202608/01/2607.23882v1-adversarial-and-inverter-graph-assisted-hardware-trojan-detection-at-scale)  
   标签：评分：6.0/10、query:ml-verify
   evidence：基于AIG网表的知识图谱嵌入机器学习方法用于大规模硬件木马检测，属于机器学习在硬件验证中的应用。
8. [VeriSkill: A Self-Evolution Framework for Program Verification Skills](/202608/01/2607.27733v1-veriskill-a-self-evolution-framework-for-program-verification-skills)  
   标签：评分：6.0/10、query:llm-hw-fv
   evidence：用于程序验证的LLM智能体技能自进化框架，可迁移至硬件RTL形式验证流程
9. [Specification-Guided Synthesis of Deadlock-Free Communication Protocol Refinements with Large Language Models](/202608/01/2607.27964v1-specification-guided-synthesis-of-deadlock-free-communication-protocol-refinements-with-large-language-models)  
   标签：评分：6.0/10、query:llm-hw-fv
   evidence：利用 LLM 与形式化会话类型合成无死锁协议精化，可迁移至硬件协议验证


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
