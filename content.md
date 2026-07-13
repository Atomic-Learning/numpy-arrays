NumPy arrays are a data structure commonly used for working with collections of values in Python. NumPy arrays are efficient and provide many useful methods for performing numerical operations on the data they contain.

NumPy is not including in the Python Standard Library, so you must install it using a tool such as `pip` before using it. You will then need to import it into your code before you can use it. It is conventional to give NumPy the alias `np` when importing it. This helps with brevity and readability when using NumPy functions in your code.

```py-cell
import numpy as np
```

One way to create a NumPy array is to call `np.array()` and passing in a sequence such as a list or tuple.

```py-cell
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