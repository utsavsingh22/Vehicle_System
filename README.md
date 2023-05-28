# Vehicle_System

General Motors is one of the leading heavy vehicles manufacture company. To improve their service they are planning to rollout lot new features based on IOT

-Vehicles has third party IOT device which will send the telemetry data(in JSON format) over the AWS cloud

-You need to move data from third party AWS to General motors Azure cloud.

-You need to validate the JSON sometime it could be incomplete or wrong JSON which needs to be rejected.

-Once JSON got validated this data would be stored in the SQL database which will be further utilised by the data science team.

As a DataEngineer the following Steps to follow:-
Step 1:- Create Architecture Diagram
![image](https://github.com/utsavsingh22/Vehicle_System/assets/60449352/fda60646-6239-4dbf-a901-96060db26831)

Step 2:- Implementation
![image](https://github.com/utsavsingh22/Vehicle_System/assets/60449352/04d83887-ccca-4c4b-84b2-8786e03a1de5)

Step 3:- Create S3 bucket
Step 4:- Create ADLS (Cloud based service provided by microsoft azure it enables the storage and analysis of large amount of unstructured and structured data.
![image](https://github.com/utsavsingh22/Vehicle_System/assets/60449352/f36d646f-0fca-4f58-987b-3396907b2299)

Step 5:- Create ADF(cloud based data integration service that enables the creation, scheduling, and management of data pipelines to move and transform data from various sources and destination.
![image](https://github.com/utsavsingh22/Vehicle_System/assets/60449352/503dabb0-b6b3-4643-a6f6-375a0430a549)

Step 6:- Create Linked Service in ADF from manage tab(A linked service is a connection to a data source or destination that is used to create a pipeline in Azure Data Factory. It contains the connection information required to access the data source or destination.
