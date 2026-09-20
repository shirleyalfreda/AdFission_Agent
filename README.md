# AdFission_Agent
AdFission Agent — An AIGC advertising creative fission engine. Turns one source asset into a testable matrix of strategy-tagged variants via multimodal deconstruction, LLM/SD dual-engine generation, and a QA decision loop. Two feedback loops (auto-rework + performance data) power a data flywheel that makes creatives smarter with every run.
# AdFission Agent · 广告素材裂变引擎

> 输入一条原始素材，自动产出 N 个面向不同人群、渠道与卖点的可投放变体。
> 把「1 条素材」变成「一个可测试的创意矩阵」，让投放从「等素材」变为「选素材」。

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-Beta%20v0.9.0-7c5cff?style=flat-square" />
  <img alt="type" src="https://img.shields.io/badge/type-AIGC%20%C2%B7%20AdTech-22d3ee?style=flat-square" />
  <img alt="demo" src="https://img.shields.io/badge/demo-pure%20frontend-f472b6?style=flat-square" />
  <img alt="license" src="https://img.shields.io/badge/license-MIT-34d399?style=flat-square" />
</p>

---

## 📌 这是什么

**AdFission Agent** 是一款面向投放团队与代理商创意团队的 AIGC 素材生产工具方向提案。

它解决的是一线投放里最真实的一个瓶颈：**广告素材有生命周期，必须持续供给新版本做 A/B 测试，而创意多版本化长期依赖设计人力。**

- **平台自营场景**：优化师直接筛选、勾选、投放，追求测试速度与策略沉淀；
- **代理商代运营场景**：同时服务多品牌客户，素材需按客户项目独立交付，还要满足客户品牌基线约束与多客户数据隔离。

> 短期看，它是一个素材生成器；长期看，它是**与投放环境共同进化的增长引擎**。

---

## 🎬 快速开始

本仓库的 Demo 是**纯前端实现**（无构建、无依赖、无后端），克隆后直接打开即可运行。

```bash
git clone https://github.com/<your-name>/adfission-agent.git
cd adfission-agent
