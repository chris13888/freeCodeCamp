---
title: Python's Enumerate Function
---

## Overview
In python, one useful function is the `enumerate` function. This function is greatly helpful when looping over an iterable; like a list or iterator. It returns an enumerate object, which can be used in a `for` loop

## Arguments
`enumerate()` takes in an iterable as an argument, as well as an optional `start` to define at which number the indexing should start.

## Return Value
An enumerate object. If you call `list()` on it, you can see that it has multiple tuples in it, with the first value being the index, and the second being the item.

## Usage Examples
    animals = ['cat', 'dog', 'rabbit', 'fox', 'wolf'] # A list of animals.
    for index, item in enumerate(animals, start=20):
      print(index, item)
      
### Output:
    20 cat
    21 dog
    22 rabbit
    23 fox
    24 wolf

<a href='https://repl.it/@StuffsExplained/pythonZipFunction'>Try it out!</a>
