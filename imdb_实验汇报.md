# IMDB 实验

实验基于 Kaggle **Bag of Words Meets Bags of Popcorn / Word2Vec NLP Tutorial** 的 IMDB 电影评论情感分析项目。当前先进行了部分方法的实验，实验还在更新中。

## 数据集

数据来自 Kaggle 的 [Word2Vec NLP Tutorial](https://www.kaggle.com/competitions/word2vec-nlp-tutorial)。

数据文件包括：

- `labeledTrainData.tsv`：带情感标签的训练评论。
- `unlabeledTrainData.tsv`：无标签评论。
- `testData.tsv`
- `sampleSubmission.csv`：提交格式示例。



## Kaggle 提交结果

以下结果依据kaggle提交分数按分数从高到低排序。

| 排名 | 模型 | 得分 |
| ---: | --- | ---: |
| 1 | RoBERTa（Trainer） | 0.98360 |
| 2 | BERT（Trainer） | 0.97541 |
| 3 | BERT（Native） | 0.97339 |
| 4 | DistilBERT（Trainer） | 0.97099 |
| 5 | DistilBERT（Native） | 0.96989 |
| 6 | CNN | 0.96532 |
| 7 | Attention + LSTM | 0.96308 |
| 8 | GRU | 0.96128 |
| 9 | Capsule + LSTM | 0.95790 |
| 10 | Transformer | 0.95691 |
| 11 | BERT（从零训练） | 0.94703 |
| 12 | CNN + LSTM | 0.93863 |
| 13 | LSTM | 0.93578 |
| 14 | Random Forest | 0.84248 |
| 15 | 平均词向量 + Random Forest | 0.83316 |
| 16 | 聚类 + Random Forest | 0.78620 |




11.15日更新了 bert_native、bert_trainer、distilbert_native、distilbert_trainer、roberta_trainer 实验评分


实验代码见主页word2vec.ipynb



## 下一步计划：

- 使用bert_native、bert_trainer、distilbert_native、distilbert_trainer、roberta_trainer方法

