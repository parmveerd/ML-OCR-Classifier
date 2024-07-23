# CMPT 310 Classifier Project

In this project, you will design three classifiers: a naïve Bayes Classifier, a perceptron classifier, and a large-margin (MIRA) classifier. You will test these classifiers on a set of scanned handwritten digit images. Even with simple features, your classifiers will be able to do quite well on these tasks when given enough training data.

Optical character recognition (OCR) is the task of extracting text from image sources. The data set on which you will run your classifiers is a collection of handwritten numerical digits (0-9). This is a very commercially useful technology, like the technique used by the US post office to route mail by zip codes. There are systems that can perform with over 99% classification accuracy (see LeNet-5 for an example system in action).

Files:

digitdata: Data file, including the digit images

naiveBayes.py: The location where you will write your naive Bayes classifier.

perceptron.py: The location where you will write your perceptron classifier.

mira.py: The location where you will write your MIRA classifier.

dataClassifier.py: The wrapper code that will call your classifiers. You will also write your enhanced feature extractor here. You will also use this code to analyze the behavior of your classifier.

answers.py: Answer to Question 2 goes here.
 
classificationMethod.py: Abstract super class for the classifiers you will write. (You should read this file carefully to see how the infrastructure is set up.)

samples.py: I/O code to read in the classification data.

util.py: Code defining some useful tools. You may be familiar with some of these by now, and they will save you a lot of time.

mostFrequent.py: A simple baseline classifier that just labels every instance as the most frequent class.