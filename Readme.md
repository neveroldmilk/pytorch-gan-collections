# Collections of GANs

Pytorch implementation of GANs

## Models
- [ ] GAN
- [x] DCGAN
- [ ] WGAN
- [x] WGAN-GP
- [x] SN-GAN 

## Requirements
- python 3.6
- Install python packages
    ```bash
    $ pip install -r requirements.txt
    ```

## How To Run
- Train model
    ```bash
    $ python dcgan.py   # DCGAN
    $ python wgangp.py  # WGAN-GP
    $ python sngan.py   # SN-GAN
    ```
- [Optional] See tensorboard for more training details.
    ```bash
    $ tensorboard --logdir=log/
    ```
    open [0.0.0.0:6006](0.0.0.0:6006)

## Generate GIF
```bash
$ python sample2gif.py --name <model name>
```
All available model name is list in [Models](#Models) 