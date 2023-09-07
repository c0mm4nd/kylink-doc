---
sidebar_position: 1
---

## On Kylink Platform

You dont need to do any installation, everything is ready.

## On Local Python Env

When you want to use kylink data in your local environment, you must install `kylink` package with `pip`:

```bash
pip install kylink
```

When you are **NOT** in kylink platform, it is required to manually initialze the Kylink instance with your API Key

```python
from kylink import Kylink

kylink = kylink(api=cXXXXXXXXX)

```

