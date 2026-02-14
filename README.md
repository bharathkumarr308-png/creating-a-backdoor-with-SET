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

## OUTPUT
<img width="669" height="500" alt="image" src="https://github.com/user-attachments/assets/de47351c-8f90-4f50-abeb-3ea24a0aafce" />
It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT
<img width="1026" height="443" alt="image" src="https://github.com/user-attachments/assets/bce60126-aa46-4013-97f6-d2c0c10fbd9f" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="793" height="300" alt="image" src="https://github.com/user-attachments/assets/cec6c7b7-6985-4e45-a40b-abe14d9e84a7" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="767" height="728" alt="image" src="https://github.com/user-attachments/assets/37828d49-21a5-439d-8f40-90e31cbcafbb" />




It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1195" height="167" alt="image" src="https://github.com/user-attachments/assets/d2494479-5c48-4189-ae5a-2090257b335e" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1070" height="808" alt="Screenshot 2026-02-13 092857" src="https://github.com/user-attachments/assets/4ecd9b7d-e74a-4c50-a3ea-e3dc1a486d2b" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1298" height="122" alt="image" src="https://github.com/user-attachments/assets/d8dde557-0517-4472-8860-62d69bcf8eac" />

SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1600" height="268" alt="image" src="https://github.com/user-attachments/assets/dbe9384b-b8b0-47c4-917c-b3b2343a6243" />



SET logs the information in the xml file under /root/.set directory:


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
