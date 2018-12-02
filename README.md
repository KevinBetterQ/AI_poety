# TensorFlow - AI写诗
基于 TensoFlow 构建两层的 RNN 网络（LSTM模型），采用 4 万多首唐诗作为训练数据，实现可以写古诗的 AI demo

## 开发环境
- 开发语言：Python
- 框架：TensorFlow


## 代码结构
- `generate_poetry.py` - 古诗清洗、过滤较长或较短古诗、过滤即非五言也非七言古诗、为每个字生成唯一的数字ID、每首古诗用数字ID表示；
- `poetry_model.py` - 两层RNN网络模型，采用LSTM模型；
- `train_poetry.py` - 训练LSTM模型；
- `predict_poetry.py` - 生成古诗，随机取一个汉字，根据该汉字生成一首古诗。

## 使用指南
这里模型训练好了一个，可以直接运行，会随机取字生成一句古诗：
>python predict_poetry.py  

自己训练的话：
>python train_poetry.py


