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

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/0ded63a0-d861-4be0-ac67-4076c23c36dd)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/44e1b860-05c9-4933-b673-f2147b716919)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/985d4bb7-d21d-4249-b69a-b3897bbe02a4)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/12ebdabc-6b5d-4fa9-9a92-e82e6626ec3c)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/6d363a2a-6d9a-4000-9723-78dd542c5375)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/cf73ce42-6b97-40cf-a151-843aad1f74b9)

It shows the following screen in which the option Google can be selected:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/18768174-b1dc-4651-9abc-710ef1a941f9)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/8bd67ce3-6e92-4171-9c8e-9e9e31c550f4)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/011a71ba-d231-413b-8277-b84bf7ad28b9)

SET logs the information regarding the Google credentials:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/c124a3b6-f1ba-4504-ad2e-74d6e8494e5d)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:

![image](https://github.com/charu-dharshinii/creating-a-backdoor-with-SET/assets/130828943/d54f65d9-50df-479b-acc1-f0bdf3ce17e4)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
