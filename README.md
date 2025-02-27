# Extraction-of-Conversational-Elements-from-Group-Chats-using-Large-Language-Models
基于大语言模型的群聊要素提取
# 群聊对话要素提取项目

## 概述
本项目旨在利用大型语言模型对群聊对话进行深度分析，提取关键要素，以便于进一步的数据处理和分析。

## 使用的大型语言模型
本项目采用了以下三种大语言模型来实现对话要素的提取：

1. **星火 (Spark)**
   - 一款高性能的语言模型，擅长于理解和生成自然语言文本。

2. **Kimi**
   - Moonshot AI 开发的先进语言模型，以其卓越的对话理解和生成能力而闻名。

3. **GPT4 (Generative Pre-trained Transformer)**
   - 由OpenAI开发的革命性模型，以其强大的文本生成和理解能力著称。

## 流程简介

### 步骤 1: 数据收集
- 收集群聊数据，包括聊天记录、用户信息、时间戳等。

### 步骤 2: 数据预处理
- 清洗数据，去除无用信息。
- 分词和标准化文本数据。

### 步骤 3: 特征提取
- 使用上述大型语言模型提取对话中的关键特征，如关键词、情感倾向、话题等。

### 步骤 4: 对话结构分析
- 识别对话中的结构，如提问、回答、陈述等。

### 步骤 5: 话题建模
- 使用LDA等话题模型识别群聊中的主要话题。

### 步骤 6: 实体和关系提取
- 识别对话中的实体和实体间的关系。

### 步骤 7: 对话管理
- 分析对话流程，识别对话的开始、结束和转折点。

### 步骤 8: 结果应用
- 将提取的要素用于聊天机器人、客户服务、市场分析等应用。

## 美观的流程图
以下是本项目的流程图，展示了从数据收集到结果应用的全过程：

```mermaid
graph LR
    A[数据收集] -->|清洗和预处理| B[数据预处理]
    B --> C[特征提取]
    C --> D[对话结构分析]
    D --> E[话题建模]
    E --> F[实体和关系提取]
    F --> G[对话管理]
    G --> H[结果应用]
nice
