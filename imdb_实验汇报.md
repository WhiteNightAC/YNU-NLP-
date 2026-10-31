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

| 排名 | 方法                       | Kaggle Score |
| ---- | -------------------------- | ------------ |
| 1    | CNN                        | **0.96532**  |
| 2    | CNN + LSTM                 | 0.93863      |
| 3    | LSTM                       | 0.93578      |
| 4    | Random Forest              | 0.84248      |
| 5    | 平均词向量 + Random Forest | 0.83316      |
| 6    | 聚类+Random Forest         | 0.78620      |



实验代码见主页word2vec.ipynb



## 下一步计划：

- 使用gru,attention_lstm,capsule_lstm,transformer,bert_scratch方法

