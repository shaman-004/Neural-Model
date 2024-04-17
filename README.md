# Neural-Model
First Neural Network model working with relationships between x and y<br>

Consider the following sets of numbers. Can you see the relationship between them?<br>
x | -1 | 0 | 1 | 2 | 3 | 4 
--- | --- | --- | --- |--- |---
y | -2 | 1 | 4 | 7 | 10 | 13 
X:

-1

0

1

2

3

4

Y:

-2

1

4

7

10

13

As you read left to right, notice that the X value is increasing by 1 and the corresponding Y value is increasing by 3. So, the relationship should be Y=3X plus or minus some value.

Then, take look at the 0 on X and see that the corresponding Y value is 1.

From both of these observations, you can determine that the relationship is Y=3X+1.

This is almost exactly how you would use code to train a model, known as a neural network, to spot the patterns in the data!

You use data to train the neural network! By feeding it with a set of Xs and a set of Ys, it should be able to figure out the relationship between them.<br><br>

<p>Requirements📐</p><br>

```console
pip install google-cloud-logging
```
```console
pip install ---upgrade protobuf
```
```console
pip install --upgrade tensorflow
```

<br>
<p>Check if TensorFlow is installed. Run the following command in the terminal:</p><br>

```console
python -c "import tensorflow;print(tensorflow.__version__)"
```


