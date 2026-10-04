--- 1. Generation & Memory ---
Shape: (1000, 5)
Initial dtype: float64
Initial memory size (bytes): 40000
float32 memory size (bytes): 20000

--- 2. Standardization ---
Column means: [-0.  0. -0. -0.  0.]
Column stds:  [1. 1. 1. 1. 1.]

--- 3. MinMax Scaling ---
axis=0 min==0: True
axis=0 max==1: True
axis=1 min==0: True
axis=1 max==1: True

--- 4. Missing Values ---
Remaining NaNs count: 0
Confirmation (== 0): True

--- 5. Outlier Replacement ---
Replacements per column: [1 1 2 4 4]

--- 6. Euclidean Distance Matrix ---
Distance matrix shape: (200, 200)
Diagonal is all zeros: True
Matrix equals its transpose: True

--- 7. k-Nearest Neighbors ---
KNN shape: (200, 5)
First row 5-NN indices: [ 35  81 120 184 102]

--- 8. Speed Benchmark ---
NumPy time:   1.214 ms
Python time:  132.845 ms
Speed-up factor: 109.4x

--- 9. Sliding Windows ---
Windows shape: (9991, 10)
Matches pandas rolling mean: True

--- 10. Reshaping ---
Reduced shape: (4, 8)

--- 11. Persistence ---
Assertion passed: clean.npy matches array A exactly.
