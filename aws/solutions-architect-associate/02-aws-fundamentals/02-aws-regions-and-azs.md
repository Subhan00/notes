# AWS Regions and AZs

- AWS has regions all around the world (us-east-1, eu-west-1)
- Each region has availability zones (us-east-1a,us-east-1b...)
- Each availability zone is a physical data center in the region, but separate from the other ones (so that they're isolated from disasters)
- AWS consoles are region scoped (except for IAM and S3)

All the regions can be viewed at https://aws.amazon.com/about-aws/global-infrastructure/

For this course, we want to use a region with at least 3 AZs.

