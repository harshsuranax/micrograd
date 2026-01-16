**micrograd (notebook)**

A tiny automatic differentiation engine and toy neural-network library implemented from scratch in Python. This notebook builds a scalar-valued computation graph, performs reverse-mode autodiff (backpropagation), and uses it to train small multilayer perceptrons (MLPs).

**Features**

**Value scalar node with:**

- data (.data), gradient (.grad), and .backward() for reverse-mode autodiff
- operator overloading: + - * / **, tanh, exp, relu, negation, etc.
- Computation graph recording parents and local backward closures.
- Neural nets: Neuron, Layer, MLP with Tanh and exp activations.
- All in one notebook for easy reading and step-through debugging.

**References:**

[Andrej Karpathy's micrograd](https://github.com/karpathy/micrograd)
