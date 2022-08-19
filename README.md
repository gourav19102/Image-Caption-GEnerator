# Image-Caption-Generator
Predicting  captions for the input image is the goal of the project. The dataset consists of 8k images and 5 captions for each image. A encoder decoder model is used for generating captions for any provided image. Pretrained Cnn model vgg16 is used for extracting features from training images and is then fed to a layer of lstm as a decoder to generate further sequence of captions(text). Understanding in both the fields of computer vision and natural language processing is required for the project.
## Dataset :<br>
* Flickr8k dataset contains 8092 photographs along with text descriptions by their photographs
* The dataset is about 8 GB in size
* link to the data : [flickr 8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)

## Referred Vlogs: <br>
[1.clairvoyant](https://www.clairvoyant.ai/blog/image-caption-generator)<br>
[2.machinelearningmastery](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)<br>

## Model Prediction: <br>

<img src="https://github.com/gourav19102/Image-Caption-Generator/blob/main/images/caption.PNG" width="400" height="400">

## Model Performance (Bleu score): <br>
<img src="https://github.com/gourav19102/Image-Caption-Generator/blob/main/images/bleu.PNG" width="200" height="100">
