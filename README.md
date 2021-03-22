# Image evolution transformer : Building a Transformer network for evolution of cosmological images obtained from Nbody simulations

Since cosmological Nbody simulations are time consuming, our goal is to build ML models trained on simulations images that can quickly produce new images of the same type. An important task in this context is to obtain images at intermediate and future time epochs, given a set of images at various time slices.

Transformer neural networks with attention mechanisms are showing great promise in prediction problems with sequential data.
Although mostly used in NLP, they have been successful with image data as well ([Image transformer](https://arxiv.org/pdf/1802.05751.pdf)).
Here we aim to build a variant of the [spatio-temporal transformer](https://arxiv.org/abs/2004.08692) with restricted attention blocks in both spatial and temporal domains.

