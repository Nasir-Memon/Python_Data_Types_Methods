In Python, the `list` data type provides several methods that allow you to manipulate lists. Below is a comprehensive list of all the standard methods for lists, followed by an explanation and example for each method.

### List of `list` Methods
1. `append()`
2. `extend()`
3. `insert()`
4. `remove()`
5. `pop()`
6. `clear()`
7. `index()`
8. `count()`
9. `sort()`
10. `reverse()`
11. `copy()`

### Explanation and Examples

#### 1. `append(x)`
Adds an element `x` to the end of the list.

```python
lst = [1, 2, 3]
lst.append(4)
print(lst)  # Output: [1, 2, 3, 4]
```

#### 2. `extend(iterable)`
Extends the list by appending all the elements from the iterable (like another list or a tuple).

```python
lst = [1, 2, 3]
lst.extend([4, 5])
print(lst)  # Output: [1, 2, 3, 4, 5]
```

#### 3. `insert(index, x)`
Inserts an element `x` at the specified position `index`.

```python
lst = [1, 2, 3]
lst.insert(1, 'a')
print(lst)  # Output: [1, 'a', 2, 3]
```

#### 4. `remove(x)`
Removes the first occurrence of the element `x` from the list. Raises a `ValueError` if `x` is not in the list.

```python
lst = [1, 2, 3, 2]
lst.remove(2)
print(lst)  # Output: [1, 3, 2]
```

#### 5. `pop([index])`
Removes and returns the element at the given position `index`. If no index is specified, it removes and returns the last item in the list.

```python
lst = [1, 2, 3]
removed_item = lst.pop(1)
print(removed_item)  # Output: 2
print(lst)  # Output: [1, 3]
```

#### 6. `clear()`
Removes all elements from the list.

```python
lst = [1, 2, 3]
lst.clear()
print(lst)  # Output: []
```

#### 7. `index(x[, start[, end]])`
Returns the index of the first occurrence of the element `x`. You can also specify the search range using `start` and `end` arguments.

```python
lst = [1, 2, 3, 2]
index_value = lst.index(2)
print(index_value)  # Output: 1
```

#### 8. `count(x)`
Returns the number of occurrences of the element `x` in the list.

```python
lst = [1, 2, 3, 2]
count_value = lst.count(2)
print(count_value)  # Output: 2
```

#### 9. `sort(key=None, reverse=False)`
Sorts the list in ascending order by default. You can pass the `key` parameter to customize the sorting and `reverse=True` to sort in descending order.

```python
lst = [3, 1, 2]
lst.sort()
print(lst)  # Output: [1, 2, 3]
lst.sort(reverse=True)
print(lst)  # Output: [3, 2, 1]
```

#### 10. `reverse()`
Reverses the elements of the list in place.

```python
lst = [1, 2, 3]
lst.reverse()
print(lst)  # Output: [3, 2, 1]
```

#### 11. `copy()`
Returns a shallow copy of the list.

```python
lst = [1, 2, 3]
copy_lst = lst.copy()
print(copy_lst)  # Output: [1, 2, 3]
```

These are all the methods for Python's `list` data type, each accompanied by a practical example.