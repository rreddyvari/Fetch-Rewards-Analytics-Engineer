# Fetch Rewards: Take Home Coding Exercise 



## Task: Fisrt


I have included the ER diagram for the given json files. 
1. Receipts data schema
   - _id(PK)
   - bonusPointsEarned 
   - bonusPointsEarnedReason
   - createDate
   - dateScanned
   - finishedDate
   - modifyDate
   - pointsAwardedDate
   - pointsEarned
   - purchaseDate
   - purchasedItemCount
   - rewardsReceiptItemList
   - rewardsReceiptStatus
   - totalSpent
   - userID(FK)
   - brandID(FK)
2. Users data schema
   - _id(PK)
   - state
   - createdDate
   - lastLogin
   - role
   - active
3. Brands data schema
   - _id(PK)
   - barcode
   - brandCode
   - category
   - categoryCode
   - cpg
   - topBrand
   - name
4. Transaction data schema
   - _id(PK)
   - userID(FK)
   - receiptID(FK)
   - brandID(FK)
  
  ## Task: Second & Third 


  I have used jupyter for all the data processing and cleaning. 
  I have included the python file.

  Data Quality issues:
  1. I have seen there are so many duplicates in the users data file.
  2. I have also detected some outliers in the'pointsEarned', 'purchaseItemCount', 'totalSpent' columns.
  3. Fields such as 'rewardsReceiptItemList', 'cpg' has nested dictionaries.

## SQl queries

I have include the queries for the given questions.

## Final task Email to stake holders

Crafted a beautiful simplified email to a fictioanl team member "Alexa". 
I have attached the email in pdf format.


  
