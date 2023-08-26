
#### Attribute Information:
1.	ID number
2.	Diagnosis (M = malignant, B = benign)

* (3 – 32)
Ten real-valued features are computed for each cell nucleus:
1. radius (mean of distances from center to points on the perimeter)
2. texture (standard deviation of gray-scale values)
3. perimeter
4. area
5. smoothness (local variation in radius lengths)
6. compactness (perimeter^2 / area - 1.0)
7. concavity (severity of concave portions of the contour)
8. concave points (number of concave portions of the contour)
9. symmetry
10. fractal dimension ("coastline approximation" - 1)

* The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
* All feature values are recoded with four significant digits.
#### Missing attribute values: none
#### Class distribution: 357 benign, 212 malignant

### 3.Build and Train model to predict using SVM
Using SVM (Support Vector Machines) we build and train a model using human cell records, and classify cells to predict whether the samples are benign or malignant. 




