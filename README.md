
be using a dataset that compiles information about NYC yellow taxi cab trips. You are required to implement the following functionalities and answer some questions using findings of queries you should create on your own. You can perform any necessary alterations to the data that may improve the usability of these queries or even make them possible. You should implement the task twice: once per NoSQL database (MongoDB and Cassandra). The dataset is divided into 2 csv files: • taxitripdata.csv contains the relevant trip data and pickup and drop-off “zones” • taxizonegeo.csv contains the longitude & latitude coordinates of the pickup zone areas. These are all list-like locations of the polygon vertices. You are required to do/answer the following :- a) Remove the columns “store_and_fwd_flag”, “rate_code” and “total_amount” from taxitripdata b) Drop rows with missing essential details that would be required to fulfill the upcoming queries c) Insert the data in the database as you see fit d) Calculate the duration for each trip and add it as a new field in your database e) Use “fare_amount”, “extra”, “mta_tax”, “tip_amount”, “tolls_amount” and “imp_surcharge” to calculate the total trip cost and add it as a new field in your database f) What is the most common payment type used per time of day? Hint: time of day meaning morning, afternoon or evening g) What is the average tip amount per passenger count? h) What are the best 5 locations for drivers to pick up passengers from?
