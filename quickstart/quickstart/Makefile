.PHONY: pulumi-up
pulumi-up:
	pulumi up

.PHONY: pulumi-bucket-name
pulumi-bucket-name:
	pulumi stack output bucketName

.PHONY: s3-ls
s3-ls: 
	aws s3 ls $(shell pulumi stack output bucketName)
