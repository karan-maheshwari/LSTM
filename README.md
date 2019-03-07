# LSTM
Train an LSTM to mimic Bertrand Russell's writing style
</br>
</br>
a) Concatenate text files to create a corpus of Russell’s writings.
</br>
</br>
b) Useed character-level representation for this model by using extended ASCII that has N = 256 characters.
</br>
</br>
c) Used window size of 100 (predicting 100th letter using previous 99 letters)
</br>
</br>
d) Using a Single Hidden Layer, a drop-out layer, and a softmax output layer.
</br>
</br>
e) Training the model for 15 epochs.
</br>
</br>
f) Result:
</br> - We can see how the LSTM is repeating the words, this can mean:
</br> - The number of books were less
</br> - The number were epcohs were less
</br> - On using more of both of the above, we can definitely get better results
