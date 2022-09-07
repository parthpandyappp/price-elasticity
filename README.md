## Introduction to the problem statement
Conglomerate Inc., has a variety of brands under it's umbrella which includes Diapers, Headphones and Breakfast cereals. In order to understand the effect of price elasticity on a categorial basis, they want to run promotional campaigns, this will eventually help them to strengthen their promotional strategy. The first and the forremost motive is to analyze the impact of price on product demand for different products and product categories. At last, a statistical report should be generated to visualize the data, and understand the patterns.

## Understanding Datasets and Data exploration.
The given file for the dataset contains Tab Separated values containing the data for per day price and sale of a particular product. In the dataset, we're provided with _Item Id, Average Price_, _Date_, and _Units sold_. A total of _462000_ entities are provided, including Diapers, Headphones, and Cereals as categories.

As we can see from the data below, there are different IDs for different categories, but even there are other IDs at the item level. For instance, let's consider _Diapers_ category, there are _110000_ entities in total where there are only _100_ unique Item IDs, _1100_ of each kind.

## Data Visualization

  ### Scatter Plot
  As we know from the Data exploration stage that we've different data at the item level too as we've different item ID's, To draw the relation between _Units sold_ and _Average price_ and to undertstand the trends associated with a particular `item_id` we'll derive a scattered plot of _Average price_ against _Units sold_ and do the further analysis.
  
 ### Ordinary least square estimation
 To estimate the unknown parameters other than the average price we'll use this linear regression technique i.e. the ordinary least sqaure estimation.
