# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![1](https://github.com/user-attachments/assets/bc175437-cf78-4313-9897-b16740ed94d3)

### It displays the following menu and select 2 for Website Attack Vectors:
![2](https://github.com/user-attachments/assets/3b05c233-7d2a-4a81-a408-baa5470366ee)


### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![3](https://github.com/user-attachments/assets/a0ea9743-9c0f-4f84-a982-f46ee66a0696)


### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![4](https://github.com/user-attachments/assets/755a1498-db7c-408e-8aad-130790b763d5)


### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![5](https://github.com/user-attachments/assets/a59aad00-2aab-4548-8707-5f8f3fc13e21)


### It shows the following screen in which the option Google can be selected

![6](https://github.com/user-attachments/assets/d8ec99b7-651f-43bb-867a-c3c13d796f4f)

### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![7](https://github.com/user-attachments/assets/79644757-cee9-4fe9-9a95-26f1a2c7cda5)


### In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![8](https://github.com/user-attachments/assets/676a824a-5486-4423-b328-53139c5f60b4)

### SET logs the information regarding the Google credentials:
![9](https://github.com/user-attachments/assets/5eebf51a-a87a-48d8-84b4-3d08db6df245)


### SET logs the information in the xml file under /root/.set directory:
![Uploading 10.png…]()


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
