# Infrastructure Description

## Diagram

[Architecture Diagram](https://github.com/MuhamedRashwan/HostingFullStackApp-AWS/blob/main/Documentation/architecture_diagram.png)

<br>

# AWS Services

### RDS Postgres 
- The application server uses AWS RDS Postgres as database for storing and retrieving information.
    + Endpoint: udagramdb.cmn6mcnbudzh.us-east-1.rds.amazonaws.com
    + Port: 5432
### Elastic Beanstack
- Used to save BE code and FrontEnd code will call the API's on  the EB through this endpoint.
    + Endpoint: http://udagram-env.eba-xqwk6rmg.us-east-1.elasticbeanstalk.com/
### S3 Bucket
- The frontend application is deployed using AWS S3 Bucket. The bundled assets are uploaded to an S3 bucket and that
bucket is made publicly readable. End users can access the application from the Bucket's endpoint.
    + Endpoint: http://udagram-rashwan.s3-website-us-east-1.amazonaws.com/
