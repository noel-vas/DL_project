# DL_Assignment Hemant D 4NI20IS043
Topic: Tangent Distance

Tangent Distance is a concept used in machine learning, particularly in the field of pattern recognition and classification. It is a distance metric that measures the dissimilarity between two objects in a feature space. Tangent Distance is often employed in conjunction with tangent vectors, which represent the local geometry of data points in the feature space.

Here's a brief overview:

1. Tangent Vectors:
   - Tangent vectors are calculated to approximate the local geometry of a data point in the feature space. They capture the shape of the data distribution around that point.

2. Tangent Distance Metric:
   - Tangent Distance is a distance metric defined based on the tangent vectors. It measures the dissimilarity between two data points by considering the difference in their local geometry.

3. Applications:
   - Tangent Distance is commonly used in the context of shape analysis, object recognition, and classification tasks.
   
   - It is particularly useful when dealing with deformable shapes or when the inherent geometry of the data is crucial for accurate classification.

4. Advantages:
   - Tangent Distance provides a way to incorporate local information about the data distribution, which can be beneficial in scenarios where global features alone may not be sufficient.
   
   - It can enhance the robustness of classifiers, especially when dealing with variations in shape or appearance.

5. Challenges:
   - The effectiveness of Tangent Distance depends on the appropriate calculation of tangent vectors, which may require careful consideration of the data representation and feature space.

6. Mathematical Formulation:
   - The Tangent Distance between two data points x and y is often calculated as the Euclidean distance between their tangent vectors: TangentDistance (x, y) = || T_x - T_y ||
     where T_x and T_y are the tangent vectors at points x and y respectively.

In summary, Tangent Distance is a technique that leverages local geometric information to measure dissimilarity between data points. It finds applications in scenarios where understanding the shape or local structure of data is essential for effective machine learning tasks.
