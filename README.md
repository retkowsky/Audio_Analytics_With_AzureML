# Audio Analytics with Azure ML and AutoML for Images

Audio processing can consist of extracting audio signal information into spectrograms (time vs frequency vs Db) images that we can use to build a custom vision model with Azure using AutoML for Images. 

We can as well extract some audio components and use a generic classification model with Azure ML and its AutoML features.

<img src="image.jpg">

## Demo 1: Acoustic Anomaly Detection for Machine Sounds based on Images

### Problem
Is it possible to detect an anomaly (not normal noise) using a machine sound file?

### Solution
- We will collect some normal and anomaly sounds files
- We will generate spectrograms for all the files 
- We will build and train a two-class classification model (Anomaly vs no anomaly) using computer vision algorithms with Azure Custom Vision and Azure AutoML for Images.
- We will generate audio features and use usual classification techniques like SVM. We will use AutoML for Classification with Azure ML.
- We will test the anomaly detection models we made.

## Azure AutoML
AutoML is an Azure Machine Learning feature, that empowers both professional and citizen data scientists to build machine learning models rapidly. Since its launch, AutoML has helped accelerate model building for essential machine learning tasks like Classification, Regression and Time-series Forecasting.

With the preview of AutoML for Images, there will be added support for Vision tasks. Data scientists will be able to easily generate models trained on image data for scenarios like Image Classification (multi-class, multi-label), Object Detection and Instance Segmentation.

AutoML for Images is currently in Public Preview.

AutoML for Images documentation:
http://aka.ms/AutoMLforImagesDoc

AutoML for Images Algorithms:
http://aka.ms/AutoMLforImagesAlgorithms

AutoML for Images Tutorial:
http://aka.ms/AutoMLforImagesTutorial

### Note
All these Python notebooks were made for demo purposes. They were not designed for production usage. This feature is currently in public preview. This preview version is provided without a service-level agreement. Certain features might not be supported or might have constrained capabilities. For more information, see Supplemental Terms of Use for Microsoft Azure Previews. https://azure.microsoft.com/en-us/support/legal/preview-supplemental-terms/

31-May-2022
Serge Retkowsky | serge.retkowsky@microsoft.com | https://www.linkedin.com/in/serger/
