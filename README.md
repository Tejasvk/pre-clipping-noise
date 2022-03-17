
(Under construction)

# pre-clipping-noise
 This exploration tests [funcTorch](https://pytorch.org/blog/pytorch-1.11-released/)'s efficient per-example gradient computation capabilities.

 We know that clipping gradients in DP-SGD introduces bias. 
 The following code studies the impact of adding symmetric pre-clipping noise on parameter recovery, suggested in Section 5 of [this](https://arxiv.org/pdf/2006.15429.pdf) paper
 on a toy logistic regression model.
 To isolate the effect of pre-clipping noise, we don't add DP noise.

## PyTorch and [Tensorboard](https://tensorboard.dev/) are required to run this notebook.
