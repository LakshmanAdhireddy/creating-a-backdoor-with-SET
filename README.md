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

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/eb4f79ff-b640-47fe-a44a-735186d64da5)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/febb72f0-0b50-4b74-b7a7-2800e20c6aa1)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: 
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/7660baef-bb01-4878-a9e3-d4add0813d60)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/200e1c34-a89e-41bf-9c6d-85b956e7b983)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/e760e4d8-4833-440f-bec3-050c9f106d25)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/cd72fa7a-2e99-49b9-ac04-c311b84660ca)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/fa07de40-ee1f-4474-8515-5aa96c42bf95)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/1e582840-c502-489b-998a-d473f2645a59)

SET logs the information regarding the Google credentials:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/4db01f1b-e9a7-4b69-81bd-2d92ae9b001c)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/LakshmanAdhireddy/creating-a-backdoor-with-SET/assets/118707265/6c9ebcd6-22f4-4961-bddc-50b47e7acc46)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
