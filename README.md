# dotdict
Very lite override of dict to access values using dot operator

```python
>>> d = dotdict({"val0": "hello", "val1": "world"})
>>> d["val0"]
'hello'
>>> d.val0
'hello'
>>> d.val2 = "!"
>>> d
{'val0': 'hello', 'val1': 'world', 'val2': '!'}
```