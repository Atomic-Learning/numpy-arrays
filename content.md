NumPy arrays are a data structure commonly used for working with collections of values in Python. NumPy arrays are efficient and provide many useful methods for performing numerical operations on the data they contain.

One way to create a NumPy array is to call `np.array()`{.python} and passing in a sequence such as a list or tuple.

```py-cell
import numpy as np

my_array = np.array([1, 2, 3])

print(my_array)
```

The resulting array stores the values in a form that NumPy can use for later numerical operations.

Note that once an array has been created, its size cannot change. In the example above `my_array`{.python} has a size of 3, and it will always have a size of 3. If you want to add or remove values from an array, the closest thing you can do is to create a new array.