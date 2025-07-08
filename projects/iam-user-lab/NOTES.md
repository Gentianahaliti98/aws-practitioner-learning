## IAM Lab 1 – Full Access User
Created IAM user with AmazonS3FullAccess policy
Verified full access to S3 bucket: upload, delete, view

IAM Lab 2 – S3 Read-Only Custom User
Created IAM user: s3-readonly-user
Created custom policy: read-only access to haliti-gentiana-static-site bucket
Verified:
:white_check_mark: Can list bucket and read files via CLI
:x: Cannot upload or delete (AccessDenied as expected)

