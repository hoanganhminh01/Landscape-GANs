<div align="center">
<figure>

 <h1> <b>Landscape Generation using Generative Adversarial Networks: A Comparison </b> </h1>
 <h3> Minh Hoang & Kenneth Ma </h3>
 
</figure>
</div>
 <em>Published on December 13, 2022</em>
<div align="right">
 
</div>

## <ins><b> Abstract </b></ins>
In this project, we explore various image generation techniques using Generative Adversarial Networks (GANs) to generate fake images of landscapes. We generated images with 3 different GANs and compare the results. We began by training an existing deep convolution GAN architecture on a Landscape image dataset from Kaggle, downsampling the dataset to 64x64 images to reduce overall training time. Then, we built two additional DCGAN networks on top of this one to handle 128x128 and 256x256 images. Unfortunately, we weren't able to train the 256x256 network with our available compute power, so instead, we compared our 64xc64 and 128x128 generated images to images gnereated by a StyleGANv3 that was pre-trained on a different landscape dataset. For an more in-depth overview of our procedure and results, see the following video summary. [INSERT HERE]().

## <ins><b> Introduction and Problem Statement </b></ins>
<b>Problem Statement:</b> Landscapes have always been a source of inspiration to anyone fond of hiking and sightseeing. We wanted to see whether deep learning models trained on landscape images can generate novel landscapes that are as realistic as nature.



## <ins><b> Related Works </b></ins>

## <ins><b> Dataset and Preprocessing </b></ins>
We used a Kaggle dataset consisting of 4,319 images of landscapes without any metadata. Since the size of the images in the dataset are inconsistent, we need to do some preprocessing to crop and resize the images into specific dimensions. We performed cropping and resizing the dataset into 3 different dimensions: 64 x 64, 128 x 128 and 256 x 256. The dataset is available [here](https://www.kaggle.com/datasets/arnaud58/landscape-pictures).

<div align="center">
<figure>

 <img alt="sample1" src="https://raw.githubusercontent.com/hoanganhminh01/Landscape-Generation-GAN/main/data_preprocessed_256/preprocessed_256/00000000_(5).jpg"> 
 <img alt="sample2" src="https://raw.githubusercontent.com/hoanganhminh01/Landscape-Generation-GAN/main/data_preprocessed_256/preprocessed_256/00000023_(7).jpg">
 <img alt="sample3" src="https://raw.githubusercontent.com/hoanganhminh01/Landscape-Generation-GAN/main/data_preprocessed_256/preprocessed_256/00000038_(3).jpg">
 
</figure>
</div>


## <ins><b> Experiments </b></ins>
<div align="center">
<figure>

 <img alt="model1" src="https://raw.githubusercontent.com/hoanganhminh01/Landscape-Generation-GAN/main/outputs/dcgan.png"> 
 
</figure>
</div>
## <ins><b> Results </b></ins>
### <ins><b> Model Performance </b></ins>
<div align="center">
<figure>

 <img alt="loss1" src="https://raw.githubusercontent.com/hoanganhminh01/Landscape-Generation-GAN/main/outputs/loss64.png"> 
 <img alt="loss2" src="https://raw.githubusercontent.com/hoanganhminh01/Landscape-Generation-GAN/main/outputs/loss128.png">
 
</figure>
</div>

### <ins><b> Model Evaluation </b></ins>


### <ins><b> Outputs </b></ins>

### <ins><b> Output Comparison </b></ins>

### <ins><b> Additional Example: Pre-trained StyleGANv3 </b></ins>

## <ins><b> Conclusion and Future Works </b></ins>
 
## <ins><b> References </b></ins>
