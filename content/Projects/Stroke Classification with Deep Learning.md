---
title: Swimming Stroke Video Classification Using a CNN
draft: false
---
As a former collegiate swimmer, I am fascinated by data-driven solutions that support athletes and enhance athletic performance. In the Fall of 2024, three of my teammates and I addressed the problem of swimming stroke classification in video data by training a convolutional neural network (CNN). We utilize video data from [SwimXYZ](https://doi.org/10.48550/arXiv.2310.04360)–a data set of synthesized videos depicting swimmers performing the four competitive strokes–and the [MC3_18](https://docs.pytorch.org/vision/main/models/generated/torchvision.models.video.mc3_18.html#mc3-18) architecture from PyTorch to develop this model. At peak performance, our model was able to correctly classify breaststroke and freestyle from video frames with a validation accuracy of 79.5%. 

![[StrokeClassificationCNN.pdf]]