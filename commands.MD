## list of useful commands
aws swf list-domains --registration-status REGISTERED --output json
aws cloudformation list-stacks  --output text --query "StackSummaries[*].StackName" >stacks
aws cloudformation list-stacks  --query "StackSummaries[*].StackName" >stacks
aws cloudformation delete stack amazon-ecs-cli-setup-ec2-example2
