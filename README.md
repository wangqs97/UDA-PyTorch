## UDA experiments with Cifar10

This is an experiment of Google's UDA [[paper\]](https://arxiv.org/abs/1904.12848)[[tensorflow\]](https://github.com/google-research/uda) in pytorch

### Requirements

Python>3.6

PyTorch>1.3.0

tensorboard

### Train

```shell
python main.py --schedule exp(or linear, log) --epoch 100 --tsa 1 --supnum 4000
```

### Tensorboard

```sh
tensorboard --logdir='./tb_logger'
```

### Result

Cifar10 with expTSA:

![exp_result.png](https://github.com/wangqs97/UDA-PyTorch/blob/master/readme_data/exp_result.png?raw=true)

