# Check Signature Version 2 in S3 API Request

When request to s3 api using signature version 2, notification to email address.

## Deploy

```
aws cloudformation deploy \
	--stack-name check-sigv2-s3-api-request \
	--template-file template.yaml \
	--parameter-overrides 'EmailAddress=notification-xxxxxxx@example.com'
```
