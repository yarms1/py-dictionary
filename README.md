# Custom dict

- Read [the guideline](https://github.com/mate-academy/py-task-guideline/blob/main/README.md) before start


Let's create your own class `Dictionary` and implement methods:
- `__setitem__(self, key, value)` 
- `__getitem__(self, key)` 
- `__len__(self)`

Be attentive to basic requirements for the implementation of the dictionary (initial capacity, load factor, resize ...)

Notes: 
- you can implement other methods of the dict interface (both regular and magic):
  - `clear`
  - `__delitem__`
  - `get`
  - `pop`
  - `update`
  - `__iter__`
- you can test `Dictionary` with custom class `Point` that has `__hash__` and `__eq__` magic methods.