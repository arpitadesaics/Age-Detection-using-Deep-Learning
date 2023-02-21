# Age-Detection-using-Deep-Learning


Deep Learning - Use this dataset to detect age: https://www.kaggle.com/datasets/arashnic/faces-age-detection-dataset. Build two deep models - one from scratch and the other using a pretrained model to obtain embeddings of the given data. Compare the performances.

DATA PRE-PROCESSING:

IMAGE RESIZING
When dealing with an image processing problem and the input images come in different sizes the resize function is used to resize all input images to a fixed size, in our case we resized input images to 100x100

DENOISING
It is a process to reserve the details of an image while removing the random noise from the image as far as possible
Median denoising is used to remove the noise from the data. The advantage is it preserves edges while removing the noise from our image.

IMAGE NORMALIZATION
Image normalization is a process, often used in the preparation of data sets for artificial intelligence (AI), in which multiple images are put into a common statistical distribution in terms of size and pixel values

CATEGORICAL ENCODING
We encoded the data using categorical encoding for training the model


MODELS IMPLEMENTED
1) Deep CNN
2) VGG

