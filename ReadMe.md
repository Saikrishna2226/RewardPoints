Technical details --> Spring Boot, Maven, H2, junit

the maven build

start java application

http://localhost:8080/createData  --> this will calculate the reward points and create dataset information in H2 DB.
output --> Sample Data is inserted

http://localhost:8080/getRewardPoints?customerName=customer1 --> Get the customer total earning points and monthly wise total earning points
output--> {"totalPoints":50,"rewards":[{"month":2,"monthPoints":0},{"month":12,"monthPoints":50}]}

http://localhost:8080/getRewardPoints?customerName=customer2 --> Get the customer total earning points and monthly wise total earning points
output --> {"totalPoints":200,"rewards":[{"month":1,"monthPoints":110},{"month":12,"monthPoints":90}]}


