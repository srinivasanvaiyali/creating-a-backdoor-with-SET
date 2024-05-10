
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

![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/ffff19f3-adc5-4809-a8e2-02d4cfbb18b2)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/149774a9-e181-4665-b340-c830a75f8712)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/6234465b-a535-41ae-a455-5927035f0c54)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/d7ee8bb4-ff2e-48c3-bbf2-c1ae9889aa1b)


it shows the following screen in which the ip address of the attacker need to be given which is the default value:


![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/484868bb-86f6-4625-ab66-6b410383ac1c)


It shows the following screen in which the option Google can be selected:


![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/49e92d97-6dcf-42a2-a751-d86d8aed4be5)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:


![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/cab7c328-f330-4b93-a81a-9cea84022014)


In windows IE, on giving the url http://192.168.43.135, the fake Google page is displayed. The victim can enter the username and password: 

![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/831900c6-86c0-4c36-a19f-b70fb408781b)

SET logs the information regarding the Google credentials:

![image](https://github.com/srinivasanvaiyali/creating-a-backdoor-with-SET/assets/145117665/72677edb-c703-411b-9e87-41367c8c585e)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
