# Hierarchical-ConvLSTM
Hierarchical ConvLSTM has a multi-layer architecture and output of each layer is used for classification.

How to use

The Hierarchical ConvLSTM module derives from nn.Module so it can be used as any other PyTorch module.

Example usage:
Model = HConvLSTM(input_channels=1024,hidden_channels=[512,256,128],kernel_size=3,num_classes=101)
