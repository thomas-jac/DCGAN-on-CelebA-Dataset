# DCGAN-on-CelebA-Dataset
This is a Deep Convolutional GAN (DCGAN) applied on the CelebA dataset to generate new face images. 
The complete dataset can be downloaded from [kaggle](https://www.kaggle.com/jessicali9530/celeba-dataset) or [here](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

The models for the discriminator and generator were inspired from [here](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html). The values of the various hyperparameters were chosen according to the recommendations of the authors of the original [DCGAN paper](https://arxiv.org/abs/1511.06434). The network was trained on a GPU for 5 epochs and achieved satisfactory results. Further implementation details can be seen in the Jupyter notebook.
