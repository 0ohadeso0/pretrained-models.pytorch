# Pretrained models

The goal of this repo is to help to reproduce research papers results.

## FB Resnet

### Resnet152

Model | Prec@1 | Prec@5
[TorchVision](https://github.com/pytorch/vision#models) | 78.312 | 94.046
[Torch7](https://github.com/facebook/fb.resnet.torch) | 77.84 | 93.84
Porting | 77.386 | 93.594

## Reproducing

```
th fbresnet/resnet152_dump.lua
python fbresnet/resnet152_load.py
```