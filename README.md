# 从零学习大模型应用开发

## 项目结构

```
llm-learning/
├── config.example.py          # 配置文件模板（可安全 push 到 GitHub）
├── config.py                  # 你的真实配置文件（.gitignore 已忽略，不会泄露）
├── .gitignore                 # 忽略敏感文件
│
├── 01-first-api-call.py       # 第1课：第一次 API 调用
├── 02-temperature-compare.py  # 补充课：理解 Temperature
├── 03-system-prompt.py        # 第2课：System Prompt 控制人格
├── 03b-system-boundary.py     # 补充课：System Prompt 控制边界和格式
│
└── README.md
```

## 使用方式

1. 复制 `config.example.py` 为 `config.py`
2. 在 `config.py` 里填好你的 API Key（SiliconFlow 或 DeepSeek）
3. 运行对应课程文件，如：`python3 01-first-api-call.py`

## 学习路线

| 阶段 | 内容 | 状态 | 完成日期 |
|------|------|------|---------|
| 第1课 | 第一次 API 调用 | ✅ | - |
| 补充 | 理解 Temperature | ✅ | - |
| 第2课 | System Prompt 控制行为 | ✅ | - |
| 第3课 | Few-shot + Chain of Thought | ⬜ | - |
| 第4课 | 结构化输出 JSON | ⬜ | - |
| 第5课 | 文档处理与分块 | ⬜ | - |
| 第6课 | 向量嵌入与检索 | ⬜ | - |
| 第7课 | 搭建第一个 RAG 系统 | ⬜ | - |
| 第8课 | Function Calling 工具调用 | ⬜ | - |
| 第9课 | 搭建第一个 Agent | ⬜ | - |
| 第10课 | QLoRA 微调模型 | ⬜ | - |
