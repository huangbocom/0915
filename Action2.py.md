### 笔记：
这篇论文开始介绍了一个健壮CF schema的特点。然后介绍了Memory-Base和 Model Based的model
接着讲解了CF的算法，BaseLine的Schema, Person引用Schema.
重点介绍Slope One的Schema
还介绍了Weighted Slope One schema
然后重点介绍Bi-Polar Slope One Schema, 大体的意思是：
当权重用于评定点评的频繁程度的时候，我们应该考虑另外一种相关的评定的模式。我们仍然使用weighted slope one算法，然后导出用户喜欢的商品预测和用户不喜欢的商品预测
这就是Bi-Polar，双极的来源。

最后，有一个实验结果。

### Idea:
	我的想法是：是不是双极的Slope One只是一个不喜欢和不喜欢的维度，在现实世界，可能这个不仅仅只是两极，有可能是连续值，或者有多个离散值， 应该怎么去考虑呢。