# VPC-PROJECT
 

## This is the arcitecture of the project


![VPC-PUBLIC-PRIVATE-ARCHITECTURE](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/4eef7556-42c5-4f80-93e2-e1e966dd6f40)



## firstally created vpc with 2 public and 2 private subnets


![Screenshot (399)](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/41e4d5af-b708-4a07-95f7-11ee28098134)

## Crated the EC2 Instances in private subnet using autoscalling group


![Screenshot (403)](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/eea368b1-d2a2-4f48-8015-fe8deeb55ccd)


## Now crated new baston-host ec2 server to access the the our EC2 servers which are located in private subnet


![Screenshot (410)](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/91d466d6-11b6-4608-9995-a3bea62ad840)

## Added load balancer to access private instances and also divert the traffic flow from one instance to another instance


![Screenshot (411)](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/ff6066c0-40e7-4e6d-be39-6617694f3344)


## Now copying the key from local host to the baston host using secure copy command of linux 

 scp -i /C/Users/Yeshwant/Downloads/BASTION_HOST.pem(this the identity file) /C/Users/Yeshwant/Downloads/Auto_scalling.pem ubuntu@13.232.185.72:/home/ubuntu        

 ## Deployed the simple python web application on port 8000 on private server(EC2) 
 

![Screenshot (412)](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/0f821023-165d-4fe5-9176-2adc1ef2cdc1)


## Finally able to access the webpage using load balancer DNS


![Screenshot (413)](https://github.com/Yeshwant-Jadhav/VPC-PROJECT/assets/153003135/3bf94d0a-519a-4e02-bca5-8ad4ec287731)




