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
![image](https://github.com/user-attachments/assets/965eb02e-be63-4962-8ff8-6eb10b2e0038)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/d75c0820-490a-4680-81cd-a072a862ddf6)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/b4cf211c-a514-4537-8d7e-ac3ad22e4384)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/ae212427-be99-40f8-8945-5f6e200a0d80)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/user-attachments/assets/0d783b9c-18c6-461f-bdc7-5c87475bc7a4)

It shows the following screen in which the option Google can be selected
![image](https://github.com/user-attachments/assets/6c044d95-9989-41bc-81a9-470f935742d7)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/34dd118c-a60d-4e7c-9f59-400491bc9680)

In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/0ce26571-f09e-4c6d-b096-f95b3c892008)

SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/359bb6d8-86d3-4145-89ca-a9704a4af3a5)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/bdba833e-f373-4b3b-b215-2741803d7b89)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
