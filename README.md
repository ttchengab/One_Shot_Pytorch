# 4211_Project_One_Shot_Learning

Setup:

1. Download dataset from https://github.com/brendenlake/omniglot

2. Go to /python and extract the folder image_background.zip

3. Set the root_dir in siamese.ipynb to the directory of the extracted folder for the dataloader to fetch the images.

4. Remember to remove all .DS_store with the command ```find . -name '.DS_Store' -type f -delete``` if you are using Mac


Dataset Format:

1. The dataset selects n random pairs of images from the dataset, half of the pairs are the same alphabet while the other half are different alphabets. n will be equal to the variable dataSize

2. The dataset is then splitted into a train set and a validation set based with the ratio given by TRAIN_PCT.

Network Architecture:

1. The network architecture currently follows the architecture given by http://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf

Reference:

https://github.com/fangpin/siamese-pytorch

https://sorenbouma.github.io/blog/oneshot/

https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d

