# Create a new EKS Cluster on US-EAST-1 Region(North Virginia) 

#### Requisites

All of these steps need to be logged using AWS CloudShell.

------------
#### Follow these steps:

#### 1. Clone this project using this command below:

```sh
git clone https://github.com/joelcpinheiro/eks_porfolio.git
```

#### 2. Install eksctl executing these commands:

```sh
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
sudo mv /tmp/eksctl /usr/local/bin
eksctl version

```

#### 2. Now you need to run the command below to perform a new EKS Cluster:

```sh
eksctl install xxx

```


#### Version
------------

1.0

#### Author
------------
 
 ***Joel Pinheiro** - *Github* - https://github.com/joelcpinheiro/

#### License
------------

Use where you think you will contribute, I hope you enjoy.

