#Image Morphing for Mini Batches in DNN

![An example for morphing: each row is a different digit.](https://github.com/kyzn/MiniBatchImageMorphing/raw/master/0 Example/Example.png)

As part of UCSC - CS218 "Deep Learning" class, we wanted to work on possible ways to improve our test accuracy. One idea was to introduce more images to mini-batches. We did it by creating new images. 

This code is based on [https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/README.md](Michael Nielsen's code), which uses MNIST dataset. We also used the same data.

To get the data file, please right click and save [https://github.com/mnielsen/neural-networks-and-deep-learning/raw/master/data/mnist.pkl.gz](mnist.pkl.gz).


##Results

|                     | Min Test Cost | Max Test Accuracy |
| ------------------- | ------------- | ----------------- |
| Benchmark           | **0.6108**    | **97.00%**        |
| With Image Morphing |   1.3728      |   95.07%          |


##License

Please visit [https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/README.md](https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/README.md) for license details of *Code samples for "Neural Networks and Deep Learning"*.
