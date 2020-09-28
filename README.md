# vh_challenge_sol
 vision health challenge, audio crow classifier challenge for Vision Health


## Files
Main project:   
Solution.ipynb

Trainin Data is stored in:   
./Data/dataset/audio

A cvs explaining the dataset can be found in:   
./Data/dataset/esc50

## How to:
Open solutions notebook
run all cells up to Train header:

## Todo
Prediction:
- Check the rooster_competition.wav files is located in main working project './'   
- Change final_model_path to desired .hdf   

Prediction should return a batch of 10ms samples
check if samples is rooster
add samples if rooster
crowing.length = Sum(samples)*.01 seconds

Count rooster length:


## Reference
 https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53
 https://towardsdatascience.com/getting-to-know-the-mel-spectrogram-31bca3e2d9d0

**Environmental Sound Classification on Microcontrollers using Convolutional Neural Networks**
 https://github.com/jonnor/ESC-CNN-microcontroller/blob/f7a02189e18cc845dd4e912654a2509215475410/microesc/urbansound8k.py#L91
  **Audio Classification with Machine Learning (EuroPython 2019)**
 https://www.youtube.com/watch?v=uCGROOUO_wY&ab_channel=JonNordby

 **Deep Learning for Audio Classification (kapre version)**(https://www.youtube.com/playlist?list=PLhA3b2k8R3t0SYW_MhWkWS5fWg-BlYqWn)

 [Seth Adams](https://www.youtube.com/user/seth8141)
