# chdir

`chdir` is a tiny Python library for setting the current working directory to the location of a Python script.

## Why? 

When writing Python scripts, you might be tired of doing this:

```python
import os

os.chdir(os.path.dirname(os.path.abspath(__file__)))
```

With `chdir`, you can do this:

```python
import chdir

chdir.here(__file__)
```
