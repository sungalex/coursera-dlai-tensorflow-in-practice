# Time Series - Week 4 Quiz

1. How do you add a 1 dimensional convolution to your model for predicting time series data?

   - [X] Use a Conv1D layer type
   - [ ] Use a Convolution1D layer type
   - [ ] Use a 1DConv layer type
   - [ ] Use a 1DConvolution layer type

2. What’s the input shape for a univariate time series to a Conv1D? 

   - [X] [None, 1]
   - [ ] []
   - [ ] [1, None]
   - [ ] [1]

3. You used a sunspots dataset that was stored in CSV. What’s the name of the Python library used to read CSVs?

   - [ ] PyCSV
   - [ ] PyFiles
   - [ ] CommaSeparatedValues
   - [X] CSV

4. If your CSV file has a header that you don’t want to read into your dataset, what do you execute before iterating through the file using a ‘reader’ object?

   - [ ] reader.next
   - [X] next(reader)
   - [ ] reader.ignore_header()
   - [ ] reader.read(next)

5. When you read a row from a reader and want to cast column 2 to another data type, for example, a float, what’s the correct syntax?

   - [X] float(row[2])
   - [ ] You can’t. It needs to be read into a buffer and a new float instantiated from the buffer
   - [ ] float f = row[2].read()
   - [ ] Convert.toFloat(row[2])

6. What was the sunspot seasonality?

   - [X] 11 or 22 years depending on who you ask
   - [ ] 11 years
   - [ ] 22 years
   - [ ] 4 times a year

7. After studying this course, what neural network type do you think is best for predicting time series like our sunspots dataset?

   - [ ] DNN
   - [ ] RNN / LSTM
   - [ ] Convolutions
   - [X] A combination of all of the above

8. Why is MAE a good analytic for measuring accuracy of predictions for time series?

   - [ ] It punishes larger errors
   - [ ] It only counts positive errors
   - [ ] It biases towards small errors
   - [X] It doesn’t heavily punish larger errors like square errors do
