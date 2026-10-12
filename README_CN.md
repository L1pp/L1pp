# YsZhang · AI 应用与 RAG

[English](README.md) | [简体中文](README_CN.md)

我重点做 AI 应用与 RAG 开发，关注资料处理、混合检索、工具化取证和可回查的报告输出，也通过受控实验研究神经网络中的几何定位与空间表征。

## 主要项目

| 项目 | 重点 | 阅读入口 |
|---|---|---|
| **[RAG Arch Demo](https://github.com/L1pp/rag-arch-demo)** | 我主导实现的建筑资料问答与方案核查链路，包含 BM25/向量检索、RRF、重排、LangGraph Agent 与来源核验。 | [运行演示](https://github.com/L1pp/rag-arch-demo/blob/main/README_CN.md) · [架构](https://github.com/L1pp/rag-arch-demo/blob/main/docs/architecture.md) · [评测](https://github.com/L1pp/rag-arch-demo/blob/main/docs/evaluation.md) |
| **[神经几何与空间表征](https://github.com/L1pp/neural-geometry-spatial-representation)** | 几何定位、卷积空间表征和支撑范围外泛化的研究归档。 | [研究概览](https://github.com/L1pp/neural-geometry-spatial-representation/blob/main/README_CN.md) · [代表性图表与结果](https://github.com/L1pp/neural-geometry-spatial-representation/tree/main/showcase) |

RAG 演示默认不需要密钥，离线脚本替身有明确说明，并保留可选在线服务入口。研究仓库是精选归档，复用脚本时需适配环境与路径。

## 技术关注

- 可追溯 AI 流程：保留资料位置、检索证据与最终引用之间的关联。
- 检索与评测：区分检索指标、答案正确率和固定参考覆盖率。
- 实现工具：Python、LangGraph、LangChain、HTTPX、NumPy、Streamlit。

求职方向以 AI 应用与 RAG 开发为主，上面的仓库是了解我工作的主要入口。

## 开源贡献

**[Parallel AI：Xiaomi MiMo 接入](https://github.com/ParkerCai/parallel-ai-extension/pull/12)**：参与增加模型提供方支持和嵌入式登录兼容，上游维护者已合并 PR #12。[我的 fork](https://github.com/L1pp/parallel-ai-extension-cn) 保留 fork 身份，原产品属于上游项目。

## 参考 fork

[Panelize](https://github.com/L1pp/Panelize) 作为 [Manho/Panelize](https://github.com/Manho/Panelize) 的参考 fork 保留，没有 fork 独有提交，不作为我的原创实现展示。
