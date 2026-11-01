CUDA Parallel Programming

This repository contains CUDA C/C++ programs implemented as part of GPU and parallel computing laboratory experiments.

📚 Programs Included

1. Vector Addition – Adds two vectors in parallel using CUDA.
2. Parallel Reduction – Calculates the sum of array elements using parallel reduction.
3. Inclusive Prefix Sum – Computes cumulative sums including the current element.
4. Exclusive Prefix Sum – Computes prefix sums excluding the current element.
5. Parallel Merging – Merges two sorted arrays into a single sorted array.
6. List Ranking – Calculates the rank of each node in a linked-list representation.
7. Sparse Matrix Addition – Adds two matrices containing mostly zero elements.
8. Parallel Sorting – Sorts array elements using parallel odd-even sort.

🛠️ Technologies Used

* Language: CUDA C/C++
* Platform: Kaggle Notebooks
* GPU: NVIDIA T4
* Compiler: NVIDIA CUDA Compiler (nvcc)

🚀 How to Run

1. Open the notebook in Kaggle with GPU acceleration enabled.
2. Write the CUDA program into a .cu file.
3. Compile the program using:

!nvcc program.cu -o program

4. Execute the compiled program:

!./program

Replace program.cu and program with the appropriate filenames.

🎯 Objective

The objective of these experiments is to understand fundamental GPU programming concepts, CUDA memory management, thread execution, and parallel algorithms.

👨‍💻 Author

Created as part of GPU and Parallel Computing laboratory practice.
