+++
title = "Autodidax: JAX core from scratch"
date = 2022-12-27
+++


Generators 

```python
def f(x):
    y = sin(x) * 2. 
    z = -y + x 
    return z 
```

```python 
from typing import NamedTuple

class Primitive(NamedTuple):
  name: str

add_p = Primitive('add')

def add(x, y): return bind1(add_p, x, y)
```

```python
def bind1(prim, *args, **params):
  out, = bind(prim, *args, **params)
  return out
```

