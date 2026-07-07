<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-07
- 运行时间：2026-07-07 21:27:56 UTC
- 运行状态：成功
- 本次总论文数：23
- 精读区：12
- 速读区：11

### 今日简报（AI）
今日聚焦 23 篇 AI 编程与软件工程论文，重点覆盖自动修复、LLM 测试验证、安全校准与 C→Rust 自动迁移。  
最值得关注的是“多候选补丁确定性融合”与“LLM 测试 Oracle 权威来源分类”两条主线，前者直指自动修复稳定性，后者系统梳理了大模型测试可信度问题。  
建议优先跟进代码安全校准、Verified Code Generation 与 Rust 自动迁移方向，这些主题已开始从研究走向工程落地。
- 详情：[/202607/07/README](/202607/07/README)

### 精读区论文标签
1. [A Single Patch Is Not Enough: Deterministic Fusion of Repair Candidates](/202607/07/2607.01597v1-a-single-patch-is-not-enough-deterministic-fusion-of-repair-candidates)  
   标签：评分：10.0/10、query:apr-oracle
   evidence：修复候选补丁的确定性融合，用于选择和构建最终补丁
2. [LLM-Based Test Oracles: Source-of-Authority Taxonomy -- A Systematic Literature Review](/202607/07/2607.05031v1-llm-based-test-oracles-source-of-authority-taxonomy----a-systematic-literature-review)  
   标签：评分：10.0/10、query:apr-oracle
   evidence：关于基于大语言模型的测试预言及其权威来源的系统文献综述
3. [Loc2Repair: A Framework for Evaluating the Impact of File-Level Issue Localization in Repo-Level LLM Repair](/202607/07/2606.30963v1-loc2repair-a-framework-for-evaluating-the-impact-of-file-level-issue-localization-in-repo-level-llm-repair)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：评估仓库级LLM修复与补丁合成的框架
4. [Checked Program Recovery from Execution Video: A Sound Oracle for Untrusted Generators](/202607/07/2607.00635v1-checked-program-recovery-from-execution-video-a-sound-oracle-for-untrusted-generators)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：针对不可信生成器的两层验证预言机以确保正确性
5. [Knowledge-Enhanced Agentic Vulnerability Repair](/202607/07/2607.00820v1-knowledge-enhanced-agentic-vulnerability-repair)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：使用验证的程序事实和知识的代理式自动漏洞修复
6. [Delta Debugging in the Absence of Test Oracles Through Metamorphic Testing](/202607/07/2607.00929v1-delta-debugging-in-the-absence-of-test-oracles-through-metamorphic-testing)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：在缺乏测试预言的情况下通过蜕变测试进行Delta调试
7. [SWE-Doctor: Guiding Software Engineering Agents with Runtime Diagnosis from Multi-Faceted Bug Reproduction Tests](/202607/07/2607.00990v1-swe-doctor-guiding-software-engineering-agents-with-runtime-diagnosis-from-multi-faceted-bug-reproduction-tests)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：用于补丁验证和指导补丁生成的缺陷复现测试
8. [ContextSniper: AntTrail's Token-Efficient Code Memory for Repository-Level Program Repair](/202607/07/2607.01916v1-contextsniper-anttrails-token-efficient-code-memory-for-repository-level-program-repair)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：用于大语言模型代理仓库级程序修复的令牌高效代码内存
9. [ContextSniper: AntTrail's Token-Efficient Code Memory for Repository-Level Program Repair](/202607/07/2607.01916v2-contextsniper-anttrails-token-efficient-code-memory-for-repository-level-program-repair)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：针对仓库级学习型程序修复的精准证据选择
10. [Beyond Textual Repository Exploration: Dual-Modal Structural Reasoning for Agentic Issue Resolution](/202607/07/2607.01929v1-beyond-textual-repository-exploration-dual-modal-structural-reasoning-for-agentic-issue-resolution)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：用于智能体神经程序修复的双模态结构化推理
11. [Anchored Self-Play for Code Repair](/202607/07/2607.03523v1-anchored-self-play-for-code-repair)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：使用生成器-修复器自博弈强化学习的神经代码修复
12. [Latent Programming Horizons in Coding Agents](/202607/07/2607.05188v1-latent-programming-horizons-in-coding-agents)  
   标签：评分：9.0/10、query:apr-oracle
   evidence：用于解码代码是否通过测试集及引入回归的神经表示

### 速读区论文标签
1. [An Empirical Study of Security Calibration in Large Language Models for Code](/202607/07/2606.31159v1-an-empirical-study-of-security-calibration-in-large-language-models-for-code)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：衡量模型的置信度是否与其输出的真实正确性一致
2. [AdaTrans: Automated C to Rust Transformation via Error-Adaptive Repair](/202607/07/2606.31706v1-adatrans-automated-c-to-rust-transformation-via-error-adaptive-repair)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：具有多阶段验证功能等效性的自动修复框架
3. [AxDafny: Agentic Verified Code Generation in Dafny](/202607/07/2606.32007v1-axdafny-agentic-verified-code-generation-in-dafny)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：验证器引导的修复框架，迭代生成实现和不变式
4. [LLVM-Bench: Benchmarking and Advancing Large Language Models for LLVM Compiler Issue Resolution](/202607/07/2607.00700v1-llvm-bench-benchmarking-and-advancing-large-language-models-for-llvm-compiler-issue-resolution)  
   标签：评分：8.0/10、query:apr-oracle
   evidence：LLM问题解决与自动补丁应用的基准测试
5. [Test-Time Verification for Text-to-SQL via Outcome Reward Models](/202607/07/2606.30851v1-test-time-verification-for-text-to-sql-via-outcome-reward-models)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：结果奖励模型作为推理时验证的学习语义评分
6. [JETO-Bench: A Reproducible Benchmark for Execution Time Improvement Patches in Java](/202607/07/2606.31767v1-jeto-bench-a-reproducible-benchmark-for-execution-time-improvement-patches-in-java)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：执行时间改进补丁的基准测试与补丁验证
7. [Large Language Models for Multi-Lingual Equivalent Mutant Detection: An Extended Empirical Study](/202607/07/2607.00511v1-large-language-models-for-multi-lingual-equivalent-mutant-detection-an-extended-empirical-study)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：利用大语言模型进行等价变体检测，以确保软件质量并减少偏差
8. [RepoRescue: An Empirical Study of LLM Agents on Whole-Repository Compatibility Rescue](/202607/07/2607.01213v1-reporescue-an-empirical-study-of-llm-agents-on-whole-repository-compatibility-rescue)  
   标签：评分：7.0/10、query:apr-oracle
   evidence：用于整库兼容性修复和缺陷修复的LLM智能体
9. [How do Execution Features Improve Statistical Fault Localization? An Empirical Study](/202607/07/2606.30324v1-how-do-execution-features-improve-statistical-fault-localization-an-empirical-study)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：利用执行特征和随机森林进行统计故障定位
10. [MOA: A Profiling-Guided LLM Framework for Memory-Optimization Automation at Codebase Scale](/202607/07/2606.31368v1-moa-a-profiling-guided-llm-framework-for-memory-optimization-automation-at-codebase-scale)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：自动检测并修复内存效率问题的LLM驱动框架
11. [ATM: CID-Brokered Pre-Write Admission for Multi-Agent Code Co-Synthesis](/202607/07/2607.00041v1-atm-cid-brokered-pre-write-admission-for-multi-agent-code-co-synthesis)  
   标签：评分：6.0/10、query:apr-oracle
   evidence：包含验证与修复的多智能体代码合成治理基座


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
