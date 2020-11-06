# DeepSpace

A collection of search space for the DeepHyper package.

## Requirements

Graphviz.

## Quick Start

```python
from deepspace.tabular import DenseSkipCoFactory

def create_search_space(input_shape=(54,), output_shape=(7,), num_layers=10, dropout=0.0):
    return DenseSkipCoFactory(**locals()).create_space()
```
