# AI Audio Classifier

## Background: 

 

The recent emergence of AI technologies has been a disruptive and transformative force in many industries. Deep learning models like ‘Diff-SVC’ and ‘MusicLM’ allow for producers and songwriters to use the voices of their favorite artists, and these new creations are flooding the internet on streaming platforms like YouTube and SoundCloud. The music industry currently finds itself at a crossroads where some artists embrace the transformative effect of AI, with many even licensing their voices, while others, out of concern for their intellectual property, resort to filing copyright claims. 

 

## Overview: 

 

These new advances necessitate a system that can recognize artificially generated tracks. This system can both benefit streaming services and protect artists by automatically identifying illegal and copyrighted content. 

 

Key questions we want to investigate: 

Are there telltale signs of when AI is present in audio? 

What distinct differences are there between authentic and AI-generated music? 

 


 

 

 

 

 

 

 

 

 

 

 

 

 

 

## Procedure: 

 

Start by identifying artists whose voices are being used the most and gather a training sample using both authentic songs and AI generated songs for those artists so we can extract key audio features. Although we might not be able to quantify these, some factors to keep in mind include lyrics, tone, and a lack of emotion or nuance.  

 

We can use the Python package ‘pytube’ to download YouTube videos in bulk and convert the .wav data into the frequency domain or another suitable format. We will implement a neural network (most likely CNN) using PyTorch or TensorFlow, feed it our pre-processed data, and perform binary classification to determine if a given song is AI generated.  

 

We will investigate other open source and freely available datasets as needed. 

 

## Future Work: 

 

The next phase of this project is to use NLP and analyze song lyrics to detect the presence of AI as another way to bolster our predictions. These models can be compared to each other to see which kind of analysis (on lyrics or on music) yields more accurate predictions. A potential stretch goal would be to incorporate the lyrics into the main data as another data column to be analyzed in conjunction with the sound wave data. 
