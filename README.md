# Python Data Type Methods

This repository contains a comprehensive overview of the methods available for Python's built-in data types: Lists, Sets, Tuples, and Dictionaries. Each section includes a list of methods along with brief descriptions.

## Contents

- [Lists](#lists)
- [Sets](#sets)
- [Tuples](#tuples)
- [Dictionaries](#dictionaries)

## Lists

Lists are mutable, ordered collections of items. Below are the methods available for lists:

1. **`append(x)`**: Adds an element `x` to the end of the list.
2. **`extend(iterable)`**: Extends the list by appending elements from another iterable.
3. **`insert(index, x)`**: Inserts an element `x` at the specified position `index`.
4. **`remove(x)`**: Removes the first occurrence of element `x`.
5. **`pop([index])`**: Removes and returns the element at the specified `index`.
6. **`clear()`**: Removes all elements from the list.
7. **`index(x[, start[, end]])`**: Returns the index of the first occurrence of element `x`.
8. **`count(x)`**: Returns the number of occurrences of element `x`.
9. **`sort(key=None, reverse=False)`**: Sorts the list in ascending order.
10. **`reverse()`**: Reverses the elements of the list.
11. **`copy()`**: Returns a shallow copy of the list.

## Sets

Sets are mutable, unordered collections of unique items. Below are the methods available for sets:

1. **`add(x)`**: Adds an element `x` to the set.
2. **`update(iterable)`**: Updates the set by adding elements from another iterable.
3. **`remove(x)`**: Removes the element `x` from the set.
4. **`discard(x)`**: Removes element `x` if present, without raising an error.
5. **`pop()`**: Removes and returns an arbitrary element from the set.
6. **`clear()`**: Removes all elements from the set.
7. **`union(*others)`**: Returns a new set with elements from the set and all other sets.
8. **`intersection(*others)`**: Returns a new set with elements common to the set and all other sets.
9. **`difference(*others)`**: Returns a new set with elements in the set that are not in the other sets.
10. **`symmetric_difference(other)`**: Returns a new set with elements in either set, but not in both.
11. **`issubset(other)`**: Returns `True` if the set is a subset of the other set.
12. **`issuperset(other)`**: Returns `True` if the set is a superset of the other set.
13. **`isdisjoint(other)`**: Returns `True` if the set has no elements in common with `other`.
14. **`copy()`**: Returns a shallow copy of the set.

## Tuples

Tuples are immutable, ordered collections of items. Below are the methods available for tuples:

1. **`count(x)`**: Returns the number of occurrences of element `x`.
2. **`index(x[, start[, end]])`**: Returns the index of the first occurrence of element `x`.

## Dictionaries

Dictionaries are mutable, unordered collections of key-value pairs. Below are the methods available for dictionaries:

1. **`clear()`**: Removes all key-value pairs from the dictionary.
2. **`copy()`**: Returns a shallow copy of the dictionary.
3. **`fromkeys(iterable, value=None)`**: Creates a new dictionary with keys from the provided iterable.
4. **`get(key, default=None)`**: Returns the value for the given key, or `default` if not found.
5. **`items()`**: Returns a view object that displays a list of dictionary's key-value pairs.
6. **`keys()`**: Returns a view object displaying a list of all the keys in the dictionary.
7. **`pop(key[, default])`**: Removes and returns the value for the given key.
8. **`popitem()`**: Removes and returns the last key-value pair added to the dictionary.
9. **`setdefault(key, default=None)`**: Returns the value of the specified key, inserting the key with `default` if not found.
10. **`update([other])`**: Updates the dictionary with elements from another dictionary or iterable.
11. **`values()`**: Returns a view object displaying a list of all the values in the dictionary.

## Usage

You can refer to the code examples in the code files of this repository for practical demonstrations of each method. Feel free to explore and contribute to the repository!

## License

This project is licensed under the MIT License.
