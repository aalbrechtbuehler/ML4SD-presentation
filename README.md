# Overview

**Machine Learning Methods for Scientific Discovery — Guided Diffusion Demonstration**

This repository contains a demonstration of classifier guidance, based on the paper **“Diffusion Models Beat GANs on Image Synthesis”** by Dhariwal and Nichol (2021). The project applies guided diffusion to the MNIST dataset.

## Repository Contents

| File | Description |
|------|-------------|
| `Guided_Diffusion_CG_Demonstration.ipynb` | Main notebook demonstrating guided diffusion |
| `Diffusion Models Beat GANs on Image Synthesis.pdf` | Seminar presentation slides |
| `unet.pth` | Pre-trained UNet diffusion model |
| `classifier.pth` | Pre-trained classifier used for guidance |
| `README.md` | Project documentation |

---

## Requirements

This project uses Python and PyTorch. 

Dependencies: 
- Python 3.8+
- PyTorch
- torchvision
- numpy
- matplotlib
- jupyter

---

## Results

The notebook shows MNIST digit samples generated via guided diffusion at different guidance scale values. 

These results illustrate how classifier guidance influences the generative process.

---

References

- Ho, J., Jain, A., & Abbeel, P. (2020). Denoising diffusion probabilistic models. Advances in neural information processing systems, 33, 6840-6851.
- Dhariwal, P., & Nichol, A. (2021). Diffusion models beat gans on image synthesis. Advances in neural information processing systems, 34, 8780-8794.
- Song, J., Meng, C., & Ermon, S. (2020). Denoising diffusion implicit models. arXiv preprint arXiv:2010.02502.

Many thanks to this Kaggle Notebook:
https://www.kaggle.com/code/vikramsandu/guided-diffusion-by-openai-fromscratch/notebook#Generate

