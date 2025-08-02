NumPy Basics Practice Project

This is a foundational practice project for learning NumPy, focusing on array creation, manipulation, transformation, and mathematical operations. It’s designed to strengthen my numerical computing skills as a core step in preparing for data science and machine learning.

📌 Project Goals

Understand how to use NumPy effectively
Create and manipulate arrays of different dimensions
Learn key array attributes (shape, dimension, data type, size, etc.)
Perform common operations: slicing, indexing, broadcasting, mathematical operations, logical comparisons, sorting
Learn how to reshape and transform arrays (reshape, transpose, dot product, etc.)

📚 Topics Covered

✅ Array Creation
1D, 2D, and 3D arrays
Arrays of all ones and zeros (np.ones, np.zeros)
Arrays with specified ranges (np.arange, np.linspace)
Random arrays (np.random.randint, np.random.random, np.random.randn)
✅ Array Properties
.shape, .ndim, .dtype, .size, type()
✅ Array Transformations
.reshape(), .T (transpose), np.dot() (dot product)
✅ Array Arithmetic
Element-wise operations: addition, subtraction, multiplication, division, power, np.square()
Aggregation: np.mean, np.max, np.min, np.var, np.std
✅ Logical Comparisons
Comparisons: >, <, ==, !=, >=, <=
Find positions with np.argmax, np.argmin, np.argsort
✅ Sorting and Searching
np.sort(), np.argsort(), np.unique()
✅ Interoperability with Pandas
Convert NumPy arrays to Pandas DataFrames

⚠️ Error Handling Examples

I intentionally caused errors to better understand dimension mismatches and how to fix them. For example:
# Error Example
array1 = np.ones((5, 3))
array2 = np.random.randint(0, 10, size=(3, 5))
array1 + array2  # Error: shape mismatch

🧠 Key Takeaways

Developed a strong grasp of array shapes and broadcasting mechanics
Learned how to generate various types of numerical data for analysis
Gained hands-on experience with NumPy operations in preparation for real-world data tasks

🔜 Next Steps

Explore advanced indexing and broadcasting in NumPy
Practice using NumPy alongside Pandas and Matplotlib
Expand this practice into a real data cleaning or feature engineering mini-project
