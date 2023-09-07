---
sidebar_position: 2
---

The root object kylink is a util lib for interacting/virtualizing on the Kylink Platform.

## `kylink.image`

```python
#!pip: ["matplotlib"]

import os
import base64
from io import BytesIO

import matplotlib.pyplot as plt

# Plot
fig, ax = plt.subplots()
ax.plot([1,3,2])

kylink.image(plt)
```

## `kylink.table`

```python
kylink.table([
    {"name": "Alice", "age": 18},
    {"name": "Bob", "age": 21}
])
```
