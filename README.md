# Audio classification 

### Introduction

Use fastai to classify audio data.By converting audio files into images,and then using the techniques of image classification to classify audio images.there are three audio-to-image conversion methods in the code.
使用fastai 来对音频数据分类。通过把音频文件转换成图像，然后利用图像分类的技巧对音频图像进行分类。代码中共利用了三种音频转图像的方式。

### Three feature conversion methods
#### chroma
    chroma image
![chroma](https://github.com/zjmlovlin/audio-classification/blob/master/show_img/1-137-A-32-chroma.jpg)
#### melspec
    melspec image
![melspec](https://github.com/zjmlovlin/audio-classification/blob/master/show_img/1-137-A-32-melspec.jpg)
#### mfccs
    mfccs image
![mfccs](https://github.com/zjmlovlin/audio-classification/blob/master/show_img/1-137-A-32-mfccs.jpg)

### How to use
    
    extractor_3feature.ipynb    -->    Feature extraction code for converting audio files into 3 different picture features
    sound_classification.ipynb    -->    The image features obtained above are sent to the image classification CNN network to obtain the classification results
    extractor_3feature.ipynb    -->    用来将音频文件转换成3种不同的图片特征的特征提取的代码
    sound_classification.ipynb    -->    将上面得到的图片特征送入到图像分类CNN网络得到分类结果
