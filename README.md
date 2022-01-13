# Create a new EKS on US-EAST-1 Region(North Virginia) using t2-micro and CentOS 7.9 AMI

#### Requisites

You must have installed ```git``` and ```unzip``` package on your GNU Linux to perform this action;<br>
You must have a ```key par``` on AWS, it will be used to insert on ```variables.tf``` file(line 24).

------------
#### Follow these steps:

#### 1. Access the AWS Web Console and create a IAM User with ```Programmatic access``` access type and add permission name ```AmazonEC2FullAccess```;

#### 2. Clone this project using this command below:

```sh
git clone https://github.com/joelcpinheiro/eks_terraform.git
```

#### 5. Now you need to install Terraform to perform a new EKS:

```sh
curl https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip -o terraform.zip;
unzip terraform.zip;
mv terraform /usr/bin/
```

#### 6. Execute these commands now and try to understand all those steps:

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

