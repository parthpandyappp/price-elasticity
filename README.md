## Introduction to the problem statement
Conglomerate Inc., has a variety of brands under it's umbrella which includes Diapers, Headphones and Breakfast cereals. In order to understand the effect of price elasticity on a categorial basis, they want to run promotional campaigns, this will eventually help them to strengthen their promotional strategy. The first and the forremost motive is to analyze the impact of price on product demand for different products and product categories. At last, a statistical report should be generated to visualize the data, and understand the patterns.

## Understanding Datasets and Data exploration.
The given file for the dataset contains Tab Separated values containing the data for per day price and sale of a particular product. In the dataset, we're provided with _Item Id, Average Price_, _Date_, and _Units sold_. A total of _462000_ entities are provided, including Diapers, Headphones, and Cereals as categories.

As we can see from the data below, there are different IDs for different categories, but even there are other IDs at the item level. For instance, let's consider _Diapers_ category, there are _110000_ entities in total where there are only _100_ unique Item IDs, _1100_ of each kind.

  ### Column wise dataset description
  ![image](https://user-images.githubusercontent.com/34797335/188852032-0a10fcc0-500f-4777-a757-7447e964d74c.png)

  ### No. of unique IDs
  ![image](https://user-images.githubusercontent.com/34797335/188852333-c60dbe0e-bb86-4466-b1d7-ec52d0032fe7.png)
  
  ### Item level data distribution
  ![image](https://user-images.githubusercontent.com/34797335/188852842-303f7069-f58b-451b-b052-dffa63539ebc.png)
  
  ### Grouped data in accordance with a particular unique item id
  ![image](https://user-images.githubusercontent.com/34797335/188853117-a54d186f-0572-422e-aefb-d0b80eb6f9b6.png)



## Data Visualization

  ### Scatter Plot
  As we know from the Data exploration stage that we've different data at the item level too as we've different item ID's, To draw the relation between _Units sold_ and _Average price_ and to undertstand the trends associated with a particular `item_id` we'll derive a scattered plot of _Average price_ against _Units sold_ and do the further analysis.
  
  #### Instance plot for item_id _D9775_ for Diapers
  ![image](https://user-images.githubusercontent.com/34797335/188853292-497114a0-17d3-4029-b63f-40bb3b66652d.png)

  
 ### Ordinary least square estimation
 To estimate the unknown parameters other than the average price we'll use this linear regression technique i.e. the ordinary least sqaure estimation.
 
 #### Instance OLS regression result
 ![image](https://user-images.githubusercontent.com/34797335/188854199-4c0e58ab-70f2-4a9d-ada4-132736c917e2.png)

