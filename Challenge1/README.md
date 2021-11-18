#The Terraform code in this Project is for Creating similar to 3 Tier Archtecture with Front end and creating a simple Website on back end
#The main.tf file contains the code for resource creation creating EC2 instance using a Provisioner
#The config.tf file is responsbile for all the ancillary resources needed by the EC2 instance creation.

**Lucid Chart Link**

```
https://lucid.app/lucidchart/ed141547-c2e9-4d01-bbe9-f5b28266e532/edit?viewport_loc=-554%2C118%2C3210%2C1407%2C0_0&invitationId=inv_9af74a84-8641-411a-b7f2-10f8de1aa252
```

**Steps to Run**

***Clone the Project***
```
git clone https://github.com/MjTaseen/Work-Repo.git
```

***Change directory to Challenge1***
```
cd Challenge1
```


***Initialize Terrafrom***
```
cd Challenge1
```

***Initialize the Terraform working directory ***
```
terraform init
```

***Validate the code to look for any errors in syntax, parameters, or attributes within Terraform code/resources that may prevent it from deploying correctly: ***
```
terraform validate
```

***You will see notifications that the configuration is valid or has issues.*** 

***Review the actions that will be performed when you deploy the Terraform code:***
```
terraform plan
```

***If all looks good deploy the code***
```
terraform apply
```

***You Might required to provide inputs based on template requirements such as Yes/NO***



**Once the code is successfuly deployed, you will notice that the Terraform provisioner tries to connect to the EC2 instance and, once that connection is established, it will run the bootstrapping that was configured in the provisioner block for instance.** 


**When complete, it will output the public IP for the Apache webserver as the Webserver-Public-IP value.Copy the IP address, paste it in a new browser window or tab, and press Enter.**

***Future Enhancements that can be done to this template***

**1. Creating Website replication to S3 Bucket on frequent Intervals**
**2. Adding HA**
**3. Backing up the entire Wesite to different VM/Volume/Host etc.**
**4. Adding Monitoring**
**5. Triggering Alerts based on Events**
**6. Migration to DB**
