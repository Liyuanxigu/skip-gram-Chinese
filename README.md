# skip-gram-Chinese
- **概要**<br>
针对中文语料数据，基于tensorflow的skip-gram算法实现,实验语料使用金庸全集（可替换）
- **代码**<br>
skipgram_chinese.py -- 源码<br>
usage_example.py -- 使用示例（需下载word2vec.txt）<br>
- **语料与模型**<br>
语料 -- 金庸全集（注意：生成通用词向量应使用其他标准语料库，可以参考https://github.com/brightmart/nlp_chinese_corpus<br>
模型 -- word2vec.txt (10万词，100维向量表示)<br>
文件较大，均提供外链下载<br>
- **效果示例**<br>

```
pd.Series(word2vec_model.most_similar(u'乔峰'))
```
*0    (鸠摩智, 0.5863361358642578)<br>
1     (萧峰, 0.5798118114471436)<br>
2    (任我行, 0.5723351836204529)<br>
3    (慕容复, 0.5638849139213562)<br>
4     (杨康, 0.5621821880340576)<br>
5    (裘千仞, 0.5401000380516052)<br>
6    (岳不群, 0.5394284725189209)<br>
7    (张翠山, 0.5377693176269531)<br>
8    (车尔库, 0.5314956903457642)<br>
9    (令狐冲, 0.5277308821678162)<br>*
- **更多详见**<br>
https://www.shushili.cn/wordpress/?p=304
