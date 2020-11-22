# sql-converter
1. Lambda: sql-convert-input
2. subdomain: sql.semantiqlabs.com
3. api: sql-rest-redirect 
4. apigw resource: convert (POST)
5. s3: bucket for source files
6. RDS: serverless destination results store instance
7. Glue: sql-converter-job for convertion logic 
