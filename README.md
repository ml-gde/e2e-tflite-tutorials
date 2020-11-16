# E2E TFLite Tutorials

Here is a list of sample app ideas and projects.

We would love your help! You can help by creating a tflite model ready for implementation, add a mobile app idea that needs a tflite model created, or write an end-to-end tutorial with sample code. 

This is also where you can seek help from the community.


## Project ideas (help needed!)
If you are interested in helping out, take a look at the potential projects below and assign an corresponding issue to yourself from the [repo issue](https://github.com/ml-gde/e2e-tflite-tutorials/issues) list.

Once you form a project team, move the idea to the "in progress" section below, create a new repo and link to it. 

* YOLO - [overview](overviews/yolo.md).
* Classify pose - [overview](overviews/classify_pose.md) (an example use-case can be found [here](https://github.com/ml-gde/e2e-tflite-tutorials/issues/33)).
* Sound classification - [overview](overviews/classify_sound.md) (an example use-case can be found [here](https://github.com/ml-gde/e2e-tflite-tutorials/issues/32)).

Here are some more details on how exactly you can help:

* Generate ideas
* Create tflite model(s)
* Create Colab Notebook(s) demonstrating the model creation process along with running inference in Python
* Publish tflite model(s) optional
* Develop Android app(s) to demonstrate the model(s)
* Develop iOS app(s) to demonstrate the model(s)

The tutorials listed below would give you a good idea of the afore-mentioned pointers. [Here](https://github.com/ml-gde/e2e-tflite-tutorials/wiki/How-to-contribute-to-the-E2E-TFLite-Tutorials%3F) you can find more detailed instructions on **how to contribute**. 

## End-to-end tutorials (in progress)
Take a look at the in progress projects to see what it's like to work on a project.

* [Deeplab V3](https://github.com/tensorflow/models/tree/master/research/deeplab ) - image segmentation. Colab Notebooks demonstrating the TFLite model conversion process for a variety of DeepLab V3 models along with running inference in Python are [available on TF Hub](https://tfhub.dev/s?module-type=image-segmentation&publisher=sayakpaul). The TFLite variants of the DeepLab V3 models are also available from the same link. 
* [DeepSpeech](https://github.com/mozilla/DeepSpeech) - a very popular ASR framework.
* Segmentation + Style Transfer - [project repo](https://github.com/margaretmz/segmentation-style-transfer).
* [`arbitrary_image_stylization` by Magenta](https://github.com/magenta/magenta/tree/f3b66aa1354cd933f0e9757a567cc9a3d2d03297/magenta/models/arbitrary_image_stylization) - art generation. Colab Notebooks demonstrating TFLite model conversion process along with inference in Python are [available on TF Hub](https://tfhub.dev/sayakpaul/lite-model/arbitrary-image-stylization-inceptionv3/dr/predict/1). The TFLite models can be downloaded from the same link. 
* Enhanced super res GAN - [project repo](https://github.com/margaretmz/esrgan-e2e-tflite-tutorial).
* Speech Command - [overview](overviews/speech_command.md).

## End-to-end tutorials (completed)

Once a project has been completed, please open a PR to [awesome-tfite](https://github.com/margaretmz/awesome-tflite) to add the links of the tflite model, sample code and tutorials.
* [U-GAT-IT](https://github.com/taki0112/UGATIT) (Selfie <-> Anime) - [project repo](https://github.com/margaretmz/selfie2anime-e2e-tutorial).
* SPICE (Pitch Detection) - [Project repo](https://github.com/farmaker47/Pitch_Estimator) - [Medium article](https://medium.com/@farmaker47/estimating-musical-scores-pitch-in-android-with-tensorflows-spice-model-4d712ded96f8).
* How to Create a Cartoonizer with TensorFlow Lite - [project repo](https://github.com/margaretmz/Cartoonizer-with-TFLite/), [blog post](https://blog.tensorflow.org/2020/09/how-to-create-cartoonizer-with-tf-lite.html).
* Optimizing MobileDet for Mobile Deployments - [Colab Notebook](https://colab.research.google.com/github/sayakpaul/Adventures-in-TensorFlow-Lite/blob/master/MobileDet_Conversion_TFLite.ipynb), [article](https://sayak.dev/mobiledet-optimization/).
* Training custom object detectors and converting them to TFLite - [project repo](https://github.com/sayakpaul/E2E-Object-Detection-in-TFLite). This repository shows how to train a custom detection model with the TFOD API (TF2 and TF1), optimize it with TFLite, and perform inference with the optimized model.

## Contact the admins

This should be done via GitHub issues. ***Only*** use it when you have something relevant to discuss otherwise the issues will be automatically closed. 
