# Image-Caption-Generator
The project is to predict the captions for the input image.
The dataset consists of 8k images and 5 captions for each image.
A encoder decoder model is used for generating captions for image. Cnn model vgg16 is used for getting features for the images and is then fed to a layers of lstm as a decoder to generate further sequence of captions(text). Both the concepts of cnn and rnn are employed here.

## Dataset :<br>
[flickr 8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)

## Referred Vlogs: <br>
[1.clairvoyant](https://www.clairvoyant.ai/blog/image-caption-generator)<br>
[2.machinelearningmastery](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)<br>

## Model Prediction: <br>

<img src="https://github.com/gourav19102/Image-Caption-Generator/blob/main/images/caption.PNG" width="400" height="400">

## Model Performance (Bleu score): <br>
<img src="https://github.com/gourav19102/Image-Caption-Generator/blob/main/images/bleu.PNG" width="200" height="100">
