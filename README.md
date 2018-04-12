# python_notes
`*`  and `**` in passing function argument
```
args = (1, 2, 3)  # usually a tuple, always an iterable[1]

f(*args) → f(1, 2, 3)

# and 

kwargs = {"a": 1, "b": 2, "c": 3}  # usually a dict, always a mapping*

f(**kwargs) -> f(a=1, b=2, c=3)
```
