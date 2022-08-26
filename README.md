# RecommenderSystem

### Baseline model

将用户评分定义为全局平均分 + 用户bias + 物品 bias

$$
rating = u + b_{u} + b_{i}
$$


### Latent Facotr Model（LFM） 隐语义模型 

用 FunkSVD将item-user 矩阵分解为两个矩阵P and Q的乘积
