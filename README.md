# Audio Analytics with Azure AutoML for Images

Audio processing can consist of extracting audio signal information into spectrograms (time vs frequency vs Db) images that we can use to build a custom vision model with Azure using AutoML for Images. 

We can as well extract some audio components and use a generic classification model with Azure ML and its AutoML features.

## Demo1: Music Genre Prediction

Problem: 
Is it possible to predict the music genre of an audio file?

Solution:
We will build spectrograms for all the training music files
Then we will use these images to build, train and deploy an Image Computer Vision model with AutoML for Images
We will test the model to predict the genre based on an audio file

Demo2: Acoustic Anomaly Detection for Machine Sounds based on Images

Problem: 
Is it possible to detect an anomaly (not normal noise) using a machine sound file?

Solution:
We will collect some normal and anomaly sounds files
We will generate spectrograms for all the files 
We will build and train a two-class classification model (Anomaly vs no anomaly)
We will test the anomaly detection model
