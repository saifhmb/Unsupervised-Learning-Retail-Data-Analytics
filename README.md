# Association Rule Mining
‘Grocery Product Purchase’ dataset is mainly collected by one of the retail stores of Kroger in the USA. This data was collected during a super-saver weekend to understand more about the customers buying behavior
a.	Please explain the customer behavior, based on your analysis.
The super-saver weekend seems to have resulted in high footfalls based on the 9,835 unique transactions that occurred.
![image](https://github.com/user-attachments/assets/67c2c86d-8429-483d-b202-e5084c2eb838)

 
Each transaction led to the purchase of at least 1 item. About 80% of customers bought at least 2 items. Half the customers bought at least 4 items. Therefore, customers were taking advantage of the super-saver weekend by buying several items to realize some savings.

 ![image](https://github.com/user-attachments/assets/58ac0c50-5fda-451f-91fa-08ba5e4ad4f5)

 
b.	Which products would you Up sell, and which products would you Cross sell? Why?
![image](https://github.com/user-attachments/assets/559e549f-1b61-4b81-a399-f1d57b721720)

 
Based on the above analysis, frequent itemsets are {yoghurt, whole milk}, {other vegetables, whole milk} and {rolls/buns, whole milk}. I would Up sell ‘other vegetables’ by recommending it to a customer as an additional item. This is because the lift (whole milk => other vegetables) is 1.51. This means that customers are 1.51 times more likely to buy other vegetables if they buy whole milk.
I would Cross sell yogurt and rolls/buns as complementary products to customers that buy whole milk. This is because these products tend to be used as breakfast items. If a customer is already buying whole milk for breakfast, there is a high likelihood the customer would also be interested in buying yogurt and rolls/buns. Additionally, the lift of (whole milk => yoghurt) and (whole milk => rolls/buns) is 1.57 and 1.21 respectively. This means that customers are 1.57 and 1.21 times more likely to buy yogurt and rolls/buns respectively if they buy whole milk.

c.	Would you consider making any decisions based on the results? Why or why not?

Based on the results, I would run a promotion on whole milk, yogurt, rolls/buns and other vegetables together. Additionally, I would have these items displayed within the same line of sight, aisle, or area to improve sales.


