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
![272231868-1f00a8ab-72ac-4321-89fb-ac15f895a946](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/7513f284-68cb-4e09-bc1d-90f486933271)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![272231948-aa82f071-9ca8-4d25-9d12-d2239f14f9f1](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/634eb63e-7e90-4968-ba41-de3d64c9ee40)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![272232052-38fd2691-08b4-4e76-9599-0061728cfd38](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/9f578622-c154-452c-98e9-af0c10d24fd0)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![272232127-cee0361c-9f61-4ee4-9357-1aa49e61a598](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/a635f190-cd74-440d-bcf4-f4cec913fbc0)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![272232174-362616f8-bf73-402c-80c7-1f59d2778754](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/38724d4c-9d55-4b69-a54d-6329d14fbfdf)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![272232232-ad1ec8f3-3e18-43ea-b520-2673e75400a0](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/a51bab8a-3f41-48c8-ab6c-19e6c3bd2f7e)

It shows the following screen in which the option Google can be selected:
## OUTPUT:
![272232274-b54b125a-8192-4fd6-ba84-c23a4e1331b6](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/dd6178fa-afe6-497d-9090-ed9f6366b118)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT:
![272232315-381f52f9-677f-41e6-879d-f9e14e5063cc](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/efa0ee7f-780c-4736-9198-24005898b2ee)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
## OUTPUT:
![272232367-bab281ee-dccc-4511-963b-79b9fd9360bb](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/fc2a5b18-3c3e-4d2f-83b1-8d1067865497)
SET logs the information regarding the Google credentials:

## OUTPUT:
![272232411-1f91e817-81e3-4ed0-98dd-75145842e812](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/1c75c8ec-7347-4645-9e2f-40720762a22a)

SET logs the information in the xml file under /root/.set directory:
## OUTPUT:
![272232475-441b35f3-839d-4030-bd35-6f040ddc093b](https://github.com/Aakash0407/creating-a-backdoor-with-SET/assets/118799103/06d5db77-2afb-4854-8890-f62338c2e619)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
