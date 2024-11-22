# Flowers102_NeuralNetworkProject
SC4001 NTU Neural Networks Project

F. Flowers Recognition
The Oxford Flowers 102 dataset is a collection of 102 flower categories commonly occurring in the United Kingdom. Each class consists of between 40 and 258 images. The images have large scale, pose and light variations. In addition, there are categories that have large variations within the category and several very similar categories. The dataset is divided into a training set, a validation set and a test set. The training set and validation set each consist of 10 images per class (a total of 1020 images each). The test set consists of the remaining 6149 images (minimum 20 per class). Some tasks to consider:
Main Task: Implement a classificatoin model to classify the flower images. Datasets:
• The dataset is available in TorchVision https://pytorch.org/vision/main/generated/torchvision.datasets.Flowers102.html
• The Oxford Flowers 102 Dataset https://www.robots.ox.ac.uk/~vgg/data/flowers/102/ Additional tasks:
• Modify some previously published architectures e.g., increase the network depth, reducing their parameters, etc. Explore more advanced techniques such as deformable convolution or visual prompt tuning for Transformers.
• Analyze the results of using fewer training images, i.e., few-shot learning
• Use more advanced transformation techniques such as MixUp (see the original paper and its
PyTorch implementation here)
• Try more advanced loss function such as triplet loss
