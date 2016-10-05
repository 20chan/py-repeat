# py-repeat
✨Super simple function which repeats function execution in python3.

Usage
-----
```python
repeat(func, args)(times)
```
`func` is a function to repeat, `args` is tupled arguments.

Example
-
```python
repeat(print, 'hi')(10) # print hi 10 times
repeat(print, ('Hello', end=', '))(10) # print 'Hello,' 10 times
```
