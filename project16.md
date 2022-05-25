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

- ran the destroy command to generate better scripts for the infrastructure automation

![](images/terraformdestroy9.png)

![](images/terraformdestroy99.png)

![](images/terraformdestroy999.png)

![](images/terraformdestroysubnets9999.png)

- created scripts that included variables to quicken the build process
- added a null to test the build response to the subnet specification. the response was as imagined - it returned a plan to build 6 subnets as was designed in the script

![](images/terraformplannulltest10.png)

- added final tweaks to the scripts\
- separated them into various files
- ran the final command

![](images/maintffinal1.png)

![](images/terraformtfvarsfinal1.png)

![](images/variablestffinal1.png)

![](images/final1.png)

![](images/final2.png)

![](images/final3.png)

![](images/final33.png)

![](images/final4.png)

![](images/final44.png)
