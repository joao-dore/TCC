
#Question 1

https://stackoverflow.com/questions/76049290/error-accesscontrollistnotsupported-when-trying-to-create-a-bucket-acl-in-aws


Error AccessControlListNotSupported when trying to create a bucket ACL in AWS

Recently I tried to deploy an aws_s3_bucket_acl resource using Terraform, and received the error:

Error: error creating S3 bucket ACL for bucket-name: AccessControlListNotSupported: The bucket does not allow ACLs │ status code: 400

I didn't see why this wouldn't create. However I checked AWS docs [1 2] and looks like they recent had an update as of April 2023 that disabled ACLs by default.

