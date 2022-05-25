### automating aws cloud infrastructure using terraform

- created an s3 bucket to store infrastructure data

![](images/s3bucket1.png)

- configured git bash to connect to aws using access key, secret access key and downloading necessary applications and dependencies

![](images/s3bucketconfgitbash2.png)

![](images/s3bucketconfgitbash22.png)

- wrote terraform script to create aws vpc in us-east-1 region
- did terraform init to start terraform backend program
- terraform plan to see the plan on creating the vpc

![](images/awsvpcresource3.png)

![](images/treexterraforminit4.png)

![](images/treexterraforminit44.png)

![](images/terraformplan5.png)

- added additional scripts to create 2 public subnets
- formatted, validated and created a plan of the scripts
- ran the apply command to see the end result

![](images/publicsubnets6.png)

![](images/terraformfmtvalidateplan7.png)

![](images/terraformfmtvalidateplan77.png)

![](images/terraformapply8.png)

![](images/terraformapplyawsvpc8.png)

![](images/terraformapplyawssubnets8.png)
