# Audio classification 

## Introduction

Use fastai to classify audio data.By converting audio files into images,and then using the techniques of image classification to classify audio images.there are three audio-to-image conversion methods in the code.

使用fastai 来对音频数据分类。通过把音频文件转换成图像，然后利用图像分类的技巧对音频图像进行分类。代码中共利用了三种音频转图像的方式。

## Three feature conversion methods
#### The result of sending the same audio file into three different feature conversion codes
同一个音频文件送入到三种不同的特征转换代码中得到的结果
#### chroma
![chroma](https://github.com/zjmlovlin/audio-classification/blob/master/show_img/1-137-A-32-chroma.jpg)
#### melspec
![melspec](https://github.com/zjmlovlin/audio-classification/blob/master/show_img/1-137-A-32-melspec.jpg)
#### mfccs
![mfccs](https://github.com/zjmlovlin/audio-classification/blob/master/show_img/1-137-A-32-mfccs.jpg)

#### Among the three features, melsec is the best, chroma is average, and mfccs is not good
#### 三种特征中，melspec效果最好，chroma一般，mfccs效果不好
## How to use
    
    extractor_3feature.ipynb    -->    Feature extraction code for converting audio files into 3 different picture features
                                       用来将音频文件转换成3种不同的图片特征的特征提取的代码
    sound_classification.ipynb    -->    The image features obtained above are sent to the image classification CNN network to obtain the classification results
                                         将上面得到的图片特征送入到图像分类CNN网络得到分类结果
