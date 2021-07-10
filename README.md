# Image data augmentation

Image augmentation is an engineered solution to create a new set of images by applying standard image processing methods to existing images.

![alt text](https://datamonje.com/wp-content/uploads/2021/07/Image-Data-Augmentation.jpg "DataMonje Image Augmentation")

This solution is mostly useful for neural networks or CNN when the training dataset size is small. Although, Image augmentation is also used with a large dataset as regularization technique to build a generalized or robust model.

Deep learning algorithms are not powerful just because of their ability to mimic the human brain. They are also powerful because of their ability to thrive with more data. In fact, they require a significant amount of data to deliver considerable performance.

High performance with a small dataset is unlikely. Here, an image data augmentation technique comes in handy when we have small image data to train an algorithm.

Image augmentation techniques create different image variations from the existing set of images using the below methods:

- Image flipping
- Rotation
- Zoom
- Height and width shifting
- Perspective and tilt
- Lighting transformations
- Crop
- Noise addition
- Cutout or erasing

This notebook contains code for:

- Image augmentation with ImageDatagenerator
- Custom augmentation with ImageDatagenerator's preprocessing_function
- Image Augmentation using Keras' experimental layers
- Building custom layers for image augmentation

Visit this article for detailed information: [Guide to Image Augmentation: from beginners to advance](https://datamonje.com/image-data-augmentation/ "Image Data Augmentation Guide")
