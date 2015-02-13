Description of a service - Amazon elastic MapReduce:

Amazon Elastic MapReduce is a webservice to process huge amounts of data in an efffective manner. It uses Hadoop to distribute the data and processing across a cluster of Amazon EC2 instances. It can also run other distributed frameworks such as Spark and Presto. It automates tasks like provisioning of the Hadoop cluster, running and terminating jobs, and handling data transfer between EC2 and Object Storage. Amazon EMR is fault tolerant for slave failures. It is used in a variety of applications like log analysis, web indexing, data warehousing, machine learning, financial analysis etc.

Procedure followed for the API call:

I made the API call using Java language binding in eclipse. I first installed the aws toolkit for eclipse and created a AWS project. Inside the class, I used BasicAWSCredentials class to authenticate my credentials. I then created a run instance request by using the RunInstancesRequest class and setting the required parameters from my AWS Management console and executed the request. Then, I made an API call to get the console output for the specified instance using the getConsoleOutput() method.

API call screenshot:

![Alt text][IMG]

[IMG]: ./apicall-screenshot.jpg
