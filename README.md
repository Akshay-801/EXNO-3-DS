## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.

STEP 2:Clean the Data Set using Data Cleaning Process.

STEP 3:Apply Feature Encoding for the feature in the data set.

STEP 4:Apply Feature Transformation for the feature in the data set.

STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation

• Reciprocal Transformation

• Square Root Transformation

• Square Transformation

  # 2. POWER TRANSFORMATION
  
• Boxcox method

• Yeojohnson method

# CODING AND OUTPUT:

![alt text](Images/image.png)

![alt text](Images/image-1.png)

## Encoding

### Label Encoding

![alt text](Images/image-2.png)

### Ordinal Encoding

![alt text](Images/image-3.png)

### Binary Encoding

![alt text](Images/image-4.png)

### One Hot Encoding

![alt text](Images/image-5.png)

## Transformation

![alt text](Images/image-6.png)

![alt text](Images/image-7.png)

### Log Transformation

![alt text](Images/image-8.png)

### Reciprocal Transformation

![alt text](Images/image-9.png)

### Square Root Transformation

![alt text](Images/image-10.png)

### Square Transformation

![alt text](Images/image-11.png)

### Box-cox method

![alt text](Images/image-12.png)

### Yeojohnson method

![alt text](Images/image-13.png)

# RESULT:

Data encoding and transformation on the given data is performed successfully. 

       
