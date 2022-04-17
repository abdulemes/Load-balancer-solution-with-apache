# Project Workflow

## Setting up VM environment

Step 1 - Additonal EC2 is spin up for load balancer.

![IMG_9803](https://user-images.githubusercontent.com/93732510/163718327-d31219e8-a3f5-4185-be18-7680b2b9a804.jpg)

Step 2 - The inbound rule is configured to open port 80.

![IMG_9804](https://user-images.githubusercontent.com/93732510/163718498-aef1c844-fcb8-4d40-9687-e0dbe204f541.jpg)

## Installing and configuring apache load balancer

![IMG_9805](https://user-images.githubusercontent.com/93732510/163718634-efe6c065-b079-4065-b807-71381b478067.jpg)

![IMG_9806](https://user-images.githubusercontent.com/93732510/163718726-52ab1cd0-3b1c-4c27-8c0b-e4c1d32c2f82.jpg)

![IMG_9807](https://user-images.githubusercontent.com/93732510/163718767-8f233cf9-6aa1-4518-af22-c46beb34564a.jpg)

![IMG_9808](https://user-images.githubusercontent.com/93732510/163718799-fabe0a46-b85f-4464-8cac-673f51e714b5.jpg)


## Configuring load balancer

Step 1 - bytraffic balancing method is applied so incoming traffic can be distributed to web servers according to current traffic.

![IMG_9809](https://user-images.githubusercontent.com/93732510/163718969-12304f8e-0f63-4523-b081-68cbe0dce2e3.jpg)

Step 2 - configuration is verified via browser.

![IMG_9810](https://user-images.githubusercontent.com/93732510/163719098-4a3acd1a-952a-44bb-b9ed-aff97345eb08.jpg)

## Bonus Step

/etc/hosts file of LB server can be updated with arbitrary name for both web servers instead of IP addresses

LB config file is then updated with the names instead of IP address.
