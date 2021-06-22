# Attention-Model
This is a an image to text generation project where the model generates text based on the image given. Here the final model takes an image as input and generates a text as output.
The data is taken from -  https://www.kaggle.com/adityajn105/flickr8k. Encoder Decoder architecture has been used in this project. The encoder is a CNN model which generates feature vectors.
An attention model generates different output at different timesteps from these feaute vectors . This output combined with the previous hidden state from the previous timetep
of the RNN in decoder goes as input to the decoder. The decoder produces the whole sentence with start and end tag. 
