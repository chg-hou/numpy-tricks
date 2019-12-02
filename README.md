# numpy-tricks


```python
def myfunc(a):
    print(a)
    return a[0]
vfunc = np.vectorize(myfunc, signature='(m)->()')

vfunc([[1, 2], [3, 4], [5, 6]])

output:
[1 2]
[3 4]
[5 6]
array([1, 3, 5])
```
