0. The Max method
```py
def Max(arr):
    maximum = arr[0]
    for i in range(len(arr)):
        if arr[i] > maximum:
            maximum = arr[i]
    return maximum
```
can be simplified into this:
```py
def Max(arr):
    maximum = arr[0]
    for x in arr:
        if x > maximum:
            maximum = x
    return maximum
```

1. This dot_product1 function 
```py
def dot_product1(arr1, arr2):
    dot_product = 0
    if len(arr1) != len(arr2):
        return "Not equal lengths"
    for i in range(len(arr1)):
        dot_product += arr1[i]*arr2[i]
    return dot_product
```
can also be simplified using zip function [see details](https://www.w3schools.com/python/ref_func_zip.asp)
```py
def dot_product1(arr1, arr2):
    if len(arr1) != len(arr2):
        return "Not equal lengths"
    dot_product = 0
    for (x,y) in zip(arr1,arr2):
        dot_product += x*y
    return dot_product
```
