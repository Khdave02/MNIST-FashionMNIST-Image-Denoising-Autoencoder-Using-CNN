# MNIST-FashionMNIST-Denoising-Autoencoder-Using-CNN
Implementation of Denoising Autoencoder on MNIST/FashionMNIST by using Pytorch and CNN

## MNIST/FashionMNIST-Dataset
MNIST DATASET is available at
The MNIST database is available at [MNIST-DATASET](http://yann.lecun.com/exdb/mnist/) and Fashion-MNIST at [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)

The MNIST database is a dataset of handwritten digits. It has 60,000 training samples, and 10,000 test samples. Each image is represented by 28x28 pixels, each containing a value 0 - 255 with its grayscale value.

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 

![This is an image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkdIB5OILwmRSfRB_Qf5-upoObl2WYTIP1_A&usqp=CAU)
![This is an image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRBxb7UywgFVpcIdEWEfolQc9VEm3hDIEpBSg&usqp=CAU)

## Denoising Autoencoder
- In denoising AE, data is corrupted in some manner through the addition of random noise, and the model is trained to predict the original uncorrupted data.
- the choice of CNN serves the purpose for dimension and computational complexity reduction when arbitrary-sized images are used as input.
![This is an image](https://miro.medium.com/max/5160/1*SxwRp9i23OM0Up4sEze1QQ@2x.png)

## Results & Outputs
![AutoencoderMnistCNN ipynb - Colaboratory - Google Chrome 10-10-2021 11_23_01 (3)](https://user-images.githubusercontent.com/87975841/136731578-1425201a-2a9a-43f5-8cbb-cb885a35bfb5.png)

![AutoencoderMnistCNN ipynb - Colaboratory - Google Chrome 10-10-2021 11_44_01 (3)](https://user-images.githubusercontent.com/87975841/136731685-6dc4a90e-e016-424e-bbba-a91ef1a5d4fa.png)

## Hyperparameters
- Batch-Size -> 64
- Learning-rate ->0.001
- Weight-decay -> 0.00001
- MSE Loss
- Adam Optimizer
- num of Epochs -> 10
## Loss plots
#### MNIST
![Untitled24 ipynb - Colaboratory - Google Chrome 07-10-2021 12_47_18 (5)](https://user-images.githubusercontent.com/87975841/136733434-74330e31-b4a8-4423-9622-e6aff43110b5.png)
#### Fashion-MNIST
![Untitled24 ipynb - Colaboratory - Google Chrome 07-10-2021 12_47_54 (4)](https://user-images.githubusercontent.com/87975841/136733468-dc6e3df5-43c1-4648-8e22-c39ed686d3c7.png)

## Architecture
![Untitled drawing - Google Drawings - Google Chrome 11-10-2021 09_15_03 (2)](https://user-images.githubusercontent.com/87975841/136733323-1595d8c0-5431-4654-9cdd-97c6eaa8173d.png)

## Why MSE LOSS
We're comparing pixel values in input and output images, it will be best to use a loss that is meant for a regression task. Regression is all about comparing quantities rather than probabilistic values.
## Resources
- [Coursera Deep learning](https://www.coursera.org/specializations/deep-learning?)
- [Pytorch Documentation](https://pytorch.org/)
- [Denoising AE](https://lilianweng.github.io/lil-log/2018/08/12/from-autoencoder-to-beta-vae.html)
- [Notes for deep learning](https://aman.ai/coursera-dl/)
- [Autoencoder basic understanding](https://www.youtube.com/watch?v=q222maQaPYo&t=104s)

Thanks to all contributors for providing great resources for learning

## Download and clone this repository
https://github.com/Khdave02/MNIST-FashionMNIST-Denoising-Autoencoder-Using-CNN.git
