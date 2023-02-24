# Monet paintings using DCGAN

## Deep Learning

## Structure of this notebook:

* Description of the problem and data
* Exploratory data analysis (EDA)
* Analysis - model building and training
* Result
* Conclusion

https://www.kaggle.com/competitions/gan-getting-started/overview


### Description of the problem and data:

The Monet paintings have a unique style. Without having Claude Monet it might be difficult to repeat his painting style for the new scenes. The main goal of this competition/project is to apply the style of Monet painting to a new given photo so that it look like it has been painted by Claude Monet. This project uses special type Generative Adversarial Networks (GAN) which is mainly used for image translation. Images are initially different sizes. We are not given a dataframe to view or plot values. Instead, we will move on to the EDA and view some images. Prior to training, we will set our training data (images) and we will normalize all images.


### Input data:

monet_tfrec_path = '../input/gan-getting-started/monet_tfrec'
monet_jpg_path = '../input/gan-getting-started/monet_jpg'

photo_tfrec_path = '../input/gan-getting-started/photo_tfrec'
photo_jpg_path = '../input/gan-getting-started/photo_jpg'
