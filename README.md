 # Introduction
## What is pfSense?.
pfSense is a free and open source firewall and router that also features unified threat management, load balancing, multi WAN, and more.
pfsense has many features and advanced capabilities that ensure it always follows either default or custom rules. It also filters traffic separately whether it's coming from your internal network of devices or the open internet, allowing you to set different rules and policies for each.


First we have to do Installation of ubuntu in Base Machine
After installation we Have to make two Bridge Connections. 1. Wan & 2 LAN. 
Create Bridge on Virt-manager (VM).

![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/a64a5ca2-d88f-4a61-88cf-5f80a62b2c89)
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/2671fc58-39e2-4a83-b746-002c6cfd59c1)

######  Download pfsense
https://www.pfsense.org/download/
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/ebc1b03e-f462-4758-a0a1-89919cc2821b)

### Make a vm of pfsense

######  Step 1 - Choose how you would like to install the operating system : select on Local install media (ISO image or CDROM)
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/6d05cfcf-930c-4d13-8ead-c6148e2661a2)


###### Step 2 - Create a new virtual machine : Use ISO image and Click on browser
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/0bdacbc8-f332-48ea-b8c1-917d4cfcbd7a)

###### Step 3 - select ISO file
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/4927ca8e-677d-4990-ab27-eaa5bc02ddb8)

###### Step 4 - Choose Memory and CPU setting
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/a4447948-bed6-489b-8480-9bd7bd54667a)

###### Step 5 - Click on Enable storage for this virtual machine
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/50b023eb-6450-4867-b6fa-2dd1920c5232)

###### Step 6  Enter the Name : pfSense, Then Click on FInish. 
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/ba6db362-404e-421d-a4ee-0e358a82af46)

###### Step 7 Network source : Virtual network Bridge device.. 
Device module : e1000
![image](https://github.com/HarikeshChourasiya/HarikeshChourasiya/assets/168734670/083f605a-42f0-4813-86ec-85b005d3f6dc)

######Step 8
Click on Add hardware and then Click on Network
Network source : Virtual network 'default' :WAN
MAC address : it will be default
Device module : e1000 or according to you select anyone.

















