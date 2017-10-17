# deep GAN
[![Github All Releases](https://img.shields.io/github/downloads/atom/atom/total.svg?style=plastic)]()

deep GAN experiment

# Requirement
* tensorflow
* numpy

# Usage
Ensure your system is installed with Git and clone this reposity with command line:

```
$ git clone https://github.com/naturomics/deepGAN.git
```
``cd deepGAN `` and edit file 'main.py' to suit your configure.

Then, start to run with command line:
```
$ python main.py
```

# Results

## Training Loss
Experiments were carried out with different hyper parameters **theta** and **beta**

The legend for various hyper parameters(theta00 meaning theta=0.0 and no using beta, theta04beta08 i.e. theta=0.4 and beta=0.8, etc.):
![Legend](imgs/training/legend.png)

d1 total loss:
![d1_loss](imgs/training/d1_loss.png)

d2 total loss:
![d2_loss](imgs/training/d1_loss.png)

d loss with g1 as fake input:
![d_loss_g1AsFake](imgs/training/d_loss_g1AsFake.png)

d loss with g2 as fake input:
![d_loss_g2AsFake](imgs/training/d_loss_g2AsFake.png)

g1 loss:
![g1_loss](imgs/training/g1_loss.png)

g2 loss:
![g2_loss](imgs/training/g2_loss.png)
