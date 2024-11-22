In this, we will be working on an image classification task (codename `pnp`) using the transfer learning technique.
The task objective is to determine whether an image contains a person (`pnp` stands for person / non-person) -- a binary classification task.

## Dataset
* Dataset contains 80K images with known labels (for model development), and 20K images with unknown labels (for scoring).
* Dataset has been created from a subset of COCO Dataset, and so all copyrights belong to the original authors: https://cocodataset.org/#termsofuse
* Images have been rescaled and padded to be of shape (224, 224, 3).

Key Highlights: Leveraged transfer learning using the MobileNet architecture for computational efficiency. Applied data augmentation techniques (rotation, flipping, zoom) and rescaling for better model generalization. Optimized for accuracy and performance on large-scale datasets. Tools: Python, TensorFlow/Keras.
