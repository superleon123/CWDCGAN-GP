# CWDCGAN-GP
To improve the performance of convolutinoal neural network, doing data augmentation based on Conditional Deep Convolutional WGAN-GP on colorectal cancer image dataset. Compared with ImageDataGenerator augmented and original images.

Folder "Col28" : code for colorectal cancer 28*28 pixel grayscale image

Folder "Col28_RGB" : code for colorectal cancer 28*28 pixel color image

Folder "Col64" : code for colorectal cancer 64*64 pixel grayscale image

Folder "Col64_RGB" : code for colorectal cancer 64*64 pixel color image


The files under the folder "col28":
color-28-28.ipynb      (test reading csv file for grayscale image)

cwgan-gp-color.ipynb    (CWDCGAN-GP augmentation for grayscale image)

color_eval_origin.ipynb   (Evaluation on the origin image)

color_eval_augment_ig_generator.ipynb   (Evaluation on the image created by ImageDataGenerator)

color_eval_augment.ipynb       (Evaluation on the image created by CWDCGAN-GP)

displayGeneratedImage_28281.ipynb    (Display images in 5*2 grid)

Under the folders "Col28_RGB", "Col64", and "Col64_RGB" , the files have the similar names as the files under folder "col28".


