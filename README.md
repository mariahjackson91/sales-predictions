# Sales Predictions
# This project is to predict item outlet sales in various supermarkets/stores
# Author: Mariah Jackson
# Problem: 
 To understand the data as it relates to the products and outlets that play crucial roles in increasing sales.

# Here is the Data Dictionary for this dataset:

     ## Variable Name Description
     ## Item_Identifier Uniquep roduct ID
     ## Item_Weight	Weight of product
     ## Item_Fat_Content	Whether the product is low fat or regular
     ## Item_Visibility	The percentage of total display area of all products in a store allocated to the particular product
     ## Item_Type	The category to which the product belongs
     ## Item_MRP	Maximum Retail Price (list price) of the product
     ## Outlet_Identifier	Unique store ID
     ## Outlet_Establishment_Year	The year in which store was established
     ## Outlet_Size	The size of the store in terms of ground area covered
     ## Outlet_Location_Type	The type of area in which the store is located
     ## Outlet_Type	Whether the outlet is a grocery store or some sort of supermarket
     ## Item_Outlet_Sales	Sales of the product in the particular store. This is the target variable to be predicted.
   
   # Steps: 
     ## Part 1
     ### Use Pandas to read in the sales prediction data set into a Google Colab Notebook and verify the data by using the df.head() command.
     ## Part 2
     ### Use Pandas to start cleaning and exploring the data.
     ## Part 3
     ### Complete any statistical analyses that help understand, explain, or model with the data. Includes one of each:
          Histogram to view the distributions of various features in your dataset.
          Boxplot to view statistical summaries of various features in your dataset.
          Heatmap of the correlation between features.
     ## Part 4
     ### Build several data visualizations to help your stakeholders better understand trends in the data.
     ## Part 5
     ### Use machine learning to make predictions about future sales based on the data provided.
           Identify the features (X) and target (y): Assign the "Item_Outlet_Sales" column as the target and the rest of the relevant variables as the features matrix. 
           Perform a train test split 
           Create a preprocessing object to prepare the dataset for Machine Learning
    ## Part 6
    ### Build a linear regression model to predict sales.
      Build a linear regression model.
      Evaluate the performance of the model based on r^2.
      Evaluate the performance of the model based on rmse.
    ### Build a regression tree model to predict sales.
      Build a simple regression tree model.
      Compare the performance of the model based on r^2.
      Compare the performance of the model based on rmse.
   
    ## Part 7
      Compare models
   
      
   
      
      
        
