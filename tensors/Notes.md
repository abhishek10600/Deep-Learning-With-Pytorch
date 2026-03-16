## What is tensor ?

- Tensor is a specialized multi-dimensional array designed for mathematical and computational efficiency

## Scalar

- 0 dimensional tensor is called a scalar.
- Example: 2, 3 etc
- Loss Value: After forward pass, the loss function computes a scalar value indicating the difference between the predicted and actual outputs.
- Example: -3.5 or 5.5

## Vectors

- 1 Dimensional tensors are called vectors.
- Examples: Embeddings --> [0.25, 0.98, 0.44]

## Matrices

- 2 Dimensional tensor is called Matrices
- Example: Grayscale image --> [
  [0,255, 128],
  [34, 90, 180]
  ]

## 3D Tensors: Coloured images

## 4D Tensors: Batched of RGB Images

- Adds the batch size as an additonal dimension to 3D data.
- [batch size x width x height x channels]

## 5D Tensors: Video data

- Adds a time dimenstion for data thatr changes over time (e.g video data).
- Example a batch of 10 video clips: each with 16 frames of size 64 X 64 and 3 channels
- [10, 16, 64, 64, 3]

## Where are tensors used in Deep Learning ?

1. Data Storage - Training data are stored in tensors.
2. Weights and Biases - The learnable parameters of neural network are stored in tensors.
3. Matrix Operations - Neural networks involve operation like matrix multiplication, dot products and broadcasting - all performed using tensors.
4. Training process - During forward pass, tensors flow throw the network, Gradient, represented as tensors are calculated during backward pass.
