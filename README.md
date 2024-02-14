# Vision-Transformer-Based-Im-age-Classification-Implementation-Using-Pytorch
Implement a basic version of vision transformer

Training a Simple ViT using Pytorch [20 marks]

In this question, you will implement a vision transformer based image classification model using pytorch. 
Implement a basic version of vision transformer (https://arxiv.org/pdf/2010.11929.pdf), that first divides an image into patches and then passes them through a set of multihead self attention modules to perform classification. Please check out the details in the paper. Note that classification happens from the CLS token of the final transformer layer.

[Experiment 1] Train this model on the CIFAR-10 dataset for 10-class classification. Keep the number of attention heads to be 4 for all the experiments. [6 points]

[Experiment 2] Try out different patch sizes (like 4x4, 8x8, 16x16). You can divide the image into both overlapping and non-overlapping patches. [4 points]

[Experiment 3] How does model performance change if you vary the number of attention heads? [4 points]

[Experiment 4] Perform classification by using the CLS token from different layers of the model. [6 points]
Create a detailed report of all the experiments and analyses.
