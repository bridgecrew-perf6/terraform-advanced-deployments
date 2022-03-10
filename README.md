# Learn Terraform Advanced Deployment Strategies

Learn how to use Terraform and AWS's Application Load Balancers for canary tests and blue/green deployments. Learn how to add feature flags to your Terraform configuration by using variables and conditionals. Follow along with [this
tutorial](https://learn.hashicorp.com/tutorials/terraform/blue-green-canary-tests-deployments) on HashiCorp Learn.


I. Provision underlying resources (VPC, security groups, load balancers) and a set of web servers to serve as the blue environment.

II. Provision a second set of web servers to serve as the green environment.

III. Add feature toggles to your Terraform configuration to define a list of potential deployment strategies.

IV. Use feature toggles to conduct a canary test and incrementally promote your green environment.

