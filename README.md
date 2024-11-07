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

![image](https://github.com/user-attachments/assets/6306b290-0323-44b0-aec0-ce5a2e1b6fd0)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/1d82bf14-b43e-4001-93e3-fe2fc0c59538)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/b8f3e347-0b97-415c-b98d-ef6f60eeaea2)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/fe5824b8-aa25-4e25-a265-016a296a32c6)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:


![image](https://github.com/user-attachments/assets/cea43a04-d84d-4c69-bd81-bf72c8ff7c67)

It shows the following screen in which the option Google can be selected


![image](https://github.com/user-attachments/assets/1a938947-5a6c-4b94-a84b-a4e0ff079baf)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:


![image](https://github.com/user-attachments/assets/be21572a-4a59-46d3-a54c-883b05255ead)

In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password


![image](https://github.com/user-attachments/assets/4e342548-b660-4eb0-b13a-ac1694096e95)

SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/32ccd435-9c9a-42d1-8038-6858e0c6afe1)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/cd45e41d-99e5-47a3-89d4-f10be27d3e1a)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
