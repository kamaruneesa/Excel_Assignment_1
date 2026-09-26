# Excel_Assignment_1
Data Exploration
1)Sum,Count,Average
Total price of all products: =SUM(D2:D35)
How many products are there in the dataset :=COUNTA(B2:B35)
Average price of the products :=AVERAGE(D2:D35)
2)MIN AND MAX
Minimum price among all products :=MIN(D2:D35)
Maximum price among all products :=MAX(D2:D35)
3)IF FUNCTION
Categorize products as "High price">=$500 and "Standard price" :
=IF(D2:D35>=500,"High Price","Standard Price")
4)SUMIF AND COUNTIF
Total price for products in the 'Electronics' category :=SUMIF(F2:F35,"Electronics",D2:D35) 
Count of products with price less than $100 :=COUNTIF(D2:D35,"<100")
5)TEXT FORMATTING - LEFT,RIGHT,MID
Day(fist 2 characters of product ID) :=LEFT(A2,2) :=LEFT(A2:A35,2)
Country code (Last 2 CHARACTERS OF PRODUCT ID): =RIGHT(A2,2) :=RIGHT(A2:A35,2)
MONTH(4th to 6th characters of product ID):=MID(A2,4,3) :=MID(A2:A35,4,3)






