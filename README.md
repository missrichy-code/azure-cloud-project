# azure-cloud-project
CREATING A AZURE VIRTUAL NETWORK AND SUBNET


STEPS
Login to your Azure Portal and if you dont have an account you can create one 
Go to Virtual Network (NETWORKING) and click create
Go to project details and 
Create a new resource group
Go to instance details then give it a VM name and put your desired rgion too
then click on Next 
Enable Azure Firewall
Enble DDOS nertwork protection 
NB: Azure firewall and DDOS Network Protection are not free services 
Then click on review and create 
After deploying, Go to resource 
TO CREATE YOUR SUBNET
Go to settings, click on subnet
leave the name as default
Go to cost management+billing
click on billing (benefits preview)
View all free services 
Select Linux Virtual Machine (750hrs) then create 
Input the VM name and region 
Image (Ubuntu Server 22.04 LTS-64 Gen 2)
Select password for authentication type 
Username - Azureuser
Then put a strong password and put the password down in your notepad to remember 
Select inbound ports (HTTP (80), SSH(22))
Review and create 
then go to your MING
Type  ssh azureuser@public IP Address
Then put your password 
With this yiuve created a server 
