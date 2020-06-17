# Vanila-GAN
Teamproject Vanila-GAN Group 2.
Team members: Daniel, Jialu, Lasse

# Documentation<br />
#### 22.05.2020<br />
We got in touch by Email,and the created a whatsapp group and a discord Server.<br />

#### 23.05.2020 - 24.05.2020<br />
We created two channel "code" and "weblinks" on discord,in order to share material.Then we started our first call on discord and discussed how to implement gan.<br />
After reading material for one day,we created the repository "vanila-gan" on github and uploaded the example code.<br />

#### 25.05.2020<br />
Since the structure of the example code is already clear,we divided the tasks before Training-part into four pieces:<br />
  
  - 1.dataset(imlement by Lasse)<br />
  - 2.generator(imlement by Jialu)<br />
  - 3.discriminator(imlement by Daniel)<br />
  - 4.random noise and optimization(random)<br />
  
the first deadline is 31.May.

#### 26.05.2020 - 31.05.2020 <br />
Our own task has been completed while we helped each other to improve the code. <br />

#### 08.06.2020<br />
The second part is to implent Training.

During the third meeting,we :<br />
   - added Random noise ,optimization and Real/fake data target<br />
   - corrected the random noise<br />
   - corrected the generator function<br />
   - corrected the optimization part<br />


#### 13.06.2020 - 17.06.2020<br />
Train-generator and train-discriminator has been added.<br />
We had our fourth meeting and dicussed to improve the logger function and README.<br />


#### ?.06.2020<br />
Mission accomplished.<br />



## Tutorial on how to run the GAN in Colab<br />
1.Open Notebook in Google Colab with following link:https://colab.research.google.com/github/Victorious3/vanila-gan/blob/master/Generative_Adversarial_Networks_PyTorch.ipynb<br />
2.To add this .ipynb file to Drive ,using the link 'https://drive.google.com/drive/my-drive' , run this cell and get authorization code.In this case TensorboardX-2.0 should be installed successfully.<br />
3.In order to run the whole GAN-code,go under 'Run all' over the dropdown menu 'Runtime'.<br />
4.<br />

## Overview<br />
The Vanila GAN is a Generative Adversarial Network that proposed by Ian Goodfellow to use adversarial processes to obtain generative models.The main part consists of Generator and Discriminator.<br />
In this project,we using the MNIST dataset to holding images of handwritten numbers.<br />
Our goal is to let the Generator produces a large number of fake images,and let the Discriminator to distinguish these 'fake data' and 'training data' .They will improve themselves together in this progress,and in the end it will be impossible for Discriminator to distinguish fake data and real data.In this way we can get a Generator with good enough effect.<br />

# Explanation of code<br />


