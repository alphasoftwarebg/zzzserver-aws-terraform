# zzzserver-aws-terraform
Simple AWS ZZZ Server installation with Terraform orchestrator

  1. Set operating system environment variables: 
    export AWS_ACCESS_KEY_ID="YOUR AWS ACCESS KEY"
    export AWS_SECRET_ACCESS_KEY="YOUR AWS SECRET ACCESS KEY"
  2. Download terraform and add the path to its executable to the PATH environment variable. 
  3. Clone this repository: 
    git clone https://github.com/alphasoftwarebg/zzzserver-aws-terraform.git
  4. Goto the repository contents: 
    cd zzzserver-aws-terraform
  5. Initialize the terraform: 
    terraform init
  6. See the terraform plan: 
    terraform plan
  7. If everithing in the plan is ok applay it: 
    terraform applay
  8. Goto your AWS acciunt and get the instance IP ADDRESS: 
    https://console.aws.amazon.com/ec2/home?region=us-east-1#Instances:sort=instanceId
  9. Goto the internet address: 
    http://[AWS INSTANCE IP ADDRESS]:8080
    where [AWS INSTANCE IP ADDRESS] is the IP ADDRESS from point 8. 
  10. See the result: 
    Hello, World

**main.tf** contains a simple terraform scrip for installing the ZZZ Server in the AWS account.
