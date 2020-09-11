# Pytorch-Autoencoders-fashionMnist
Implementation of 3 flavours of autoencoders (vanilla AE, Convolutional-AE, Variational-AE) trained on [fashionMnist dataset, courtsey of zalandoresearch](https://github.com/zalandoresearch/fashion-mnist).
<br/>**A notebook is also provided which enables a simple and easy-to-use playfield to try out these different models.**


## Vanilla-Autoencoder Architecture
<div align="center">
  <img src="./images/vanilla_AE.png" width="600">  
  <p>Simplified vanilla autoencoder architecture.</p>
</div>

## Convolutional-Autoencoder Architecture
<div align="center">
  <img src="./images/CNN_AE.png" width="600">  
  <p>Simplified convolutional-autoencoder  architecture.</p>
</div>


## Variational-Autoencoder Architecture
<div align="center">
  <img src="./images/VAE.png" width="600">  
  <p>Simplified variational-autoencoder architecture.</p>
</div>

## Training using a ubiquitous `Learner`
A common learner was devised to train all three models. This common `Learner` class enables training, testing, and progress visualization routine in a coherent manner.
