# Title: How to create a super cheap Linux Home Server
## What you'll need for this project:

- A separate PC we won't be using as our home server. Either a Windows PC or a modern Linux machine will work fine. 
- A USB stick to use as a boot-able drive. 8 GB of storage or higher is recomended
- A separate PC with it's own mouse and keyboard to use as our Linux home server
## Step 1:
### The first step is to find a good machine.
![The PC I'm using for this project](images/01_my_pc.png)
### Above you can see the mini PC I'm using for this project. As you can see this PC was very affordable costing only $31 on EBAY. You can find many similar machines on the used market although I wouldn't go for anything less powerful than the machine shown here as it works but if I were to do this project again I would opt for something slightly more powerful but this machine gets the job done just fine. The biggest requirement is that the machine must be 64 bit. Many parts of this tutorial will not work on a 32 bit machine
## Step 2:
### Preparing the Antix Linux boot-able USB:
Navigate to the official antix downloads site: https://antixlinux.com/download/ and choose the 64 bit full ISO whatever the newest version is. At time of writing the newest version is 26.1 
![Antix Downloads Site](images/02_Antix_Site.png)


```sudo nano /etc/wpa_supplicant/enterprise.conf```
