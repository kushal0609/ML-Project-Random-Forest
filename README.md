
# Prediction with Random Forest Classifier
***

### Projects:

Project 1: Prediction about the segment or attributes causes high sale in the company.
Project 2: Prediction of the fraud check data.

### Objectives:

Exploring Insights/Inferences by performing EDA on the given data. Relevant graphs were plotted to get some insights on data using seaborn package. Model fitting via Random Forest Classifier by Importing sklearn package. 
***

### Python Libraries Used:
   * Pandas
   * Numpy
   * Matplotlib
   * Seaborn
   * Scikit learn
   * Joblib

***

### Methodology:
 1. Data copying and cleaning:
    * Read the csv file
    * copy the data
    * check for null values and other informations
    * drop the duplicate values
 
 2. Exploratory Data Analysis:
    * Conduct all the necessary EDA using various graphs on the dataset
    * interpret the graphs
    * check for outliers and correlation among the coloumns
    * perform one hot encoding in case of categorical columns

 3. Sampling of data:
    * Divide the data into x and y
    * standardize the data using StandardScaler lib
    * import test_train_split from sklearn.model_selection
    * divide the data into training and testing


  4. Modelling of data:
     * import RandomForestClassifier and initialize it
     * fit the model
     * predict the model

  5. Model validation (Error Calculation):
     * From sklearn.metris import accuracy_score, precision_score, confusion_matrix
     * check the accuracy of the model

  6. Save the Model:
     * import joblib
     * save the model

  ***
  ## Project 1
  ## Company Sales data Probelm: 
  
  *File name: Company-Sales-data files*
  
  #### EDA Inferences:
  * There are total sales of **2942.97** (in thousands).
  * Total sale in US stores is **1986.815**.
  * Total sales in urban areas is **2064.74**.
  * Total sales in US urban area is **1402.05**.
  * Bad, medium and good shelve quality places have **529.815,1591.15 and 822.005** sales: 
  * Medium quality shelving location as more sales followed by good and bad quality.
  * Least sales are observed in case .**of bad shelving location.
  * The data is normally distributed in all the cases.
  * The skewness is calculted to be **0.21, 0.40, 0.05, 0.64, 0.05, 0.44, 0.08 and 0.04** for sales, compprice, income, advertising, population, price, age and education, respectively.
  * The correlation of age and salary with the Iphone purchase is **62 and 38%**, repectively.
  * There are outliers present in the features named Sales, compPrice and price.


 
  #### Random Forest Model Results:
  The accuracy of the model is came out to be:
  
  **Accuracy Score: 0.79**

  **Precision Score:0.83** 
  
***  
  ## Project 2
  ## Fraud Check data Probelm: 
  
  *File name: Fraud-Check-data files*
  
  #### EDA Inferences:
  * There are total **476** and **124** individuals with good and risky status, respectively.
  * Soem of them are married, divorced and single individuals.
  * There are large number of Single(**174**) individuals who have good status, followed by divorced(**153**) and married(**149**).
  * There are large number of married (**45**) individuals who have risk status, followed by single(**43**) and divorced(**36**).
  * Graduation status (Undergrad) and location (Urban) does not give any impactful data on the tax criteria i.e good and risky status.
  * The data is normally distributed in all the features.
  * The skewness is calculted to be **0.03, 0.13 and 0.02** for taxable income, city population and work experience, respectively.
  * There are no outliers present in the dataset


 
  #### Random Forest Model Results:
  The accuracy of the model is came out to be:
  
  **Accuracy Score: 0.81**

  
***  


## Contribution

Still Learning,

So feel free, Anything You wanna contirubute.

***
       
      
     
     
     

