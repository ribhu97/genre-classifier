# WyGen: music genre classifier
Convolutional Neural Network that classifies different genres of music

Based on the AlexNet architecture, the network consists of 3 convolutional layers, and 2 fully-connected layers, classifying music into 10 different genres (Blues, Classical, Country, Disco, Hip-Hop, Jazz, Metal, Pop, Rock, and Reggae). 
With an accuracy of 63.7% it is not state-of-the-art(6 genres:accuracy of 84%), but it performs well above the 10% chance.

### Future Changes
* Adding an LSTM (or another derivative recurrent neural net) layer that helps capture the sequential nature of music.
* Add 1-2 more convolutional layers to capture even lower level features.
* Train and test on more data.
