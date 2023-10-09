# Starbucks-Hot-Beverages-Cluster
This assignment source code can be ran in google colab. The approach taken was using hierarchal clustering to first, find the most popular times, then proceeding to find the most popular drinks within those time slots.
## Results of clustering to find the most popular times
### Single Linkage
![image](https://github.com/kellynguyvn/Starbucks-Hot-Beverages-Cluster/assets/80297074/26cd5bbe-9f57-45d0-a6d5-87910a058602)
Most popular time slots: 9 (4 occurrences), 7 (3 occurrences), 6 and 8 (2 occurrences each)
### Complete Linkage
![image](https://github.com/kellynguyvn/Starbucks-Hot-Beverages-Cluster/assets/80297074/4f1ae5e8-1dec-4eff-9ee9-536912c53923)
Cluster 1: Time slots 3 and 4 (2 and 1 occurrences) <br>
Cluster 2: Time slots 7 and 9 (2 occurrences each)<br>
Cluster 3: Time slots 6, 8, and 9 (2 occurrences each)
### Average Linkage
![image](https://github.com/kellynguyvn/Starbucks-Hot-Beverages-Cluster/assets/80297074/717950a2-f16e-44ce-95af-36293fbab5c9)
Cluster 1: Time slot 3 (1 occurrence)<br>
Cluster 2: Time slot 9 (2 occurrences)<br>
Cluster 3: Time slots 7, 8, and 9 (2 occurrences each)<br>
### Popular Times
Time slot 9 (8-9 PM) appears frequently in all linkage methods.<br>
Time slot 7 (1-3 PM) also appears frequently.<br>
Time slots 6 (12-1 PM) and 8 (3-4 PM) could be considered for the third slot.
## Popular Drinks
### Single Linkage
Coffee Types: 2 (Cafe Latte) and 3 (Cafe Mocha) with 2 and 3 occurrences, respectively.
### Complete Linkage
Coffee Types: 2 (Cafe Latte) and 3 (Cafe Mocha) with 2 and 3 occurrences, respectively.
### Average Linkage
Coffee Types: 2 (Cafe Latte) and 3 (Cafe Mocha) with 2 and 3 occurrences, respectively.

## Conclusion
It appears that Cafe Latte and Cafe Mocha are the most common hot beverages sold during the popular time slots across all linkage methods. Therefore, offering coupons for these types of drinks could be particularly effective. The manager could consider offering coupons for Cafe Latte and Cafe Mocha during the time slots 8-9 PM, 1-3 PM, and optionally 12-1 PM or 3-4 PM to maximize customer loyalty.


