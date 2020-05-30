# One Shot Learning with PyTorch

Setup:

1. Download dataset from https://github.com/brendenlake/omniglot

2. Go to /python and extract the folder image_background.zip

3. Set the root_dir in siamese.ipynb to the directory of the extracted folder for the dataloader to fetch the images.

4. Remember to remove all .DS_store with the command ```find . -name '.DS_Store' -type f -delete``` if you are using Mac.



Network Architecture:

1. The network architecture currently follows the architecture given by http://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf, but some additions and tuning of the hyperparameters and network structure for experimentation.

Reference:

https://github.com/fangpin/siamese-pytorch

https://sorenbouma.github.io/blog/oneshot/

https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d

