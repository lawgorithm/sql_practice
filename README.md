# sql_practice

### Rolling Averages
* Rolling average of number of tweets (e.g. ROWS BETWEEN 2 PRECEDING AND CURRENT ROW)
  * [Tweets' Rolling Averages [Twitter SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Tweets'_Rolling_Averages_%5BTwitter_SQL_Interview_Question%5D.ipynb)
 
### RANK() and DENSE_RANK()
* Top 3 salaries, handling ties appropriately
  * [Top Three Salaries [FAANG SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Top_Three_Salaries_%5BFAANG_SQL_Interview_Question%5D.ipynb)
* Top 5 musicians, handling ties appropriately
  * [Top 5 Artists [Spotify SQL Interview Question]](https://colab.research.google.com/github/lawgorithm/sql_practice/blob/main/Top_5_Artists_%5BSpotify_SQL_Interview_Question%5D.ipynb)

### ROW_NUM()
* Get multiple data fields for the third transaction for every user
  * [User's Third Transaction [Uber SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/User's_Third_Transaction_%5BUber_SQL_Interview_Question%5D.ipynb)
* Top three items per category by total spend
  * [Highest-Grossing Items [Amazon SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Highest_Grossing_Items_%5BAmazon_SQL_Interview_Question%5D.ipynb)
* Get odd an even measurements (by daily measurement time) from a sensor
  * [Odd and Even Measurements [Google SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Odd_and_Even_Measurements_%5BGoogle_SQL_Interview_Question%5D.ipynb)

### Timestamps
* Events within a date range
  * [Histogram of Tweets [Twitter SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Histogram_of_Tweets_%5BTwitter_SQL_Interview_Question%5D.ipynb)
  * [Teams Power Users [Microsoft SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Teams_Power_Users_%5BMicrosoft_SQL_Interview_Question%5D.ipynb)
* Complex date diffing (days, hours, seconds). E.g. EXTRACT(EPOCH FROM ts) to get seconds.
  * [Average Post Hiatus (Part 1) [Facebook SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Average_Post_Hiatus_(Part_1)_%5BFacebook_SQL_Interview_Question%5D.ipynb)
* Date diffing using the INTERVAL keyword
  * [Second Day Confirmation [TikTok SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Second_Day_Confirmation_%5BTikTok_SQL_Interview_Question%5D.ipynb)
* DATE() function to extract date from timestamp
  * [Odd and Even Measurements [Google SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Odd_and_Even_Measurements_%5BGoogle_SQL_Interview_Question%5D.ipynb)
* Finding earliest or latest timestamp
  * [Histogram of Users and Purchases [Walmart SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Histogram_of_Users_and_Purchases_%5BWalmart_SQL_Interview_Question%5D.ipynb)
* EXTRACT() to get month number or year number
  * [Active User Retention [Facebook SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Active_User_Retention_%5BFacebook_SQL_Interview_Question%5D.ipynb)
 
### EXISTS()
* Get users active (exist) this month who also were active (existed) last month
  * [Active User Retention [Facebook SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Active_User_Retention_%5BFacebook_SQL_Interview_Question%5D.ipynb)
 
### LAG()
* Get last year spend and this year spend to create a YoY spend change
  * [Y_on_Y_Growth_Rate_[Wayfair_SQL_Interview_Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Y_on_Y_Growth_Rate_%5BWayfair_SQL_Interview_Question%5D.ipynb)

### Joins
* [Page With No Likes [Facebook SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Page_With_No_Likes_%5BFacebook_SQL_Interview_Question%5D.ipynb)
* Self-joins on different columns
  * [Well Paid Employees [FAANG SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Well_Paid_Employees_%5BFAANG_SQL_Interview_Question%5D.ipynb)

### CASE ... WHEN instead of IF
* [Laptop vs. Mobile Viewership [New York Times SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/Laptop_vs_Mobile_Viewership_%5BNew_York_Times_SQL_Interview_Question%5D.ipynb)

### NULL handling
* Replace IFNULL(X, 0) with COALESCE(X, 0)
  * [IBM db2 Product Analytics [IBM SQL Interview Question]](https://github.com/lawgorithm/sql_practice/blob/main/IBM_db2_Product_Analytics_%5BIBM_SQL_Interview_Question%5D.ipynb)
 
### Tricky subqueries 
* SELECTing from another table in a WHERE clause for filtering
  * [Compressed Mode [Alibaba SQL Interview Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Compressed_Mode_%5BAlibaba_SQL_Interview_Question%5D.ipynb)

### Casting to other data types
* Casting integers to decimal
  * [Compressed_Mean_[Alibaba_SQL_Interview_Question].ipynb](https://github.com/lawgorithm/sql_practice/blob/main/Compressed_Mean_%5BAlibaba_SQL_Interview_Question%5D.ipynb)

