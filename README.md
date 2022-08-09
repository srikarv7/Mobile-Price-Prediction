# Mobile-Price-Prediction
Final project for the course Data Science Engineering Methods and Tools at Northeastern University.***Please read this readme file in White Theme to view the labels***

In this project we are trying to classify mobiles based on the price range. We use features like battery power, bluetooth enabled, 4g, 3g, RAM, internal memory etc to do the classification. We predict 4 price ranges -
0 - Low cost, 1 - Medium cost 2 - High cost 3 - Very high cost. This could be used by mobile manufacturing companies to predict price range of mobiles with various features and help understand competition. It can also be used by customers of mobiles to check if the features they require in a mobile are available in a particular price range.

![image](https://user-images.githubusercontent.com/32200918/183536917-10170ac6-c063-4dca-b2e0-ab15b6463a9d.png)


## Data inference and Visualization

### Distribution of the target outcomes
The target feature 'price range' has 4 values - 0,1,2,3. The below plot shows the distribution of these values in the dataset. We found that the distribution of the values are the same in all the 4 categories.

![image](https://user-images.githubusercontent.com/32200918/183537356-a351e363-e4b1-48a4-8523-06ccc8188d3b.png)

### Distribution of data in various features 

#### 1. Count plot for bluetooth
From the below graph we can infer that the count of mobiles in each price range is almost the same irrespective of the availabilty of bluetooth in a mobile

![image](https://user-images.githubusercontent.com/32200918/183537435-0f35fe02-9797-46c3-af3f-1dfa2e7df013.png)

#### 2. Count plot for Dual Sim
From this count plot we do not see a drastic variation between single sim and dual sim. But we see a slight variation. The count of mobiles with dual sim in the high price range is higher than in lower price ranges

![image](https://user-images.githubusercontent.com/32200918/183537498-17c99903-9099-4797-8d13-4a80298231b3.png)

#### 3. Count plot for 4g
The data distribution is almost uniform. There are a higher number of mobiles with 4g in the highest price range.

![image](https://user-images.githubusercontent.com/32200918/183537524-ccb0b417-de77-409b-985b-6d1da1c704a4.png)

#### 4. Count plot for Cores
There cores of mobiles range from 1 to 8. The plot shows the count of mobiles with each type of core in all the price ranges

![image](https://user-images.githubusercontent.com/32200918/183537556-d338ec4d-94c9-4bf6-a639-04b05ec4f5d6.png)

#### 5. Count plot for wifi
We see that there is no much variance for the count of mobiles with and without wifi

![image](https://user-images.githubusercontent.com/32200918/183537615-5e5fd493-8d9a-4d2d-9eb3-a90ecaf2d0b3.png)

#### 6. Piechart for 3g support
We can infer that most mobiles in the dataset support 3g

![image](https://user-images.githubusercontent.com/32200918/183537659-34c23407-90cc-4d2a-8d4e-51711b090d97.png)

#### 7. Piechart for 4g support
From this piechart we can infer that almost half the phones support 4g and half the phones dont support 4g

![image](https://user-images.githubusercontent.com/32200918/183537706-fa1cafc6-ec9e-4268-a4b2-57fc252cdf70.png)

#### 8. Relationship between price_range and RAM
We plot a pointplot to check the relationship between RAM and price_rance. We see a linear relationship between the two parameters indicating that higher the RAM of a mobile higher is the price_range

![image](https://user-images.githubusercontent.com/32200918/183537753-a1987306-2573-4462-8740-23a722fd39a5.png)


#### 9. Relationship between price_range and mobile weight
We plot a pointplot to analyse this relationship. We see that low and medium range phones have similar weights. The weight for high price phones are higher. The costliest phones ie mobiles in range 3 have the lowest weight

![image](https://user-images.githubusercontent.com/32200918/183537810-1a8b9588-1983-4049-9988-f572a91970be.png)

#### 10. Relationship between Battery and Price Range
We use a boxplot to visualize this relationship.We see that as the price range increases that battery power also increases

![image](https://user-images.githubusercontent.com/32200918/183537862-f8a128cd-b1ae-433a-a680-33b62ca0cc17.png)

#### 11. Relationship between Price Range and Internal Memory
Relationship between internal memory and price range is obtained using a pointplot. It has a general upward trend except in price range 2. The costliest mobiles have the highest internal memory

![image](https://user-images.githubusercontent.com/32200918/183537901-7de37339-f7a4-4aed-891f-08822c19fb0e.png)


