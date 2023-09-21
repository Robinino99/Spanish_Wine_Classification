# Spanish_Wine_Classification
Classification exercise on the Spanish Wine Dataset. To classify which wine variant will have the relevant body type. 
## 

**Robin Abrahams**: 

### Business problem:
We had been tasked to evaluate and classify the body type of the various wine brands, across regions and prices.


### Data:
This included the 
* winery
* rating
* Outlet Type
* Location of Stores 
* Item Outlet Type

## Methods
We applied standard dataprocessing techniques:
* Feature evaluation
* Data Cleaning (duplicate removal/inconsistency correction)
* Developed a Model Data Pipeline(s) (numeric & categorical)
* ColumnTransformer
* Train_Test_Split
* Applied a Logistic Regression Model
* Applied a K Nearest Neighbors Model
* Applied a Decision Tree Classifier Model

## Results

### Here are examples of how to embed images from your sub-folder


#### Correlation Heatmap
![image](https://github.com/Robinino99/Spanish_Wine_Classification/assets/138812946/c27947e0-09f4-4c2a-93ee-fe8a712b2c0a)

Standard heatmap to determine which features correlated the most. As we can see from the above heatmap, price and rating features were strongly correlated. 

#### Exploratory Visual of the Rating vs Price feature

![image](https://github.com/Robinino99/Prediction-of-Product-Sales/assets/138812946/1f4c8f72-675f-4448-9aa8-3abeddcc8ca5)

The above chart further visualizes the relationship of rating to price. 

#### A brief visual of the Top 5 Regions Avg Price

![image](https://github.com/Robinino99/Spanish_Wine_Classification/assets/138812946/3cd4a3ef-f256-4f24-8ec5-ad93f32dc97b)


### Model(s) implemented

Based on the classification exercise, we opted to train, evaluate and test the following three models:
* Logistic Regression
* KNN
* Decision Tree Classifier

### Metrics
* Logistic pre tune:
![image](https://github.com/Robinino99/Spanish_Wine_Classification/assets/138812946/f392a8b0-accf-4a8f-acb9-da20b52a1e40)

* Logistic post tune:
  ![image](https://github.com/Robinino99/Spanish_Wine_Classification/assets/138812946/7237bf03-7b19-421b-9232-04718c28d790)



## Recommendations:
Additionally, another sampling method could be applied to lessen the data to balance it. I opted for class_weights for my models.


## Limitations & Next Steps

* To further improve the models and their predictions, the dataset could increase in size in future.

### For further information


For any additional questions, please contact **email**
