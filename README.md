1. Download the terraform (add the path)
2. Download the az cli (authenticate)
3. Create the SP and give contributor right
   

Error We are facing while provisioning the resources using terraform.
Below snap, we need to provide the SP details.
![image](https://github.com/user-attachments/assets/fdf88ddc-6691-4e82-bce9-c281c1b9c9d5)

You are not in the right path, this is the error on below snap.
![image](https://github.com/user-attachments/assets/d1825a54-3efd-4046-b1c2-c4786ee45d3f)

Below error indicate the client_secret is nothing but value. And we have to given the SP user as a contributor right. I have explain in details how we can create the Service principle along with access.
![image](https://github.com/user-attachments/assets/a1124147-7492-4956-ada2-35852927d581)

SP Details
![image](https://github.com/user-attachments/assets/5d3006c1-8c5b-48bb-968c-e1be0f20889e)

 client_id       = "d9f"
 client_secret   = "VAb8Q" #value is the client secret
 tenant_id       = "693bed"
 subscription_id = "603c"

error while creating the remote backed.
<img width="1463" height="169" alt="image" src="https://github.com/user-attachments/assets/a3a28b52-4bfe-4f92-818b-1085b0a7768c" />

solution of remote backed. we have to manually create the storage account and manually create the container file as well.
<img width="846" height="283" alt="image" src="https://github.com/user-attachments/assets/b3f923d8-1daa-4ff3-8d6e-01790ab98950" />


