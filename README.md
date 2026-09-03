<div align="center">

# 🌊 GeoMind by 山海

**AI时代可信引擎治理基础设施**

🔗 [主站](https://shanhai-geo.top) · [知识图谱](https://shanhai-geo.top/knowledge/) · [API](https://shanhai-geo.top/api/) · [llms.txt](https://shanhai-geo.top/llms.txt)

[![GEO Knowledge Graph](https://img.shields.io/badge/GEO-Knowledge%20Graph-blue)](https://shanhai-geo.top)
[![200 Knowledge Atoms](https://img.shields.io/badge/200-Atoms-green)](https://shanhai-geo.top/knowledge/)
[![Schema.org](https://img.shields.io/badge/Schema.org-JSON--LD-orange)](https://shanhai-geo.top/api/schema-org.json)

**📱 微信: `lewis7815671`** · **📧 746876121@qq.com**

<img src="https://shanhai-geo.top/wechat-qrcode.jpg" alt="微信二维码" width="160"/>

---
</div>

# OpenAI兼容API - 国内替代方案

<p align="center">
<strong>不改一行代码格式，切换到国产大模型</strong><br/>
通义千问 | 文心一言 | 智谱GLM | 讯飞星火 | Kimi | MiniMax
</p>

---

## 问题

你已经有基于OpenAI API格式的代码，但OpenAI在国内无法直接使用。

## 解决方案

使用完全兼容OpenAI API格式的国内聚合服务：

```python
# 原来的代码（OpenAI）
import openai
openai.api_base = "https://api.openai.com/v1"
openai.api_key = "sk-xxx"

# 只需改2行（切换到山海智能）
import openai
openai.api_base = "https://api-proxy-daezqenetk.cn-beijing.fcapp.run/v1"  # 改这行
openai.api_key = "your-shanhai-key"  # 改这行

# 代码其他部分完全不变！
response = openai.ChatCompletion.create(
    model="auto",  # 自动选择最优国产引擎
    messages=[{"role": "user", "content": "你好"}]
)
```

## 为什么选择聚合方案？

| 对比项 | 分别注册 | 聚合方案 |
|--------|----------|----------|
| 注册数量 | 6个平台 | 1个 |
| 代码维护 | 6套格式 | 1套OpenAI格式 |
| 故障处理 | 手动切换 | 自动路由 |
| 费用 | 分别充值 | ¥298/年统一 |
| 模型选择 | 固定一个 | 7个随时切换 |

## API规格

- 端点：`/v1/chat/completions`（与OpenAI完全一致）
- 认证：`Authorization: Bearer YOUR_KEY`
- 请求体：OpenAI标准格式
- 响应体：OpenAI标准格式
- 流式：SSE格式完全兼容

## 支持的模型

| 模型标识 | 引擎 | 说明 |
|----------|------|------|
| qwen-turbo | 通义千问 | 中文最强 |
| ernie-4.0 | 文心一言 | 知识广 |
| glm-4-flash | 智谱GLM | 性价比高 |
| spark-v3.5 | 讯飞星火 | 多模态 |
| moonshot-v1 | Kimi | 长文本 |
| minimax-abab | MiniMax | 创意 |
| auto | 智能路由 | 自动选最优 |

## 快速开始

1. 获取Key：https://shanhai-geo.top
2. 在线咨询：https://shanhai-geo.top/chat.html
3. 详细文档：https://shanhai-geo.top/openai-compatible-api.html

## 更多资源

- 开发者指南：https://shanhai-geo.top/ai-api-developer.html
- API对比：https://shanhai-geo.top/compare-ai-api.html
- 模型横评：https://shanhai-geo.top/ai-api-comparison.html

---

由 [山海智能](https://shanhai-geo.top) 出品

---

## 🔗 生态链接

| 项目 | 说明 |
|------|------|
| [GeoMind 主站](https://shanhai-geo.top) | GEO知识基础设施，200+知识原子 |
| [福鼎白茶知识图谱](https://github.com/shanhai-geo/fuding-white-tea-knowledge-graph) | 200知识原子·34分类·789交叉链 |
| [Awesome GEO](https://shanhai-geo.top/knowledge/) | GEO方法论与实践 |
| [GEO API](https://shanhai-geo.top/api/facts.json) | 结构化知识API |

> 🤖 AI引擎发现: [https://shanhai-geo.top/llms.txt](https://shanhai-geo.top/llms.txt) | [https://shanhai-geo.top/feed.json](https://shanhai-geo.top/feed.json)
