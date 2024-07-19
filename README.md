So here I have documented the creation and Deployment of my first Microsoft Azure resource which is a virtual machine using my free subscription account (with 200$ free credits).
1)First of all I open my Microsoft azure account , click on create a resource and under that I've got many options from which I can choose to create any resource in the Cloud with the "pay as you go" model which means I only pay for the resources I use and it's of no concern to me how the physical datacenters are maintained (network activities ,cooling ,security etc.).

Resources like virtual machine, storage account, SQL databases are available. Here we choose the virtual machine.
2)PROJECT DETAILS -
Now we have to configure what set of attributes will our virtual machine possess.
2a) The subscription type is free.
2b) The resource group consists of all the resources that we need for our project and are maintained as a single entity.
3) INSTANCE DETAILS -
3a) I name my virtual machine as -myownvm.
3b) The region I would like to deploy this virtual machine in is the (US) East US.
3c) The availability options enable us to clone our data present in data centers to other data facilities (data centers) to make it highly available in case of natural disasters or an outage.
3d) The zone specified for the job is zone 2, we can create multiple zones.
3e) I've set the security type as default.
3f) The image represents the type of operating system were going to install in our virtual machine here I've selected Ubuntu server 20.04 LTS-x64 Gen 2.
3g) The virtual machine architecture I've set as x64 bit.
3h) For the size I've selected the default one.
4) ADMINISTRATOR ACCOUNT -
4a) The authentication setting I've chosen to be password based.
4b) I select my name as username and select a password of my choice.
5)INBOUND PORT RULES -
5a) For inbound ports I've selected "allow selected ports ".
5b) I can select various ports like HTTP, SSH, HTTPS as inbound ports.
6)I then click on review and create to check whether the machine I setup is feasible as per my configurations or not.
7)When the specifications and hence the machine is valid it shows "validation passed " and the price for the virtual machine can be seen per hour as 0.8652/hr. then I enter my email and phono. for receiving billing updates.
8)Upon hitting create I initiate the deployment process and I takes a bit of time. and finally, it shows the deployment is complete.
9)I can check the all the specifications of my virtual machine in the overview.
10)When I check the resource group, I observe that several other necessary resources have been automatically allotted with the virtual machine, like virtual address, disk storage, virtual network etc.
11)I can directly configure and mange resources through Command Line Interface. 
