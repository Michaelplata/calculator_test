# Python built-in functions

In this lesson we will have a look at some of Python built-in functions that will simplify our code making it cleaner and easier to read and in same scenarios, even faster.

### any()

The **any()** function returns **True** if any element of an iterable is **True**. If not, it returns **False**.

>
**Syntax**
>
```Python
any(iterable)
```
>
**Example**
>
```Python
boolean_list = ['True', 'False', 'True']
>
# check if any element is true
result = any(boolean_list)
print(result)
>
# Output: True
```

The **any()** function takes an iterable (_list, dictionary, string etc_) in Python and return one of the following boolean values:

- `True` if at least one element of the iterable is true.
- `False` if all elements are false or if the iterable is empty.

```Python
numbers = [10, 20, 30, 40, 50]
print(any(20)
# Output: True
      
print(any(60)
# Output: False

```