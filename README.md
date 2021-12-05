# DeepMasker
Map a randomly generated face onto an input video with [StyleGAN3](https://github.com/NVlabs/stylegan3) and [SimSwap](https://github.com/neuralchen/SimSwap)

1. Generate images with `StyleGAN3 Face Generation.ipynb`
2. Generate deepfake with `FaceSwap.ipynb`

Highly recommended to run both notebooks on Google Colab with GPU on.

## Application
When censoring people's faces on media, blurring their faces makes you lose emotional connection. Instead, map random faces onto their faces and preserve all facial movements!

## Acknowledgements
- [Alias-Free Generative Adversarial Networks (StyleGAN3)](https://nvlabs.github.io/stylegan3/)
- [SimSwap: An Efficient Framework For High Fidelity Face Swapping](https://arxiv.org/pdf/2106.06340v1.pdf)
