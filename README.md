# CS260D_Final_Project
Repository containing Python Notebooks for "Data Poisoning Attack on Pruned Neural Networks" by Janani Venkatramani, Sherine Chally, Diya Lakhani, and Anvi Penmetsa

The following is a list of notebooks that can be found in this respository, alongside a brief description of how they are relevant to the paper:<br>
1) CS260D_Approach_1_UNet_MNIST.ipynb has code for Approach 1 using the U-Net model as the poison generator. The U-Net is modified to have two downsampling layers and two upsampling layers. The models are trained on the MNIST dataset.
2) CS260D_Approach_1_Oversimplified_UNet.ipynb has code for Approach 1 using a simple 2-convolutional layer poison generator. We refer to this generator as "Oversimplified U-Net".
3) CS260D_Approach_1_UNet_CIFAR10.ipynb has code for Approach 1 using the modified U-Net model as a poison generator and is tested on the CIFAR-10 dataset.
