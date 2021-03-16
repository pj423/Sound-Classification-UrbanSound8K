# Sound-Classification-UrbanSound8K

Implementation of Sound Classifier using Convolutional Neural Networks (CNNs) on [UrbanSound8K Dataset](https://urbansounddataset.weebly.com/ "UrbanSound8K"), which contains a environmental sounds, each having a duration of 4 seconds. There are 8732 labeled slices (8.75 hours of audio).
There are a total of 10 sound classes in the dataset:
1. Air Conditioner
2. Car Horn
3. Children Playing
4. Dog Bark
5. Drilling
6. Engine Idling
7. Gun Shot
8. Jackhammer
9. Siren
10. Street_music

## Preparation Of Data
The library Librosa is used to load the audio files and also extract the features out of the audio files. It is also making the sampling rate uniform across all audio clips and making the number of channels to be one (mono). Mel Spectrogram is used for the features of the audio files, and is input to the CNN.



