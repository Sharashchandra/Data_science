### Explantaion (2)

#### We use pandas as it helps us with data analysis.
#### we import pandas and read the dataset from the csv file which inturn creates a DataFrame


#### we then calculate the throughput for each row in the DataFrame by making use of the formula, 

##      Throughput = Total data send / Total time taken to send the data        

#### We then group the data by ASN and we find the mean of the throughput of the different ASN's which gives us the average throughput for all the different ASN's

#### We repeat the same by grouping with respect to the Co Servers and finding the mean of the throughput to find the average



### Explaination (3)

#### In the future, we can create a grouping field with respect to the country, Metric A etc
#### We can group the data with respect to more than one column to get a more detailed analysis of the throughput for different scenarios i.e
#### We can group based on the Country and ASN so that we can get to know the throughput of a particular ASN in a particular country

#### Some of the keys that can be used are:
* Country
* Timestamp(based on years)
* Timestamp(based on months)
* Timestamp(based on days)
* Timestamp(based on hours)
* Metric A
* Country and ASN
* Country and TimeStamp
* Country and Metric A
* Country and Co Server
* Country, ASN and TimeStamp
* Country, ASN and Metric A
* Country, ASN and Co Server
* Country, ASN, TimeStamp and Metric A
* Country, ASN, TimeStamp and Co Server
* Country, ASN, TimeStamp, Metric A and Co Server
