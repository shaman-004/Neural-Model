# Neural-Model👋
First Neural Network model working with relationships between x and y<br>

Consider the following sets of numbers. Can you see the relationship between them?<br>
| x   | -1  | 0   | 1   | 2   | 3   | 4   |
| --- | --- | --- | --- | --- | --- | --- |
| y   | -2  | 1   | 4   | 7   | 10  | 13  |
<br>
<p>As you read left to right, notice that the X value is increasing by 1 and the corresponding Y value is increasing by 3. So, the relationship should be Y=3X plus or minus some value.</p>

<p>Then, take look at the 0 on X and see that the corresponding Y value is 1.

From both of these observations, you can determine that the relationship is Y=3X+1.

This is almost exactly how you would use code to train a model, known as a neural network, to spot the patterns in the data!

You use data to train the neural network! By feeding it with a set of Xs and a set of Ys, it should be able to figure out the relationship between them.</p><br>

<p>Requirements📐:</p><br>

```sh
pip install google-cloud-logging
```
```sh
pip install ---upgrade protobuf
```
```sh
pip install --upgrade tensorflow
```

<p>Check if TensorFlow is installed. Run the following command in the terminal:</p><br>

```sh
python -c "import tensorflow;print(tensorflow.__version__)"
```
<p>Output👁️:</p>
![image](https://github.com/shaman-004/Neural-Model/assets/93532515/ff1f2288-e1d9-40bd-b0d2-87bd5bfc38f7)

