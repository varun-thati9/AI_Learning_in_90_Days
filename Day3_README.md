# ✅ Day 3 – NumPy: Arrays, Indexing, Reshaping

---

## 🟢 Beginner Level
(Understand basic array creation and operations)

1. Create a 1D NumPy array with values from 0 to 9.  
2. Create a NumPy array filled with zeros, ones, and a custom constant (e.g., 7).  
3. Create a 2D array of shape `(3, 3)` with numbers from 1 to 9.  
4. Extract the first 3 elements from a 1D array.  
5. Given an array `[10, 20, 30, 40, 50]`, access the last two elements.  
6. Slice the 2D array below to extract only the first two rows:  
   ```python
   arr = np.array([[1,2,3],[4,5,6],[7,8,9]])
   ```  
7. Reshape a 1D array of 12 elements into a 3x4 2D array.  

---

## 🟡 Mid Level
(Apply indexing, slicing, reshaping in problem-solving)

1. Create an array of even numbers from 2 to 20.  
2. Generate a 4x4 identity matrix using NumPy.  
3. Create a 3x3 matrix with random integers between 1 and 20. Find the max, min, and their indices.  
4. Replace all odd numbers in a NumPy array with `-1`.  
5. Given a 1D array of 25 numbers, reshape it into a 5x5 matrix and extract the 2nd row.  
6. Stack two arrays vertically and horizontally:  
   ```python
   a = np.array([1,2,3])
   b = np.array([4,5,6])
   ```  
7. Flatten a 2D array into a 1D array.  

---

## 🔴 Advanced Level
(More complex reshaping, fancy indexing, boolean masking)

1. Create a 5x5 matrix of random numbers and extract the diagonal elements.  
2. Given a 4x4 matrix, replace the second column with all 0s.  
3. Create a 10x10 matrix with values from 1 to 100, then extract all even numbers using boolean indexing.  
4. Given:  
   ```python
   arr = np.arange(1, 17).reshape(4,4)
   ```  
   - Extract the sub-matrix:  
     ```
     [[6,7],
      [10,11]]
     ```  
5. Create a 6x6 array and reshape it into a 3D array of shape `(2,3,6)`.  
6. Use advanced indexing to pick elements at positions `(0,0), (1,1), (2,2), (3,3)` from a 2D array.  
7. Create a random array of size 20 and sort it in ascending and descending order.  
