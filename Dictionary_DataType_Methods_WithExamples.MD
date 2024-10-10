Dictionaries in Python are mutable, unordered collections of key-value pairs. They provide several methods for adding, removing, and manipulating key-value pairs. Below is the list of dictionary methods, followed by explanations and examples for each.

### List of `dict` Methods
1. `clear()`
2. `copy()`
3. `fromkeys()`
4. `get()`
5. `items()`
6. `keys()`
7. `pop()`
8. `popitem()`
9. `setdefault()`
10. `update()`
11. `values()`

### Explanation and Examples

#### 1. `clear()`
Removes all key-value pairs from the dictionary.

```python
d = {'a': 1, 'b': 2, 'c': 3}
d.clear()
print(d)  # Output: {}
```

#### 2. `copy()`
Returns a shallow copy of the dictionary.

```python
d = {'a': 1, 'b': 2}
copy_d = d.copy()
print(copy_d)  # Output: {'a': 1, 'b': 2}
```

#### 3. `fromkeys(iterable, value=None)`
Creates a new dictionary with keys from the provided iterable and all values set to the specified value (default is `None`).

```python
keys = ['a', 'b', 'c']
d = dict.fromkeys(keys, 0)
print(d)  # Output: {'a': 0, 'b': 0, 'c': 0}
```

#### 4. `get(key, default=None)`
Returns the value for the given key. If the key is not found, it returns the `default` value (which is `None` if not specified).

```python
d = {'a': 1, 'b': 2}
value = d.get('b')
print(value)  # Output: 2
missing_value = d.get('c', 'Not Found')
print(missing_value)  # Output: Not Found
```

#### 5. `items()`
Returns a view object that displays a list of dictionary's key-value pairs (as tuples).

```python
d = {'a': 1, 'b': 2}
items = d.items()
print(items)  # Output: dict_items([('a', 1), ('b', 2)])
```

#### 6. `keys()`
Returns a view object displaying a list of all the keys in the dictionary.

```python
d = {'a': 1, 'b': 2}
keys = d.keys()
print(keys)  # Output: dict_keys(['a', 'b'])
```

#### 7. `pop(key[, default])`
Removes and returns the value for the given key. If the key is not found, it raises a `KeyError` unless the `default` value is provided.

```python
d = {'a': 1, 'b': 2}
value = d.pop('a')
print(value)  # Output: 1
print(d)  # Output: {'b': 2}
```

#### 8. `popitem()`
Removes and returns the last key-value pair added to the dictionary as a tuple. Raises a `KeyError` if the dictionary is empty.

```python
d = {'a': 1, 'b': 2}
item = d.popitem()
print(item)  # Output: ('b', 2)
print(d)  # Output: {'a': 1}
```

#### 9. `setdefault(key, default=None)`
Returns the value of the specified key. If the key doesn't exist, it inserts the key with the `default` value and returns the `default`.

```python
d = {'a': 1}
value = d.setdefault('b', 2)
print(value)  # Output: 2
print(d)  # Output: {'a': 1, 'b': 2}
```

#### 10. `update([other])`
Updates the dictionary with elements from another dictionary or an iterable of key-value pairs. Existing keys are overwritten.

```python
d = {'a': 1}
d.update({'b': 2, 'c': 3})
print(d)  # Output: {'a': 1, 'b': 2, 'c': 3}
```

#### 11. `values()`
Returns a view object displaying a list of all the values in the dictionary.

```python
d = {'a': 1, 'b': 2}
values = d.values()
print(values)  # Output: dict_values([1, 2])
```

These are the main methods available for the `dict` data type in Python, each accompanied by examples demonstrating how they work.