# py-repeat
✨Super simple function repeating in python3.

HowTo
-
```python
repeat(func, args)(times)
```
`func` is function to repeat, `args` is tupled arguments.

Example
-
```python
repeat(print, 'hi')(10) # print hi 10 times
repeat(print, ('Hello', end=', '))(10) # print 'Hello,' 10 tiems
```
