# Project 1 Generative Text

Yifan Hou, yihou@ucsd.edu


## Abstract

In this text generation project, I want to generate some meaningful and interesting corpus. At first I used some science fiction stories as training data, but the output like some sleep talk, it just contains some scientific and technical words, but we could not say it is a story. Due to the GPU is limited, it is hard to generate a whole story. So I change the training data, and choose short jokes as training data. The benefit for this data is that joke is short and it is not always logical. The joke generated by machine might give us some suprise. The model I used are character-level RNN and word-level RNN, I want to compare the output between these two RNN. 


## Model/Data

- training model is chara-level-RNN model and word-level-RNN model.
- training data is short jokes https://www.kaggle.com/abhinavmoudgil95/short-jokes


## Code


Your code for generating your project:
- training_code.py or training_code.ipynb - your training code
- generative_code.py or generative_code.ipynb - your generation code

## Results
- I use these different 2 model generate 5 text.
- The batch size is bellow.

- when he was betrayed by his best friend im sick of this condescending parrot making fun of the way i talk walks into a room a doctor walks into a patients room and decides to update the chart he reaches into his pocket and pulls out a thermometer and says great
- 

## Technical Notes

- My code requires TensorFlow, NumPy and keras . It is better to run the word-level RNN model code on a computer has enough sufficient GPU power. Otherwise, It will take a long time to run. 

## Reference

References to any papers, techniques, repositories you used:
- Papers
  - [This is a paper](this_is_the_link.pdf)
- Repositories
- Blog posts https://github.com/hunkim/word-rnn-tensorflow

