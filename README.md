# Dry Beans Classification Project

The Dry Bean Classification project is a supervised machine learning initiative designed to accurately classify different types of dry beans based on a set of measurable physical features. The project utilizes a structured dataset containing morphological and geometrical attributes derived from images of dry bean seeds, which are used to distinguish between seven distinct bean cultivars. These cultivars include Seker, Barbunya, Bombay, Cali, Horoz, Sira, and Dermosan—all of which have unique agricultural and nutritional characteristics.The dataset used for this project is sourced from 
 
## 📊 Dataset Information

The dataset used in this project is the **Dry Bean Dataset**, originally provided by the [Uci Data Repository](https://archive.ics.uci.edu/dataset/602/dry+bean+dataset). It contains a total of **13,611 samples** representing **seven different types of dry beans**, with each sample described by **13 numerical features** derived from digital image processing.

This dataset serves as a benchmark for testing multiclass classification models in the agricultural domain, where physical characteristics of objects—such as shape, area, and contour—are used for automatic categorization.

### 🫘 Target Classes (Bean Types)

Each sample belongs to one of the following seven bean varieties:

- **Seker**
- **Barbunya**
- **Bombay**
- **Cali**
- **Dermosan**
- **Horoz**
- **Sira**

These classes represent cultivars commonly grown in Turkey and surrounding regions, each with different visual and physical characteristics relevant for sorting, packaging, and export purposes.

### 📐 Feature Descriptions

The 13 features included in the dataset are numerical values that describe various **shape, size, and structural properties** of the beans. All features are continuous and have been extracted from bean images using image analysis techniques.

| Variable Name     |  Description   | 
|-------------------|----------------|
| Area              | The area of a bean zone and the number of pixels within its boundaries.                        | 
| Perimeter         | Bean circumference is defined as the length of its border.                                     |        
| MajorAxisLength   | The distance between the ends of the longest line that can be drawn from a bean.               |   
| MinorAxisLength   | The longest line that can be drawn from the bean while standing perpendicular to the main axis.| 
| AspectRatio       | Defines the relationship between MajorAxisLength and MinorAxisLength.                          |       
| Eccentricity      | Eccentricity of the ellipse having the same moments as the region.                             |       
| ConvexArea        | Number of pixels in the smallest convex polygon that can contain the area of a bean seed.      | 
| EquivDiameter     | Equivalent diameter: The diameter of a circle having the same area as a bean seed area.        |
| Extent            | The ratio of the pixels in the bounding box to the bean area.                                  |
| Solidity          | Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.  |
| Roundness         | Calculated with the following formula: (4piA)/(P^2).                                           |        
| Compactness       | Measures the roundness of an object.                                                           | 
| ShapeFactor1      |                                                                                                |       
| ShapeFactor2      |                                                                                                |     
| ShapeFactor3      |                                                                                                |       
| ShapeFactor4      |                                                                                                |       
| Class             | Target  |  (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira)                           |  


## 🏁 Evaluation and Results

This study explored the classification of dry bean types using a variety of machine learning algorithms, including K-Nearest Neighbors (KNN), Gaussian Naive Bayes, Logistic Regression, Support Vector Machine (SVM), Random Forest, and Decision Tree. Each model was evaluated using metrics such as accuracy, precision, recall, and F1-score.  The findings highlight the potential of machine learning in agricultural applications, particularly in automating the classification process with high reliability and efficiency. This project serves as a foundation for future improvements, such as hyperparameter tuning, feature selection, or integration into real-time systems.
