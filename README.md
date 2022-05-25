# TF2 Model Clones

This repo provides code to convert a selection of popular models from a PyTorch model to a Tensorflow 2 model. Since many pretrained models are released in PyTorch and not TF2, this repo aims to help bridge the gap. The TF2 models are built with Keras and have fully functional forward and backward passes. The TF2 model outputs are near exact numeric matches to their PyTorch counterparts, up to numeric differences native to each language (for example, TF2 and PyTorch square root functions produce slightly different results given the same input).

## Supported Models

The models below are currently supported. Requests for conversion of other models are welcome.

| Model | Dataset (if generator net) | Conversion File | PyTorch Source Repo |
| - | - | - | - |
| BigGAN-deep-128 | Conditional ImageNet 128x128 | save_biggan_tf2.ipynb | [link](https://github.com/huggingface/pytorch-pretrained-BigGAN) |
| BigGAN-deep-256 | Conditional ImageNet 256x256 | save_biggan_tf2.ipynb | [link](https://github.com/huggingface/pytorch-pretrained-BigGAN) |
| BigGAN-deep-512 | Conditional ImageNet 512x512 | save_biggan_tf2.ipynb | [link](https://github.com/huggingface/pytorch-pretrained-BigGAN) |
| SNGAN | Unconditional ImageNet 128x128 | save_imagenet2012_sngan_tf2.ipynb | [link](https://github.com/kwotsin/mimicry) |
| SNGAN | Celeb A 64x64 | save_celeb_a_sngan_tf2.ipynb | [link](https://github.com/kwotsin/mimicry) |
| SNGAN | CIFAR-10 32x32 | save_cifar10_sngan_tf2.ipynb | [link](https://github.com/kwotsin/mimicry) |
| CLIP | N/A | save_clip_tf2.ipynb | [link](https://github.com/openai/CLIP) |

## Contact

Please direct inquiries to Mitch Hill at ```point0bar1@gmail.com```.
