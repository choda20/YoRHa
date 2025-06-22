# YoRHa
Repo for Way Of The Code project.

## Deployment
To run the application you only need to run the commands:

```bash
cd Deployment
docker compose up
```
### Connecting to services
#### S3
To connect to the Minio s3 deployment you have 2 options:
##### Web UI
The minio Web UI will be available in the address: http://127.0.01:9001/, you can login with the following credentials:
- Username: admin
- Passsword: admin123
##### S3 Browser
To connecto to minio with S3 Browser you will need the following configuration:
- Account: S3 Compatible Storage
- API: localhost:9000
- Acess Key: admin
- Secret Access: admin123
- Use secure transfer (SSL/TLS): unchecked
#### Database
To connect to the PostgreSQL deployment you can use the Adminer Web UI in the address: http://127.0.01:8080/, you can login with the following credentials:
- System: PostgreSQL
- Server: db
- Username: admin
- Passsword: admin
- Database:  YoRHa
