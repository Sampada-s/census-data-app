# Census Data Application

### Python flask application that can be deployed to Elastic Bean stalk on Aws Cloud

#### Features -
1) Connect to Sql Server using pyodbc and execute sql queries
2) Redis cache for better performance

#### Deployment -
Using eb cli
1) eb init -p python-3.6 census-app --region us-east-1
2) eb init
3) eb create flask-env
4) eb open (runs the application)
