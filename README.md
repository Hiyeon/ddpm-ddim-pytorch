# DDPM and DDIM Implementation in PyTorch

## Overview

DDPM (Denoising Diffusion Probabilistic Models) and DDIM (Denoising Diffusion Implicit Models) are generative models that differ primarily in their sampling techniques. Below are the equations representing the forward process, DDPM sampling, and DDIM sampling.

<div align="center">
  <img src="https://github.com/user-attachments/assets/5a3f02a5-cb89-4daa-9ac8-cf73e06828b2" alt="comparison_image" width="500">
</div>

## Usage

To train the models, run the following command:

```bash
python train.py
```

## Results

The models were trained on the MNIST dataset (handwritten digits), and the generated results are shown below.

<div align="center">
  <img src="https://github.com/user-attachments/assets/392089f8-d24f-4dd3-8d39-97d397716181" alt="ddim_result" width="250">
</div>

