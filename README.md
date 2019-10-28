# gobang

A game with tf，keras and cuda.

运行gobang.exe进入游戏。目录下的Config.txt为参数配置文件。玩家可选为Human，MCTS AI 或 DeepMind。

与 MCTS AI 对弈无需配置环境。 而 DeepMind 则需要 Python ，Tensorflow-GPU 以及 Keras。其中Cuda版本为10.0。

# 如何训练？

确保train文件夹下有一定量数据，然后在目录下运行:
```html
python train.py
```
