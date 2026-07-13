NumPy arrays are the main data structure used for working with collections of values efficiently in Python. You create one by calling `np.array()` and passing in a sequence such as a list or tuple.

```py-cell
import numpy as np

my_array = np.array([1, 2, 3])
```

The resulting array stores the values in a form that NumPy can use for later numerical operations.

# Printing Arrays

You can print a NumPy array in the same way as other Python values.

```py-cell
print(my_array) # Print our NumPy array

print([1, 2, 3]) # Print a list for comparison
```

Notice that NumPy prints the array without commas between the values, while a Python list includes commas. That makes it easier to tell the two types apart when they are displayed.