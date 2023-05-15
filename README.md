# fruit_30app
一个部署在安卓手机端的生活中常见30种水果识别的app
哈密瓜、圣女果、山竹、杨梅、柚子、柠檬、桂圆、梨、椰子、榴莲、火龙果、猕猴桃、石榴、砂糖橘、胡萝卜、脐橙、芒果、苦瓜、苹果-红、苹果-青、草莓、荔枝、菠萝、葡萄-白、葡萄-红、西瓜、西红柿、车厘子、香蕉、黄瓜
app下载链接：https://pan.baidu.com/s/1iemJ_WIxoI0OR7SUwqcB4g?pwd=b3ce 提取码：b3ce
思路：利用pytorch中自带的在imagenet大图像数据中预训练好的resnet18模型进行迁移学习，从网上爬出30中水果的图像进行训练，得出自己的水果分类模型，转成ONNX格式，在 android studio中部署成ONNX runtime安卓手机app
相关代码下载链接：https://pan.baidu.com/s/1MCVCpWVa2KjGRIk3XpwEYA?pwd=kw7h 提取码：kw7h
相关图像下载链接：https://pan.baidu.com/s/1L50oYvDT-SwVqKdJ0yQWcg?pwd=g7i0 提取码：g7i0
