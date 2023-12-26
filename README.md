# Privacy-Protection-using-Gen-AI
Using Gen AI to generate datasets with same statistical properties as the original dataset utilizing these synthetic datasets in training DL models thus protecting the privacy of original data. 
However, the synthetic data won't have the exact same properties (100 % same) and this can be well understood from the fact that we always get a loss value while training and testing as well and this value is not exactly 0, indicating a loss in original data's statistical properties. The aim of this project is to try and experiment with some new ways to come up with ignorable losses.

Currently the present used methods for data generation are GANs, transformers (encoder-decoder models), etcetera.
Presently, there is a ipynb file for image generation using GAN but has non-ignorable loss.
