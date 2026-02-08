# 📊 Sorting Performance Study

## Project Overview
This project analyzes and compares the performance of multiple sorting algorithms using experimental benchmarking in Python. The study evaluates how execution time changes with increasing input sizes and different dataset characteristics.


## Objectives
- Compare performance of common sorting algorithms
- Analyze scalability with increasing dataset size
- Study differences between theoretical and practical complexity
- Visualize algorithm efficiency using graphs


## Algorithms Implemented
- Bubble Sort
- Selection Sort
- Merge Sort
- Quick Sort
- Python Built-in Sort (Timsort)


## Experiment Methodology

### Dataset Types
- Random Data (Average Case)
- Sorted Data
- Reversed Data (Worst Case)

### Input Sizes Tested
- 100 elements
- 500 elements
- 1000 elements
- 2000 elements

### Performance Metric
- Execution Time (seconds)


## Results & Observations

### Bubble Sort
- Slow performance for large datasets
- Confirms quadratic time complexity O(n²)

### Selection Sort
- Slightly better than Bubble Sort
- Still inefficient for large inputs

### Merge Sort
- Efficient and stable performance
- Demonstrates O(n log n) scalability

### Quick Sort
- Very fast in average cases
- Efficient memory usage
- Performance depends on pivot selection

### Python Built-in Sort
- Fastest overall performance
- Uses Timsort (hybrid of Merge Sort + Insertion Sort)
- Optimized for real-world datasets


## Technologies Used
- Python
- Google Colab
- Matplotlib
- GitHub


## 📂 Project Structure
