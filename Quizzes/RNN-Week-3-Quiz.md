# RNN - Week 3 Quiz

1. Why does sequence make a large difference when determining semantics of language?

   - [X] Because the order in which words appear dictate their impact on the meaning of the sentence
   - [ ] It doesn’t
   - [ ] Because the order in which words appear dictate their meaning
   - [ ] Because the order of words doesn’t matter

2. How do Recurrent Neural Networks help you understand the impact of sequence on meaning?

   - [ ] They shuffle the words evenly
   - [ ] They look at the whole sentence at a time
   - [X] They carry meaning from one cell to the next
   - [ ] They don’t

3. How does an LSTM help understand meaning when words that qualify each other aren’t necessarily beside each other in a sentence?

   - [X] Values from earlier words can be carried to later ones via a cell state
   - [ ] They don’t
   - [ ] They shuffle the words randomly
   - [ ] They load all words into a cell state

4. What keras layer type allows LSTMs to look forward and backward in a sentence?

   - [X] Bidirectional
   - [ ] Unilateral
   - [ ] Bilateral
   - [ ] Bothdirection

5. What’s the output shape of a bidirectional LSTM layer with 64 units?

   - [ ] (None, 64)
   - [ ] (128,None)
   - [X] (None, 128)
   - [ ] (128,1)

6. When stacking LSTMs, how do you instruct an LSTM to feed the next one in the sequence?

   - [ ] Do nothing, TensorFlow handles this automatically
   - [ ] Ensure that return_sequences is set to True on all units
   - [X] Ensure that return_sequences is set to True only on units that feed to another LSTM
   - [ ] Ensure that they have the same number of units

7. If a sentence has 120 tokens in it, and a Conv1D with 128 filters with a Kernal size of 5 is passed over it, what’s the output shape?

   - [ ] (None, 120, 124)
   - [X] (None, 116, 128)
   - [ ] (None, 116, 124)
   - [ ] (None, 120, 128)

8. What’s the best way to avoid overfitting in NLP datasets?

   - [ ] Use LSTMs
   - [ ] Use GRUs
   - [ ] Use Conv1D
   - [X] None of the above
