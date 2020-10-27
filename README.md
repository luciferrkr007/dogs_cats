# dogs_cats

A model is made using cnn which determines whether the input image is of dog or cat.
Layers in CNN model
1.Conv2D: a basic cnn layer, we are using 64 neurons.

2.Dense :  Dense layer is needed by every neural network 
           to finally output the result however every once in while 
           using a Dense layer helps in making model learn.
3.MaxPooling : CNN has a concept of max pooling. After every 
               convoulution we get some values in a kernel. 
               However in max pooling we select max kernel value.
4.Flatten: Conv2D layer returns doesn't return a flatten
           data hence we need Flatten layer before feeding 
           it into final Dense layer
           
Activation function=relu and softmax
optimizer= Adam
loss=Sparse categorical crossentropy
metrics=Accuracy

