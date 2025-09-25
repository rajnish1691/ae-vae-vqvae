# ae-vae-vqvae
PyTorch implementation of:
- Autoencoder
- Variational Autoencoder (VAE)
- Vector-Quantized Variational Autoencoder (VQ-VAE)


## Conda setup and running vq-vae

```
base$ conda create -n ae-vae-vqvae python=3.11.9
base$ conda activate ae-vae-vqvae
ae-vae-vqvae$ conda install -y pytorch torchvision cpuonly -c pytorch
ae-vae-vqvae$ pip install -q "numpy<2.0"
ae-vae-vqvae$ conda install -y scipy opencv matplotlib six
```

## Notebook

See [ae-vae-vqvae.ipynb]
https://github.com/rajnish1691/ae-vae-vqvae/blob/main/ae-vae-vqvae.ipynb