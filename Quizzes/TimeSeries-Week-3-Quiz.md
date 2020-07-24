# Time Series - Week 3 Quiz

1. If X is the standard notation for the input to an RNN, what are the standard notations for the outputs?

   - [ ] Y
   - [ ] H
   - [X] Y(hat) and H
   - [ ] H(hat) and Y

2. What is a sequence to vector if an RNN has 30 cells numbered 0 to 29

   - [X] The Y(hat) for the last cell
   - [ ] The Y(hat) for the first cell
   - [ ] The total Y(hat) for all cells
   - [ ] The average Y(hat) for all 30 cells

3. What does a Lambda layer in a neural network do?

   - [ ] There are no Lambda layers in a neural network
   - [ ] Pauses training without a callback
   - [X] Allows you to execute arbitrary code while training
   - [ ] Changes the shape of the input or output data

4. What does the axis parameter of tf.expand_dims do?

   - [X] Defines the dimension index at which you will expand the shape of the tensor
   - [ ] Defines the dimension index to remove when you expand the tensor
   - [ ] Defines the axis around which to expand the dimensions
   - [ ] Defines if the tensor is X or Y

5. A new loss function was introduced in this module, named after a famous statistician. What is it called?

   - [ ] Hubble loss
   - [ ] Hawking loss
   - [ ] Hyatt loss
   - [X] Huber loss

6. What’s the primary difference between a simple RNN and an LSTM

   - [X] In addition to the H output, LSTMs have a cell state that runs across all cells
   - [ ] LSTMs have a single output, RNNs have multiple
   - [ ] LSTMs have multiple outputs, RNNs have a single one
   - [ ] In addition to the H output, RNNs have a cell state that runs across all cells

7. If you want to clear out all temporary variables that tensorflow might have from previous sessions, what code do you run?

   - [ ] tf.keras.clear_session
   - [X] tf.keras.backend.clear_session() 
   - [ ] tf.cache.backend.clear_session()
   - [ ] tf.cache.clear_session()

8. What happens if you define a neural network with these two layers?

    ~~~python
    tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),
    tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),
    tf.keras.layers.Dense(1),
    ~~~

   - [ ] Your model will fail because you need return_sequences=True after each LSTM layer
   - [ ] Your model will compile and run correctly
   - [X] Your model will fail because you need return_sequences=True after the first LSTM layer
   - [ ] Your model will fail because you have the same number of cells in each LSTM
