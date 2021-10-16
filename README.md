# Amazon_Vine_Analysis
# Overview of the analysis
-- Project : Analyzing Amazon reviews written by members of the paid Amazon Vine program
The project was aimed at analyszing Amazon Vine program in reviewing companies product.
Some reviews were done as part  of the Vine program (paid) and there were review that
was not part of the Vine program (unpaid).

# Results
Customers_table DataFrame
![image](https://user-images.githubusercontent.com/70987568/137602951-249ef81e-9a44-4396-bda8-0908a2c77e08.png)

Products_table DataFrame
![image](https://user-images.githubusercontent.com/70987568/137602956-cabbb25e-5157-42d0-8f11-36297792b3d5.png)

Review_id_table DataFrame. 
![image](https://user-images.githubusercontent.com/70987568/137602961-b6f44c23-d0e4-47ba-8dac-3012dc2caea8.png)

Vine_table. DataFrame
![image](https://user-images.githubusercontent.com/70987568/137602968-fa8a4334-7a24-467a-ad60-785eed62c6cf.png)

•	Vine reviews = 3 
![image](https://user-images.githubusercontent.com/70987568/137602841-7bde00d2-0ca3-4bbc-a9b9-71b4a8becb47.png)
 non-Vine reviews = 3094
![image](https://user-images.githubusercontent.com/70987568/137602850-d763f459-ff15-416a-b165-09ff5b07936e.png)
•	Vine reviews were 5 stars= 2
![image](https://user-images.githubusercontent.com/70987568/137602857-dded4d4b-7f4b-446e-8b8a-bd848d25270e.png)
  non-Vine reviews were 5 stars = 1704
![image](https://user-images.githubusercontent.com/70987568/137602867-f4324ac3-741e-4b6e-9b0d-dded7e6fef92.png)
•	Percentage of Vine reviews were 5 stars = 66.7% 
  Percentage of non-Vine reviews were 5 stars = 55.1%
# Summary
The total votes for the non-Vine reviews(unpaid) increases as the helpful vootes increases as shown
in the lineare regression analysis
![image](https://user-images.githubusercontent.com/70987568/137602827-ced59361-2fba-45b3-9738-67e507ce8cd8.png)
![image](https://user-images.githubusercontent.com/70987568/137602742-7627cf00-4d5f-4ca6-abea-f2d88bd6d3b9.png)
Depicted with model.coeffficien of variation of [1.05694134] and an model.intercept_ of 1.59
The Vine reviews (paid) is lower than the non-Vine reviews(unpaid) in numbers as showns above 
and tends to be neglible when compared to the non-Vine reviews(unpaid)
![image](https://user-images.githubusercontent.com/70987568/137602814-1b7db74c-db59-4bfb-9922-631ff97e654d.png)
