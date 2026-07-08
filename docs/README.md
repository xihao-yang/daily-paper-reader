<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-08
- 运行时间：2026-07-08 20:53:56 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日共追踪 17 篇 LLM 编程与测试方向论文，重点精读了“提示优化提升代码生成”和“先写代码还是先测试”的工程实践问题。  
最值得关注的是：自然语言 Prompt 优化已能显著改善代码生成效果，而多篇工作开始把测试、代码审查与形式化规范纳入 LLM 开发闭环。  
建议优先关注“代码生成 + 自动测试/Review”协同流程，这类方法最可能在真实开发环境里率先落地。
- 详情：[/202607/08/README](/202607/08/README)

### 精读区论文标签
1. [From Failing to Passing: Evolving Natural Language Prompt Optimization Rules for LLM Code Generation](/202607/08/2607.05121v1-from-failing-to-passing-evolving-natural-language-prompt-optimization-rules-for-llm-code-generation)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：结合提示优化与执行反馈修复的分阶段修复流水线
2. [On the risk of coding before testing: An empirical study on LLM-based test generation workflow](/202607/08/2607.05139v1-on-the-risk-of-coding-before-testing-an-empirical-study-on-llm-based-test-generation-workflow)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：研究LLM生成的测试作为独立可靠测试预言的有效性
3. [Loc2Repair: A Framework for Evaluating the Impact of File-Level Issue Localization in Repo-Level LLM Repair](/202607/08/2606.30963v1-loc2repair-a-framework-for-evaluating-the-impact-of-file-level-issue-localization-in-repo-level-llm-repair)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：评估仓库级LLM修复和补丁合成失败模式的框架
4. [Benchmarking Code Improvement with Progressive, Adaptive, and Interactive Feedback](/202607/08/2607.01360v1-benchmarking-code-improvement-with-progressive-adaptive-and-interactive-feedback)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：超越二元正确性，利用反馈引导的细化来评估程序修复和代码改进。
5. [ContextSniper: AntTrail's Token-Efficient Code Memory for Repository-Level Program Repair](/202607/08/2607.01916v2-contextsniper-anttrails-token-efficient-code-memory-for-repository-level-program-repair)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：使用大语言模型智能体和上下文选择进行仓库级程序修复
6. [Diagnosis-Driven Automatic Repair for Agentic Workflow via Symbolic Inference](/202607/08/2607.02882v1-diagnosis-driven-automatic-repair-for-agentic-workflow-via-symbolic-inference)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：通过符号推理对智能体工作流进行诊断驱动的自动修复

### 速读区论文标签
1. [Kaizen: Metamorphic Fuzzing and Differential Testing for LLM-Translated HPC Applications](/202607/08/2607.04058v1-kaizen-metamorphic-fuzzing-and-differential-testing-for-llm-translated-hpc-applications)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：通过蜕变模糊测试和差异测试确保行为正确性
2. [Teaching Code LLMs to Reason with Intermediate Formal Specifications](/202607/08/2607.04232v1-teaching-code-llms-to-reason-with-intermediate-formal-specifications)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：可执行形式化规范作为修复代码的机器可检查约束
3. [SWE-Review: Closing the Loop on Issue Resolution with Agentic Code Review](/202607/08/2607.06065v1-swe-review-closing-the-loop-on-issue-resolution-with-agentic-code-review)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：智能体代码审查以决定PR接受并提供修订反馈
4. [LogicHunter: Testing LLM Agent Frameworks with an Agentic Oracle](/202607/08/2607.06195v1-logichunter-testing-llm-agent-frameworks-with-an-agentic-oracle)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：用于测试LLM框架以解决预言机歧义的代理预言机
5. [Safe and Adaptive Cloud Healing: Verifying LLM-Generated Recovery Plans with a Neural-Symbolic World Model](/202607/08/2607.01595v1-safe-and-adaptive-cloud-healing-verifying-llm-generated-recovery-plans-with-a-neural-symbolic-world-model)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：用于故障自愈和恢复的神经符号程序合成
6. [Refploit: Facilitating Exploit Construction via Code-Agent Trajectory Repair](/202607/08/2607.01760v1-refploit-facilitating-exploit-construction-via-code-agent-trajectory-repair)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：检测看似成功但未触发漏洞逻辑的补丁
7. [Mastermind: Strategy-grounded Learning for Repository-Scale Vulnerability Reproduction](/202607/08/2607.01764v1-mastermind-strategy-grounded-learning-for-repository-scale-vulnerability-reproduction)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：验证补丁构建后崩溃是否消失
8. [Prompt Coverage Adequacy](/202607/08/2607.02057v1-prompt-coverage-adequacy)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：针对提示词生成代码的测试充分性准则
9. [Are Performance-Optimization Benchmarks Reliably Measuring Coding Agents?](/202607/08/2607.01211v1-are-performance-optimization-benchmarks-reliably-measuring-coding-agents)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：通过应用补丁并比较运行时间来评估编码智能体
10. [Repair the Amplifier, Not the Symptom: Stable World-Model Correction for Agent Rollouts](/202607/08/2607.01767v2-repair-the-amplifier-not-the-symptom-stable-world-model-correction-for-agent-rollouts)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：用于修复代理部署中失败规划图的世界模型校正
11. [Regression Accumulation in Multi-Turn LLM Programming Conversations](/202607/08/2607.01855v1-regression-accumulation-in-multi-turn-llm-programming-conversations)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：多轮大模型编程中的回归累积与测试充分性


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
