# Audio Analytics with Azure ML and AutoML for Images

Audio processing can consist of extracting audio signal information into spectrograms (time vs frequency vs Db) images that we can use to build a custom vision model with Azure using AutoML for Images. 

We can extract some audio features as well and use a generic classification model with Azure ML and its AutoML capabilities to find the best model.

## AI Show Audio Analytics demo<br>
<a href="https://aka.ms/AIShow/AudioAnalytics">
<img alt="AI Show Audio Analytics" src="AIShow.jpg" height="400"></a>   
<br><br>
https://aka.ms/AIShow/AudioAnalytics <br>
https://youtu.be/iHL9RmOejdo

  
## Audio Analytics with Azure Presentation<br>
Document is available here:<br>
https://github.com/retkowsky/Audio_Analytics_With_AzureML/blob/main/Audio%20Analytics.pdf

<img src="image.jpg" height = 400>

## Demo: Acoustic Anomaly Detection for Machine Sounds based on Images

### Problem
Is it possible to detect an anomaly (not normal noise) from an equipment or a machine just using a sound file?

### Solution
- We can collect some normal and non-normal (anomaly) sounds files as a training database.
- We can generate spectrograms for all the files for the two categories we want to predict (anomaly / no anomaly).
- We will build and train an image classification model (anomaly / no anomaly) using computer vision algorithms with Azure Custom Vision and Azure AutoML for Images using the spectograms images.
- We can generate audio features and use some usual classification techniques like SVM. We can leverage AutoML Classification features with Azure ML to ensure to find the best model.
- We can deploy the models using these techniques in Azure or on the Edge to test the anomaly detection models we made.

### All the Python notebooks are available

### Azure AutoML
AutoML is an Azure Machine Learning feature, that empowers both professional and citizen data scientists to build machine learning models rapidly. Since its launch, AutoML has helped accelerate model building for essential machine learning tasks like Classification, Regression and Time-series Forecasting.

With the preview of AutoML for Images, there will be added support for Vision tasks. Data scientists will be able to easily generate models trained on image data for scenarios like Image Classification (multi-class, multi-label), Object Detection and Instance Segmentation.

- AutoML for Images documentation: http://aka.ms/AutoMLforImagesDoc
- AutoML for Images Algorithms: http://aka.ms/AutoMLforImagesAlgorithms
- AutoML for Images Tutorial: http://aka.ms/AutoMLforImagesTutorial

### Note
All these Python notebooks were made for demo purposes. They were not designed for production usage. AutoML for Images is currently in public preview. This preview version is provided without a service-level agreement. Certain features might not be supported or might have constrained capabilities. 
For more information, see Supplemental Terms of Use for Microsoft Azure Previews. <br>
https://azure.microsoft.com/en-us/support/legal/preview-supplemental-terms/

25-Oct-2022
Serge Retkowsky | serge.retkowsky@microsoft.com | https://www.linkedin.com/in/serger/
