# Project 3 within Deep Learning Nanodegree @Udacity 

## Task
In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using part of the Seinfeld dataset of scripts from 9 seasons. The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.
(copied from project description)

## My solution
Please check the Jupyter notebook with the instructions and implementation [here](dlnd_tv_script_generation.ipynb).

The implementation uses LSTM cells to mitigate the Vanishing Gradient Problem. The embedding dimension and other hyperparameters are inspired by leading researchers such as Bengio (2012) or Hochreiter & Schmidhuber (1997).  

During implementation phase I have compared self-trained word embeddings and pretrained word vectors from the GloVe project (https://nlp.stanford.edu/projects/glove/).
The variant with the pretrained word vectors resulted in a slightly bigger loss and less natural sentence generation.
**As a consequence the variant with self-trained word embeddings is used.**

## Excerpt from generated script

```
george: i know.

jerry: well, i'm sure!

george:(to the phone) : i know, you don't have to meet in this night of that.

jerry: i want to say with this new little party on my little one idea. and if i think i just get a life- hands- front- homeless- hand. jerry, 
i just have like the wheelchair from a life on the door of front by a minute, you just got a life like a party of the door of a lot of pressure to body, he doesn't them to be in the doubt thing just made him to him him the lot of a little minute, then you had a life on the party to a party of a party of my hands has this whole supreme place, then doesn't get them out to the supreme behind the little thing- they do it in the car?
...

```
