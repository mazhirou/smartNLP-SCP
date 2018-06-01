# 基于自然语言处理的语义计算平台

## 开发规范

每个项目要注明所用计算引擎，如xxx-pytorch或xxx-tensorflow

## 算法说明

### 业务算法
* 内容搜索
* 内容推荐
* 自动问答
* 话题检测
* 智能对话
* 文本理解
* 语言生成
* 情感分析
* 意图理解
* 知识推理

### 基础算法
* 词法分析
  * 中文分词
  * 词性标注
  * 实体识别
* 句法分析
  * 句法结构
  * 向量表示
  * 相似度量
* 文档分析
  * 文档聚类
  * 事件挖掘
  * 文档分类
* 知识图谱
  * 实体抽取
  * 关系抽取
  * 知识融合

## 目录说明

<pre name="code" class="python">
.
├── app  ######################### 业务算法
│&nbsp;&nbsp; ├── readMe.txt
│&nbsp;&nbsp; └── chatbot
├── core ######################### 基础算法
│&nbsp;&nbsp; ├── readMe.txt
│&nbsp;&nbsp; ├── text_classifier
│&nbsp;&nbsp; └── word_vector
├── data ######################### 语料数据
│&nbsp;&nbsp; ├── readMe.txt
│&nbsp;&nbsp; └── corpus
├── docs ######################### 文档资料
│&nbsp;&nbsp; ├── readMe.txt
│&nbsp;&nbsp; └── paper
├── models ######################### 模型数据
│&nbsp;&nbsp; ├── readMe.txt
│&nbsp;&nbsp; └── ner.model
├── scripts ######################### 执行脚本
│&nbsp;&nbsp; ├── __init__.py
│&nbsp;&nbsp; ├── jieba
└── tests ######################### 测试单元
    └── readMe.txt
</pre>
<br />
