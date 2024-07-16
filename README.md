# KNN for the Iris Dataset

## Summary of the KNN Project for the Iris Dataset

This project aims to implement the K-Nearest Neighbors (KNN) algorithm from scratch in Google Colab, without using any external libraries. The implementation is based on the Iris dataset, which includes 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify these samples into three different species of iris.

## Traditional KNN Implementation

The initial implementation of the KNN algorithm was done using traditional methods, without relying on libraries like NumPy. This version allows the classification of five new objects into one of the three classes based on their features.

## Refactored KNN Implementation

The initial KNN implementation was then refactored to improve performance. Several optimization strategies were considered, including:

- Priority Queue
- KD-Tree
- Ball-Tree
- Vectorized implementation with NumPy

## Performance Measurement

Both the traditional and optimized implementations were tested on the Iris dataset. The time taken for classification in each case was measured and compared to evaluate the efficiency gains achieved through optimization.

## Conclusion

The project demonstrates the implementation of the KNN algorithm from scratch, followed by a performance-optimized version. The comparison of the two implementations highlights the improvements in classification time, showcasing the benefits of using advanced data structures or vectorization techniques.
