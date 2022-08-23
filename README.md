# Image-Caption-Generator
Predicting  captions for the input image is the goal of the project. The dataset consists of 8k images and 5 captions for each image. A encoder decoder model is used for generating captions for any provided image. Pretrained Cnn model vgg16 is used for extracting image features while lstm is used to extract textual features .The features extracted are merged and passed to dense layers decoding the encodes into sequence of text.Merge architecture is used here which is different than normal encoder decoder model where generally lstm acts as a generator of sequences. Understanding in both the fields of computer vision and natural language processing is required for the project.
## Dataset :<br>
* Flickr8k dataset contains 8092 photographs along with text descriptions by their photographs
* The dataset is about 8 GB in size
* link to the data : [flickr 8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)

## Basic Workflow:
* Image Feature Extraction: <br>
    *  pretrained cnn model "VGG16" has been used to extract features from the images
    *  50% dropout and a dense layer
* Sequence Processer:
    * input sequence of 34(maxlength) words
    * embedding layer for word embeddings
    * 50% dropout
* Decoder
    * LSTM with 256 units
    * dense layer with softmax to produce probability of next word

## Referred Paper/Blogs: <br>
[1.Where to put the Image in an Image Caption Generator](https://arxiv.org/abs/1703.09137)<br>
[2.clairvoyant](https://www.clairvoyant.ai/blog/image-caption-generator)<br>
[3.machinelearningmastery](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)<br>

## Model Prediction: <br>

<img src="https://github.com/gourav19102/Image-Caption-Generator/blob/main/images/caption.PNG" width="400" height="400">

## Model Performance (Bleu score): <br>
<img src="https://github.com/gourav19102/Image-Caption-Generator/blob/main/images/bleu.PNG" width="200" height="100">
