# **Audio MNIST Digit Recognition**

---------------------
## **Context**
---------------------

Significant progress has been made in the field of audio recognition in recent decades, and extensive research is being conducted worldwide to use deep learning to recognise speech or audio data. In this field, translating audio to spectrograms and vice versa is the most frequent use case.

In its most basic form, audio is typically represented as a wave, and even for brief audio clips, we require a wide range of amplitudes to represent that in a data structure. This structured data conversion for any audio wave is highly voluminous, even at modest sampling rates, however it depends on the sound wave's sampling rate. As a result, even basic computations on such data become computationally expensive and difficult to store.

A cost-effective substitute for this is the use of spectrograms. Fourier or Short Time Fourier Transforms applied to sound waves yield spectrograms. While there are many different types of spectrograms, we will be utilising MFCC spectrograms. A spectrogram, to put it simply, is a visual representation of audio data. This is a two-dimensional graph with time on the X-axis and Mel Coefficients on the Y-axis. However, we can treat this as an image because it is continuous on a two-dimensional plane.



---------------------
## **Objective**
---------------------

The goal is to create an artificial neural network capable of classifying audio files into ten groups based on their Mel or MFCC spectrograms. The audio files contain recordings of various individuals pronouncing a specific digit; the digit itself is the matching class that needs to be predicted.


---------------------
## **Dataset**
---------------------

The dataset we will use is the **Audio MNIST dataset**, which has audio files (having .wav extension) stored in 10 different folders. Each folder consists of these digits spoken by a particular speaker.
