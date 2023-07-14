
# Char RNN next-word-prediction-using-nlp-and-lstm


Minimalist code for character-level language modelling using Multi-layer Recurrent Neural Networks (LSTM) in keras. The RNN is trained to predict next letter in a given text sequence. The trained model can then be used to generate a new text sequence resembling the original data.

## Requirements

Trained and tested on:

- `Python 3.6`
- `keras 2.10.1`
- `NumPy 1.16.3`

## Usage

### Training
To train a new network run `CharRNN.py`. If you are using custom data, change the `data_path` and `save_path` variables accordingly. To keep the code simple the batch size is one, so the training procedure is a bit slow. The average loss and a sample from the model is printed after every epoch.

### Testing
To test a preTrained network (~15 epochs) run `test.py`. The training dataset is required for testing, to create vocabulary dictionary, and also for sampling a random small (10 letters) text sequence to begin generation.

## Samples

**Shakespeare Dataset (~ 15 epochs) :**
```
DOCSER:
What, will thy fond law?
or that in all the chains that livinar?

KING HENRY V:
Come, come, I should our name answer'd for two mans
To deafly upbrain, and broke him so our
Master Athital. Mark ye, I say!

B-CANSSIO:
Come, let us die.

Hostes:
This was my prince of holy empress,
That shalt thou save you in it with brave cap of heaven.
Or is the digest and praud with their closets save of faitral'?

KING HENRY V:
Your treason follow Ncpius, Dout &ystermans' clent,
On the pity can, when tell them
Freely from direen prisoners town; and let us
know the man of all.
