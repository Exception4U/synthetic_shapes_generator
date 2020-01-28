## Synthetic shapes generator

#### API

```python
from synthetic_shapes import SyntheticShapes
config = {
    'primitives': 'all',
    'on-the-fly': True,
    'preprocessing': {
        'resize': [240, 320],
        'blur_size': 11,
    }
}
dataset = SyntheticShapes(**config)
data = dataset.get_test_set()
```
Also test_classical_detectors.ipynb can be used to refer.
