Technologies used for this project:  Spring Boot, H2, Maven
Please follow the below steps 
1)	Do maven clean install 
2)	Start the application
3)	Type below url in browser, this will calculate the reward points and create dataset information in H2 DB.
http://localhost:8080/createDataSet 
The above link will create sample dataset
4)	Type below url to get the customer total earning points and monthly wise total earning points
http://localhost:8080/getCustomerRewardPoints?customerName=c1

Sample Output:
{"totalPoints":100,"rewards":[{"month":6,"monthPoints":20},{"month":7,"monthPoints":30},{"month":8,"monthPoints":50}]}

5)	Type below url to get the customer total earning points and monthly wise total earning points
http://localhost:8080/getCustomerRewardPoints?customerName=c2

Sample Output:
{"totalPoints":200,"rewards":[{"month":7,"monthPoints":90},{"month":8,"monthPoints":110}]}



