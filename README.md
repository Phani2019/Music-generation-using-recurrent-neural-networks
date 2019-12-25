# Music-generation-using-recurrent-neural-networks



# Real World Problem

This Project focuses on generating music automatically using Recurrent Neural Network(RNN). We do not necessarily have to be a music expert in order to generate music. Even a non expert can generate a decent quality music using RNN. We all like to listen interesting music and if there is some way to generate music automatically, particularly decent quality music then it's a big leap in the world of music industry. 
# Task
Our task here is to take some existing music data then train a model using this existing data. The model has to learn the patterns in music that we humans enjoy. Once it learns this, the model should be able to generate new_ music for us. It cannot simply copy-paste from the training data. It has to understand the patterns of music to generate new music. We here are not expecting our model to generate new music which is of professional quality, but we want it to generate a decent quality music which should be melodious and good to hear. Now, what is music? In short music is nothing but a sequence of musical notes. Our input to the model is a sequence of musical events/notes. Our output will be new sequence of musical events/notes. In this case-study we have limited our self to single instrument music as this is our first cut model. In future, we will extend this to multiple instrument music.
# Data Source:
1.http://abc.sourceforge.net/NMD/

2.http://trillian.mit.edu/~jc/music/book/oneills/1850/X/

From first data-source, we have downloaded the first file
* Jigs (340 tunes)

# How to Run the Model



# How to Generate Music Sequence

# Type of Data:

# Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.

1.Python 3
2.Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
3.keras


# Installing
1.Python 3: https://www.python.org/downloads/
2.Anaconda: https://www.anaconda.com/download/
3.Keras: pip install keras


# Built With
* ipython-notebook - Python Text Editor
* numpy, scipy- number python library
* pandas - data handling library
* Keras - Deep Learning Library


# Authors
* Phanindra kumar
# References
* https://folkrnn.org/
* https://en.wikipedia.org/wiki/ABC_notation
* https://abcjs.net/abcjs-editor.html
* https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
* http://karpathy.github.io/2015/05/21/rnn-effectiveness/
* https://medium.com/artists-and-machine-intelligence/neural-nets-for-generating-music-f46dffac21c0
