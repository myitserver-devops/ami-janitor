Delete AMIs in AWS account that are older then certain age and not in-use to launch active EC2 instances.
Usage:

Run cleanup with defaults (AMIs older then 30 days) in region us-east-1

AWS_REGION=us-east-1 ansible-playbook -v ami-cleanup.yml
