---
sidebar_position: 1
---

When you want to use kylink data in your local environment, you must install kylink package with pip:

```bash
pip install kylink
```

When you are not in kylink platform, it is required to manually initialze the KyLink instance with your API Key

```python
from kylink import Kylink

kylink = kylink(api=cXXXXXXXXX)

```

