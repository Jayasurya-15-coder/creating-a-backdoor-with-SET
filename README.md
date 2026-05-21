# Creating a backdoor with SET - Ethical Hacking Techniques course

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

<img width="538" height="876" alt="Screenshot 2026-05-21 092856" src="https://github.com/user-attachments/assets/a636d387-f085-4555-9786-fa9a5de68e16" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT


<img width="450" height="210" alt="image" src="https://github.com/user-attachments/assets/664da56c-2715-4c81-baf8-e343ff5ca25a" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1050" height="597" alt="Screenshot 2026-05-21 083345" src="https://github.com/user-attachments/assets/248c79b9-4cc1-4926-abd6-b4a55f49e6cb" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="852" height="540" alt="Screenshot 2026-05-21 083522" src="https://github.com/user-attachments/assets/3f0f9663-c956-4210-b8bf-23b1e07cca91" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="852" height="540" alt="Screenshot 2026-05-21 083522" src="https://github.com/user-attachments/assets/76ab50be-b34e-496d-a49c-0a1bfd13894c" />


It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="480" height="221" alt="image" src="https://github.com/user-attachments/assets/e67326a3-5312-4831-af82-a4ffbaec051d" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="677" height="192" alt="image" src="https://github.com/user-attachments/assets/2eaea227-57e0-4b34-8afc-47053cfc651d" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

![Uploading Screenshot 2026-05-21 092439.png…]()

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1332" height="365" alt="Screenshot 2026-05-21 092457" src="https://github.com/user-attachments/assets/39707aef-e2a4-47a2-a341-d87e29517cb0" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
