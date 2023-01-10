# Youtube-Analysis-DataEngineering-project
YouTube Analysis Data Engineering Project  
This is a End-To-End Data Engineering Project using Kaggle Youtube Trending Dataset.
We intially had data onto the Kaggle.com.We build a landing area and uploaded all the raw data using AWS CLI that got stored into s3 bucket.Once uploaded into s3 bucket we started analyzing the data .So we created glue crawler to understand how the data is built.So we found out that we had some errors in our JSON version files.We start processing that JSON file using AWS lamda and storing that particular data inside the second s3 bucket(cleansed/enriched).So we have to transform that data into Apache format and put that data onto the cleansed version bucket.Now we need to work with CSV file which contain our actual data.We will build a crawler on top of CSV file to understand the data.We start processing that CSV version files using AWS Glue and storing that particular data inside the second s3 bucket(cleansed/enriched).So we have to transform that data into Apache format and put that data onto the cleansed version bucket.After that we ran query and did some ETL run on top of the cleaned/enriched version and making sure all the data get properly transformed and securily built on top of data warehouse.and build a final reporting version based on that data.We can easily visualize that data into quicksight.


 
