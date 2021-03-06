# Low-light-image-synthesis
This reposity contains the code used for our 8th semester VGIS project at Aalborg University.


# Abstract
Low light image enhancement deep learning networks need enormous amount of images for training. State of the art low light enhancement models use a mixture of real low light image datasets and synthetically degraded images by adjusting gamma and adding noise. However, most of the existing datasets are insufficient and the degradation pipelines do not capture the true essence of real low light images. RELLISUR was created to overcome this challenge and provides a large scale real low light to real normal light image dataset. This still does not address every use case in the set of low light image enhancement problems. In order to extend RELLISUR and provide a sophisticated image degradation method, we present a supervised multi-domain GAN for normal light to low light translation. Our model takes real normal light images and generate low light images with specified exposure value ranging from -2.5EV to -4.0EV. Upon extensive experiments, Our model was also found to provide better and variety of degradation, closer to real low light images.


We have used RELLISUR dataset for training. Low light Images and normal light images are to be concatenated before training. 
Comments are added in the notebook that explains the code. 
