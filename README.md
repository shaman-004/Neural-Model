# Neural-Model
First Neural Network model working with relationships between x and y<br>

Consider the following sets of numbers. Can you see the relationship between them?<br>
x | #-1 | #0 | #1 | #2 | #3 | #4 
--- | --- | --- | --- |--- |---
y | -2 | 1 | 4 | 7 | 10 | 13 

Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269

As you read left to right, notice that the X value is increasing by 1 and the corresponding Y value is increasing by 3. So, the relationship should be Y=3X plus or minus some value.

Then, take look at the 0 on X and see that the corresponding Y value is 1.

From both of these observations, you can determine that the relationship is Y=3X+1.

This is almost exactly how you would use code to train a model, known as a neural network, to spot the patterns in the data!

You use data to train the neural network! By feeding it with a set of Xs and a set of Ys, it should be able to figure out the relationship between them.<br><br>

<p>Requirements📐</p><br>

```sh
pip install google-cloud-logging
```
```sh
pip install ---upgrade protobuf
```
```sh
pip install --upgrade tensorflow
```

<br>
<p>Check if TensorFlow is installed. Run the following command in the terminal:</p><br>

```sh
python -c "import tensorflow;print(tensorflow.__version__)"
```


