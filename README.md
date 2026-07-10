# ProofRun

> **This repository has moved.** Active development continues at **[ProofRun/LoopVera](https://github.com/ProofRun/LoopVera)**. Please use the new repository for issues, contributions, and releases.
>
> **本仓库已迁移。** 后续开发请前往 **[ProofRun/LoopVera](https://github.com/ProofRun/LoopVera)**。问题反馈、贡献与发布均在新仓库进行。

---

## English

**ProofRun Vision** brings commercial-grade runtime debugging to open-source vision pipelines. Add `observe()` to your **OpenCV / NumPy / PyTorch / OpenMMLab / custom** code to plug into a **four-pillar closed loop** — **See · Tweak & rerun · Diff across runs · Sign-off** — without replacing any operator. Library-agnostic, replayable, and free. When debug folders fill with `debug_003_v2_final.png`, the gap is tooling, not algorithms. Install via `pip install proofrun-vision`, run once, then open the local workbench in your browser.

### The closed loop

At its core is a **four-pillar closed loop**: capture every intermediate (**See**), adjust a parameter and rerun (**Tweak & rerun**), compare two runs side by side (**Diff across runs**), and sign off when stakes are high (**Sign-off**) — then the loop closes and you iterate again.

---

## 简体中文

**ProofRun Vision** 把「商业视觉软件级」的运行时调试带给开源视觉栈：在 **OpenCV / NumPy / PyTorch / OpenMMLab / 自研算子** 代码里加入 `observe()`，接入一条 **四支柱闭环** — **看清 · 改参重跑 · 跨次对比 · 签字担责** — 挂在你现有代码上，不替代任何算子。**库无关**、可回放、免费。测试集掉点、文件夹堆满 `debug_003_v2_final.png` 时，缺的多是开发工具而非算法。`pip install proofrun-vision` 安装，跑一次后在浏览器打开本地工作台即可。

### 闭环

核心是一条 **四支柱闭环**：采集中间产物（**看清**）→ 改参并重跑（**改参重跑**）→ 两版并排对比（**跨次对比**）→ 高风险场景人工签字（**签字担责**）→ 回到起点，持续迭代。

---

*Run with proof.*
