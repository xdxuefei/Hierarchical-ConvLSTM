# Hierarchical-ConvLSTM
Hierarchical ConvLSTM has a multi-layer architecture and output of each layer is used for classification.

### How to use

The Hierarchical ConvLSTM module derives from nn.Module so it can be used as any other PyTorch module.

Example usage:
```
model = HConvLSTM(input_channels=1024,
                  idden_channels=[512,256,128],
                  kernel_size=3,
                  num_classes=101)
```

### TODO (in progress...)
- Add spatial attention
- Replace the average pooling by weighted pooling with spatial attention as weights
- Add example useage on the task of video-based action recognition
- ...

### Disclaimer

This is still a work in progress and is far from being perfect: if you find any bug please don't hesitate to open an issue.
