# EX-7.Creating-a-backdoor-with-SET
## Date:16vcds/10/2024
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

![7_1](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/18c27e46-1e16-4908-902a-0ee8cc739910)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![7_2](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/eb2cdb1f-c010-44ea-b6d8-6f3a5459980c)

It displays the following menu and select 2 for Website Attack Vectors:

![7_3](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/ce13edab-fd6f-4c47-be71-dbc039465ee3)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![7_4](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/43d6257f-b8d0-43e3-af6b-ffc06cf5adce)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![7_5](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/ddf4a871-76a2-49b6-bb84-ba2f214d28c4)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![7_6](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/0b66f632-673c-41f5-8003-ccc549b6497a)

It shows the following screen in which the option Google can be selected:

![7_7](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/d28f26e6-d02c-4482-a55d-0cb35cba6107)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![7_8](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/f46be16f-e375-4d28-a390-47513f012406)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![VirtualBox_Windows 7_16_04_2024_08_56_25](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/ddfca21d-cefc-4324-9b8c-c431c483bdd6)


SET logs the information regarding the Google credentials:

![7_10](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/032532d3-ebf4-4052-a88d-e165b838bc88)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
