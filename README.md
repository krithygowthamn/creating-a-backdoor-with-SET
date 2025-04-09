# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course
## NAME : GOWTHAM N
# REG NO: 212222220013
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
![image](https://github.com/user-attachments/assets/c3a8ccd5-685b-4a77-92aa-972ba64cc409)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/22681247-1a23-46df-983d-50e39e132f76)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/60578e77-9f25-455f-85e1-fb7a2b3b2484)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/ba3496ed-b959-4272-b6fa-25c910f72a7f)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/user-attachments/assets/07d0612a-bfa2-48b3-8ddb-5daca7ad8436)
It shows the following screen in which the option Google can be selected:
![image](https://github.com/user-attachments/assets/a50c933c-a529-4e6c-a19b-cc0ecbad0506)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/2d179e4f-9f5a-4bf1-81c1-6f603e65902e)
In windows IE, on giving the url http://192.168.192.189, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/8ebbe337-84a6-4872-a023-bbc1f5c37e76)
SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/68ccd9a4-8927-4b68-9a5f-f21a305ee3ea)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
