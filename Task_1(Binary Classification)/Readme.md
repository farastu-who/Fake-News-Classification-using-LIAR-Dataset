
## Task 1 - Binary Classification

It is the task of classifying the elements of a given set into two groups (predicting
which group each one belongs to) on the basis of a classification rule.) There are many
classifiers algorithms to use for the different number of predictions, but here we use Random
Forest. and another one is being used is LSTM Classification Keras.

### Random Forest:
Random Forest Classifier is ensemble algorithm. In next one or two
posts we shall explore such algorithms. Ensembled algorithms are those which combines
more than one algorithms of same or different kind for classifying objects. For example,
running prediction over Naive Bayes, SVM and Decision Tree and then taking vote for final
consideration of class for test object.

  * • Here by using Bags of word Technique we are achieving the Accuracy: 63%


### LSTM Classification Keras:
How it Work: A sequence is a set of values where each value corresponds to an observation
at a specific point in time. Sequence prediction involves using historical sequential data
to predict the next value or values. Machine learning models that successfully deal with
sequential data are RNNˆas (Recurrent Neural Networks).
First, to give some context, recall that LSTM are used as Recurrent Neural Networks (RNN).
RNNs are neural networks that used previous output as inputs. We consider that
RNNs has a kind of internal dimension, that will be the dimension of hi vectors. This
dimension is constant over time.

After one fed all inputs xi into the RNN, the last output, ht, is supposed to carry
information about the whole sentence. This is theoretically true, but it shows weakness for
long sequences. Thatˆas what LSTMs tries to solve.
       
 * • Here by using RNN we are achieving the Accuracy: 58%
