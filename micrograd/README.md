### important resourcs:
- https://en.wikipedia.org/wiki/Hyperbolic_functions
- for tensors https://docs.pytorch.org/docs/2.13/tensors.html ( basic multi-dimensional array properties to contrast PyTorch's highly optimized, vectorized tensor-level operations against micrograd's basic, individual python scalar floats.)
- for autograd: https://docs.pytorch.org/docs/2.13/autograd.html ( He points out this package to explain how PyTorch dynamically tracks operations on tensors when requires_grad=True )
- backward : https://docs.pytorch.org/docs/2.13/generated/torch.Tensor.backward.html (the exact method he discusses for executing the backward pass. He uses it to show how PyTorch calculates gradients of a tensor with respect to graph leaves using the chain rule, mirroring the custom .backward() method created in micrograd)
