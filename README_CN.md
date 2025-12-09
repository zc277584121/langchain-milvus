# 🦜️🔗 LangChain Milvus

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/LangChainAI.svg?style=social&label=Follow%20%40LangChain)](https://x.com/LangChainAI)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/milvusio.svg?style=social&label=Follow%20%40Milvus)](https://x.com/milvusio)

![](https://github.com/langchain-ai/langchain-milvus/blob/main/readme_img.png)

本仓库包含 LangChain 的 Milvus 集成包：

- [langchain-milvus](https://pypi.org/project/langchain-milvus/) - LangChain 与 Milvus 的强大集成，为 AI 应用提供向量搜索和检索器功能。

## 概述

LangChain Milvus 提供了 LangChain（一个用于构建大语言模型应用的框架）与 Milvus（一个专为相似性搜索和 AI 应用设计的强大向量数据库）之间的无缝集成。该集成能够为语义搜索、推荐系统和 RAG（检索增强生成）等 AI 应用提供高效的向量存储和检索功能。

## 功能特性

- **向量存储**：在 Milvus 中存储来自任何 LangChain 嵌入模型的向量
- **相似性搜索**：对向量数据执行高效的相似性搜索
- **混合搜索**：结合向量搜索和关键词搜索以获得更好的结果
- **最大边际相关性**：在搜索结果中过滤多样性
- **多向量字段**：支持单个集合中的多个向量字段
- **稀疏向量**：支持稀疏向量嵌入
- **内置函数**：支持 Milvus 内置函数（如 BM25）
- **异步支持**：完整支持异步操作和 API

## 安装

```bash
pip install -U langchain-milvus
```

## 使用指南

- [基础用法](https://milvus.io/docs/basic_usage_langchain.md)：学习如何使用 LangChain 在 Milvus 中进行基本的向量操作。

- [构建 RAG（检索增强生成）](https://milvus.io/docs/integrate_with_langchain.md)：了解如何通过结合 LangChain 和 Milvus 构建强大的 RAG 应用。

- [全文搜索](https://milvus.io/docs/full_text_search_with_langchain.md)：探索如何使用 LangChain 和 Milvus 实现全文搜索功能。

- [混合搜索](https://milvus.io/docs/milvus_hybrid_search_retriever.md)：学习如何结合向量搜索和关键词搜索以获得更准确的结果。

## 贡献

欢迎贡献！请参阅 [CONTRIBUTING.md](https://github.com/langchain-ai/langchain-milvus/blob/main/CONTRIBUTING.md) 了解相关指南。

## 许可证

本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](https://github.com/langchain-ai/langchain-milvus/blob/main/LICENSE) 文件。
