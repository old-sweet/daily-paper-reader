<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-07
- 运行时间：2026-09-07 23:15:34 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：2
- 速读区：2

### 今日简报（AI）
今日4篇论文聚焦系统验证与硬件设计，精读覆盖RISC-V内核验证与进化电路合成，速读涉及程序验证及故障注入。

高分亮点：结合AI代理与并发分离逻辑验证xv6内核（RISC-V）达10分，以及通过进化合成发现非传统多精度算术电路的CircuitsDNA（8分）。

建议优先查阅《Extending Concurrent Separation Logic》了解AI赋能内核验证的最前沿思路，作为扩展可浏览速读两篇入门工具链。
- 详情：[/202609/07/README](/202609/07/README)

### 精读区论文标签
1. [Extending concurrent separation logic to the hardware level to verify the xv6 OS kernel on RISC-V with AI agents](/202609/07/2609.04043v1-extending-concurrent-separation-logic-to-the-hardware-level-to-verify-the-xv6-os-kernel-on-risc-v-with-ai-agents)  
   标签：评分：10.0/10、query:llm-hw-fv
   evidence：利用LLM智能体将并发分离逻辑验证扩展到RISC-V硬件级语义，在亚指令级验证xv6内核
2. [CircuitsDNA: Discovering Unconventional Multi-Accuracy Arithmetic Circuits via Evolutionary Synthesis](/202609/07/2609.01735v1-circuitsdna-discovering-unconventional-multi-accuracy-arithmetic-circuits-via-evolutionary-synthesis)  
   标签：评分：8.0/10、query:ml-verify
   evidence：用进化搜索结合验证miter自动生成算术电路，属于面向硬件正确性的搜索方法。

### 速读区论文标签
1. [SkillForge: Compositional Skill Synthesis with Verification-in-the-Loop for Generating Formally Verified Dafny Programs](/202609/07/2608.29841v1-skillforge-compositional-skill-synthesis-with-verification-in-the-loop-for-generating-formally-verified-dafny-programs)  
   标签：评分：7.0/10、query:llm-hw-fv
   evidence：用LLM生成经Dafny形式化验证的程序，采用验证在环技能库；可迁移到硬件形式验证
2. [GlitchLab: A Hardware-in-the-Loop Optimizer for Physical Fault Injection](/202609/07/2609.00502v1-glitchlab-a-hardware-in-the-loop-optimizer-for-physical-fault-injection)  
   标签：评分：6.0/10、query:ml-verify
   evidence：面向硬件故障注入验证的强化学习与搜索优化


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
