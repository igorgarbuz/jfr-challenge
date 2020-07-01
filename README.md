# JFR-Hackhathon
Annual challenge organised by the french association of radiologists. 2019 edition took place from 14/09 to 13/10, teams were presented with x3 datasets:
1. TC images of lungs for cancer nodules detection (classification)
2. TC images of the brain for prediction of multiple sclerosis' level (regrassion: score prediction 1-20)
3. Calculation of the muscle surface for sarcopenia (segmentation)
Present notebooks are a part of lung cancer classification project.

Learning dataset consisted of ~650 3D DICOM images with an typical average resolution of 512x512x350.
Images were processed for NN 224x224x3 input to use weights pretrained on the ImageNet. 
An example of a normalized x3 2D slices stacked to RGB image:

![alt text](https://github.com/IgorVG/jfr-challenge/blob/master/2D-slice-sample.jpg)

Link to organiser's web-site:
https://jfr.radiologie.fr/presidents-word
