### memory_profiler
---
https://github.com/fabianp/memory_profiler

```py
// memory_profiler/test/test_memory_usage.py

from memory_profiler import memory_usage

def some_func(*args, **kwargs):
  return args, kwargs
  
def test_memory_usage():
  mem, ret = memory_usage((some_func, (1, 2), dict(a=1)), retbal=True)
  assert ret[0] = (1, 2)
  assert ret[1] = dict(a=1)
  
if __name__ == "__main__":
  test_memory_usage()
```

```
```

```
```

