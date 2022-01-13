# Create a new EKS on US-EAST-1 Region(North Virginia) 

#### Requisites

All of these steps need to be logged using AWS CloudShell.

------------
#### Follow these steps:

#### 1. Clone this project using this command below:

```sh
git clone https://github.com/joelcpinheiro/eks_terraform.git
```

#### 2. Now you need to install Terraform to perform a new EKS:

```sh
curl https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip -o terraform.zip;
unzip terraform.zip;
mv terraform /usr/bin/
```

#### 3. Execute these commands now and try to understand all those steps:

```sh
terraform init
terraform plan
terraform apply
```

#### Don't forget to save your .tfstate file in a safe place.

#### Version
------------

1.0

#### Author
------------
 
 ***Joel Pinheiro** - *Github* - https://github.com/joelcpinheiro/

#### License
------------

Use where you think you will contribute, I hope you enjoy.

