<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-09
- 运行时间：2026-07-09 21:48:26 UTC
- 运行状态：成功
- 本次总论文数：16
- 精读区：5
- 速读区：11

### 今日简报（AI）
今天共追踪 16 篇 AI 代码智能与 Agent 方向论文，重点精读了 LLM 修复循环与编译器优化补丁两条高分研究线。  
最值得关注的是《Is Three the Magic Number?》对 LLM 多轮修复效果的实证评估，以及 Agent 驱动编译器优化补丁的分析，另有 AgentTether 聚焦提升 LLM Agent 运行可靠性。  
如果你关注 AI Coding 或自动化开发，下一步可以优先跟进“多轮修复 + Agent 调试/干预”这类正在快速落地的工程实践方向。
- 详情：[/202607/09/README](/202607/09/README)

### 精读区论文标签
1. [Is Three the Magic Number? An Empirical Evaluation of LLM-Based Repair Loops](/202607/09/2607.05197v1-is-three-the-magic-number-an-empirical-evaluation-of-llm-based-repair-loops)  
   标签：评分：8.5/10、query:apr-oracle
   evidence：对使用反馈进行伪像验证的迭代修复循环进行实证评估
2. [Understanding Agent-Based Patching of Compiler Missed Optimizations](/202607/09/2607.02370v1-understanding-agent-based-patching-of-compiler-missed-optimizations)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：基于智能体的编译器优化缺失补丁修复及补丁泛化研究
3. [Understanding Agent-Based Patching of Compiler Missed Optimizations](/202607/09/2607.02370v2-understanding-agent-based-patching-of-compiler-missed-optimizations)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：基于智能体的编译器优化缺失补丁修复及补丁泛化研究
4. [What Predicts Correctness in Text-to-SQL? A Selective-Prediction Study](/202607/09/2607.06799v1-what-predicts-correctness-in-text-to-sql-a-selective-prediction-study)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：预测正确性并使用LLM裁判进行验证
5. [What Makes a Good Bug Report for an AI Agent?](/202607/09/2607.07593v1-what-makes-a-good-bug-report-for-an-ai-agent)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：自动程序修复代理与影响修复成功的错误报告特征

### 速读区论文标签
1. [AgentTether: Graph-Guided Diagnosis and Runtime Intervention for Reliable LLM Agent Operation](/202607/09/2607.06273v1-agenttether-graph-guided-diagnosis-and-runtime-intervention-for-reliable-llm-agent-operation)  
   标签：评分：7.5/10、query:apr-oracle
   evidence：针对LLM智能体轨迹的运行时修复框架
2. [Guiding Human Validation of LLM-Generated Code via Verifiable Literate Programming](/202607/09/2607.02333v1-guiding-human-validation-of-llm-generated-code-via-verifiable-literate-programming)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：LLM生成代码的人工验证与可验证编程
3. [TestEvo-Bench: An Executable and Live Benchmark for Test and Code Co-Evolution](/202607/09/2607.02469v1-testevo-bench-an-executable-and-live-benchmark-for-test-and-code-co-evolution)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：测试与代码协同演化的基准测试及针对新行为的测试生成
4. [Can Coding Agents Implement Missed Compiler Optimizations? Evaluating LLM Agents on LLVM Peephole Optimizations](/202607/09/2607.02684v1-can-coding-agents-implement-missed-compiler-optimizations-evaluating-llm-agents-on-llvm-peephole-optimizations)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：评估LLM代理修复真实编译器优化问题的能力
5. [A Systematic Methodology for Evaluating Failure Independence in LLM-Generated Code](/202607/09/2607.02808v1-a-systematic-methodology-for-evaluating-failure-independence-in-llm-generated-code)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：评估LLM生成代码的故障独立性与可靠性
6. [EvoOtter: Evolutionary Reproduction Test Generator](/202607/09/2607.02854v1-evootter-evolutionary-reproduction-test-generator)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：生成缺陷复现测试以提供补丁执行反馈
7. [Cheap Code, Costly Judgment: A Case Study on Governable Agentic Software Engineering](/202607/09/2607.01087v1-cheap-code-costly-judgment-a-case-study-on-governable-agentic-software-engineering)  
   标签：评分：6.5/10、query:apr-oracle
   evidence：用于可纠正AI辅助开发的证据和反馈循环
8. [BeSpec: Behavior-Level Specification Alignment for Code Generation](/202607/09/2607.02949v1-bespec-behavior-level-specification-alignment-for-code-generation)  
   标签：评分：6.5/10、query:apr-oracle
   evidence：行为级规范对齐，以确保生成的代码符合意图
9. [Fixed-Set Robustness in Programming by Example: Example Corruption and Semantic Partition Recovery](/202607/09/2607.01280v1-fixed-set-robustness-in-programming-by-example-example-corruption-and-semantic-partition-recovery)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：PBE中的测试预言鲁棒性和语义签名验证
10. [UA-ChatDev: Uncertainty-Aware Multi-Agent Collaboration for Reliable Software Development](/202607/09/2607.02186v1-ua-chatdev-uncertainty-aware-multi-agent-collaboration-for-reliable-software-development)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：用于可靠软件开发和细化的不确定性感知多智能体框架
11. [Characterizing and Bridging the Diagnostic Gap in eBPF Verifier Rejections](/202607/09/2607.02748v1-characterizing-and-bridging-the-diagnostic-gap-in-ebpf-verifier-rejections)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：重建证明以弥合eBPF程序修复中的诊断差距


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
