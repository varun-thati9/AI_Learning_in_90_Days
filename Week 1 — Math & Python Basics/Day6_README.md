# ✅ Day 6 – Linear Algebra: Vectors, Matrices, Dot Product

Welcome to Day 6 of your learning journey! This module introduces key concepts in **Linear Algebra** using Python and NumPy. You'll work with vectors, matrices, and operations like dot product, matrix multiplication, and more advanced topics like eigenvalues and SVD.

---

## 🟢 Beginner Level

### ✅ Basic Vector and Matrix Operations
1. Create a vector using NumPy: `v = [2, 4, 6]`. Print its shape and dimension.
2. Create a `3x3` identity matrix using `np.eye()`.
3. Create two matrices and perform **addition** and **subtraction**:
   ```python
   A = [[1, 2], [3, 4]]
   B = [[5, 6], [7, 8]]

4. Multiply a matrix by a scalar value (e.g., 2 * A).

5. Transpose a given matrix using .T.

6. Check whether a given matrix is symmetric.

7. Create a zero vector of length 5 and a ones vector of length 5 using np.zeros() and np.ones().

🟡 Mid Level
✅ Intermediate Matrix and Vector Computations
1. Perform matrix multiplication between two 2x2 matrices using np.dot() or @.

2. Compute the dot product of two vectors: a = [1, 2, 3], b = [4, 5, 6].

3. Compute the magnitude (norm) of a vector v = [3, 4] using np.linalg.norm().

4. Find the determinant of a 2x2 and 3x3 matrix using np.linalg.det().

5. Calculate the inverse of a matrix (if it exists) using np.linalg.inv().

6. Solve a system of linear equations:

2
𝑥
+
𝑦
=
5

𝑥
−
𝑦
=
1
 using np.linalg.solve().

7. Create a random 4x4 matrix using np.random.rand() and find its trace using np.trace().

🔴 Advanced Level
✅ Deep Linear Algebra Concepts
1. Compute the eigenvalues and eigenvectors of a square matrix using np.linalg.eig().

2. Verify the matrix property:

(
𝐴
⋅
𝐵
)
𝑇
=
𝐵
𝑇
⋅
𝐴
𝑇
 for two random matrices.

3. Perform Singular Value Decomposition (SVD) of a matrix using np.linalg.svd().

4. Show that the dot product of two orthogonal vectors is zero.

5. Write a function to compute the Gram-Schmidt orthogonalization process.

6. Implement a function to check if a matrix is positive definite.

7. Use NumPy to simulate a 2D rotation matrix by angle 
𝜃
 and rotate a vector.
