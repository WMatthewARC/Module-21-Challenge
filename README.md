# Module-21-Challenge

## Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

* **EIN** and **NAME**—Identification columns
* **APPLICATION_TYPE**—Alphabet Soup application type
* **AFFILIATION**—Affiliated sector of industry
* **CLASSIFICATION**—Government organization classification
* **USE_CASE**—Use case for funding
* **ORGANIZATION**—Organization type
* **STATUS**—Active status
* **INCOME_AMT**—Income classification
* **SPECIAL_CONSIDERATIONS**—Special consideration for application
* **ASK_AMT**—Funding amount requested
* **IS_SUCCESSFUL**—Was the money used effectively


### Step 1: Preprocess the Data
![image001](https://user-images.githubusercontent.com/30300016/201495591-fcd7e05c-92d3-42fa-90c3-7c6309970c23.JPG)

![Capture](https://user-images.githubusercontent.com/30300016/201495593-0427054c-aa9d-4a86-9dc2-27d6d7eda012.JPG)

![Capture02](https://user-images.githubusercontent.com/30300016/201495614-b3f9edf1-152d-46ef-bcd4-604999277f73.JPG)

![Capture 03JPG](https://user-images.githubusercontent.com/30300016/201495618-f33192c8-06f5-4274-8cff-4505c088ff7c.JPG)

### Step 2: Compile, Train, and Evaluate the Model

![Capture04](https://user-images.githubusercontent.com/30300016/201495625-c0fd3a3d-90d0-4f44-a6b2-06233c7688a4.JPG)
![Capture05](https://user-images.githubusercontent.com/30300016/201495629-c3675a01-52c8-401d-bd50-714432ebf1b9.JPG)
![Capture06](https://user-images.githubusercontent.com/30300016/201495637-c0964640-7ac5-41dc-99bc-96c2fcb20525.JPG)

1. **Overview** of the analysis: Explain the purpose of this analysis.
   I saw I came I written a model to help see weather campaign where successful and the model seems fairly accurate.

2. **Results**: Data Preprocessing
    * What variable(s) are the target(s) for your model?
    AFFILIATION	CLASSIFICATION	USE_CASE	INCOME_AMT	SPECIAL_CONSIDERATIONS	ASK_AMT	IS_SUCCESSFUL are all used. Anything that would be considered as a variable in that campaign and whether it was successful.
   
    * What variable(s) are the features for your model?
    AFFILIATION	CLASSIFICATION	USE_CASE	INCOME_AMT	SPECIAL_CONSIDERATIONS	ASK_AM
    
    * What variable(s) should be removed from the input data because they are neither targets nor features?
    EIN	NAME	ORGANIZATION	NAME

* Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
       3 see in the images above.
    * Were you able to achieve the target model performance?
       Yes 75%
    * What steps did you take in your attempts to increase model performance?
        Adjust what variables to use and how much weight to give them settled on 45 

thank you for your time. 
Matt-- 
