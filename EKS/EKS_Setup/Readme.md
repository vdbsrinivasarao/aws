## Step1 
Create IAM Roles and Attach that role to an EC2 Instance

## Step2
Install the awscli 

   https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
   
Set environment variable
   
   export PATH="/usr/local/bin:$PATH"

## Step3 
Install kubectl

   https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html
   
## Check kubectl version
  'kubectl version'


## Step4
  Install eksctl
  https://docs.aws.amazon.com/eks/latest/userguide/eksctl.html
  curl -sLO "https://github.com/eksctl-io/eksctl/releases/latest/download/eksctl_$PLATFORM.tar.gz"
 curl -sL "https://github.com/eksctl-io/eksctl/releases/latest/download/eksctl_checksums.txt" | grep $PLATFORM | sha256sum --check
 tar -zvxf eksctl_Linux_amd64.tar.gz
 sudo mv eksctl /usr/local/bin
 eksctl
