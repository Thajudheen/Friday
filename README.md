S3 bucket with supported features
versioning
lifecycle rules
server-side encryption
access control

Usage
To run this example you need to execute:

$ terraform init

$ terraform plan

$ terraform apply

Requirements
Name	Version
terraform	>= 0.13
aws	>= 3.36

Outputs

Name                             Description
s3_bucket_object_etag	           The ETag generated for the object (an MD5 sum of the object content).
s3_bucket_object_id	             The key of S3 object
s3_bucket_object_version_id	     A unique version ID value for the object, if bucket versioning is enabled.

