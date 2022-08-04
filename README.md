# Python-AI-model

But first, what is a neural network? The human brain consists of 100 billion cells called neurons, connected together by synapses. If sufficient synaptic inputs to a neuron fire, that neuron will also fire. We call this process “thinking”.

![Screenshot_4](https://user-images.githubusercontent.com/40389694/182826673-c3004351-eebf-4670-9cb8-6e2317c9f435.png)
![Screenshot_3](https://user-images.githubusercontent.com/40389694/182826713-970c73e8-707f-489f-839c-e5dea5180269.png)

We can model this process by creating a neural network on a computer. It’s not necessary to model the biological complexity of the human brain at a molecular level, just its higher level rules. We use a mathematical technique called matrices, which are grids of numbers. To make it really simple, we will just model a single neuron, with three inputs and one output.

## Training process

But how do we teach our neuron to answer the question correctly? We will give each input a weight, which can be a positive or negative number. An input with a large positive weight or a large negative weight, will have a strong effect on the neuron’s output. Before we start, we set each weight to a random number. Then we begin the training process:

Take the inputs from a training set example, adjust them by the weights, and pass them through a special formula to calculate the neuron’s output.
Calculate the error, which is the difference between the neuron’s output and the desired output in the training set example.
Depending on the direction of the error, adjust the weights slightly.
Repeat this process 10, 000 times.

![Screenshot_5](https://user-images.githubusercontent.com/40389694/182826947-70b4c93c-5489-444a-bdb5-50e939fe725f.png)


## Constructing the Python code

We will import four methods from a Python mathematics library called numpy. These are:

- exp — the natural exponential
- array — creates a matrix
- dot — multiplies matrices
- random — gives us random numbers

## Output
```
Random starting synaptic weights:
[[-0.16595599]
[ 0.44064899]
[-0.99977125]]
```

```
New synaptic weights after training:
[[ 9.67299303]
[-0.2078435 ]
[-4.62963669]]
```
```
Considering new situation [1, 0, 0] -> ?:
[ 0.99993704]
```
