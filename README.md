# WyGen: music genre classifier
Convolutional Neural Network that classifies different genres of music

Based on the AlexNet architecture, the network consists of 3 convolutional layers, and 2 fully-connected layers, classifying music into 10 different genres (Blues, Classical, Country, Disco, Hip-Hop, Jazz, Metal, Pop, Rock, and Reggae). 
With an accuracy of 63.7% it is not state-of-the-art(6 genres:accuracy of 84%,250 genres: 93.6%).

UPDATE:
I tried a few more different architectures and I hope to try out a few more soon.

| Architecture | Accuracy |
|--------------|----------|
| AlexNet      | 63.7     |
| SqueezeNet   | 64       |
| ResNet34     | 84.5     |
| ResNet50     | 85       |

### Future Changes
* Adding an LSTM (or another derivative recurrent neural net) layer that helps capture the sequential nature of music.
* Train and test on more data.
