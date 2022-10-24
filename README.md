# -Learning-Based-Representation-of-Data-towards-filtering-and-Selection-of-Images-
Learning-based approach is followed to develop a deep learning model to filter and select the images from crowdsourced data that helps in the better 3D reconstruction of Heritage sites. Intentional blur and unintentional blur images are also considered while filtering which is unique in the project.
![image](https://user-images.githubusercontent.com/47131180/197508153-15024136-dec3-4719-b86a-cb2843b48d8e.png)

In this project, we work towards filtering data and selecting images. The input data consists
of crowdsourced images. Crowdsourced images are those which are acquired from a huge crowd
(group of people). Crowdsourced data is collected to obtain widespread observation. Crowdsourced data is captured by different people using different devices with varying intentions. The
captured crowdsourced data may have blur, noise, brightness, shadow, occlusion, redundant images, and images containing text. Hence there is a requirement to come up with a methodology
to classify blur and sharp images. Specifically, to classify intentional blur and un-intentional blur.
Intentional blur images are those which contain blur in the background and un-intentional blur
images are those which contain blur in the foreground. To classify intentional and un-intentional
blur, we implement different methodologies like two-class CNN (convolutional neural network)
classifier, AE (autoencoder) based classifier, classification using vgg16 architecture, and classification using LeNET-5 architecture. The classification model will classify intentional blur images
and un-intentional blur images. This project can be extensively used when we need to filter the
data while selecting the images for 3D reconstruction.
