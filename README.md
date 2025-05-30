# Audio Classifier Project

source: https://www.tensorflow.org/tutorials/audio/simple_audio

I based my final project around audio processing and classification. The source listed above provided a dataset and general framework for me to build my project off of. I utilized many of the visualization and processing methods used in the above example but I performed my own exploratory analysis given the prior. I explored the effects of different processing techniques and different models on audio data while also learning more about the hyperparameters that govern these models. 

I was able to produce a model that was able to classify the data with nearly 90% accuracy and utilize this model to process realtime data from an available microphone. If I had more time and more processing power, I would have tested more complex architecture to try and improve the accuracy but I am limited by the constraints of my laptop. Overall, I am happy with the results and gained a lot of insight into the process of how more complex models are trained and designed.


The file Command_Recognition.ipynb is the main file that contains my research and analysis of audio processing.

The file RealTimeCommands.ipynb is a simple script I wrote to test the functionality of my final model that takes in real time audio data from a connected mic. It performs reasonably well but it does not perform well with rapid sequences of commands which I would like to improve.

The final model iteration has been saved to the 'saved' folder for use in other projects.
