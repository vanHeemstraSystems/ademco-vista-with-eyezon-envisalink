# 100 - Quick-Start Manual

Source: "EnvisaLink 4 - Quick-Start Manual from EyezOn" at https://www.eyez-on.com/EZMAIN/Envisalink4QuickStart.pdf

Attached: [Envisalink4QuickStart.pdf](https://github.com/vanHeemstraSystems/ademco-vista-with-eyezon-envisalink/files/10471917/Envisalink4QuickStart.pdf)

**NOTE**: For Honeywell (now Ademco) users it is important that you create your EyezOn account and activate the module on the account before you connect it to the panel.

## 100 - Record the 12-digit MAC ID

**Important**: Before installing record the 12-digit MAC ID from the sticker on the module. You will need it during activation.

12-digit MAC ID: **001C2A003303E**

## 200 - ESP Account For Website & Mobile Access

See also "Envisalink 4 Installation & Account Setup" at https://www.home-security-systems-answers.com/envisalink-4.html
See also "EyezOn EVL-4EZR Operation" at https://www.home-security-systems-answers.com/eyezon.html

1. Visit https://www.eyezon.com from any web-enabled device.
2. If you do not have an account proceed to this link https://www.eyezon.com/EZMAIN/createaccount.php and follow the instructions. You will receive a confirmation e-mail with log-in credentials.

Registered with email-account / username / account login id: **wvanheemstra@icloud.com**

Make note of the password as received through e-mail on above account.

3. Log-in to your account (using above account login id and received password) at https://portal.eyezon.com/app/login.php.
4. Click the "Add System" link on the page. 
5. Choose "EnvisaLink Card" as the System.
6. On the form enter the EnvisaLink System Device Type: **EnvisaLink 4 Honeywell**
7. On the form enter the EnvisaLink System Device MAC ID: **001C2A003303E**
8. On the form enter the EnvisaLink System Device Name: **Zanger 4**
9. Submit the form by clicking "Add System". You will see confirmation that the new system has been added to your account.
10. Your device will show in your [account page](https://portal.eyezon.com/app/index.php?page=system-details&param=B5zBQcMvT0w0qOTgRylR6gv3K8N13ZJRO+3EmI53hoh4LY9jj4WogM5Jq+vIV0BjFIC9vJeZPUHXU/4qbUnzzg==&k=), whereas its status may still be **Offline** as we haven't connected it to the WiFi router yet.
11. You should now be able to see the same account details when logged in to your accompanying EyezOn App (for iOS and Android).

## 300 - To Connect the Module to the Control Panel

See also "Envisalink 4 Installation & Account Setup" at https://www.home-security-systems-answers.com/envisalink-4.html
See also "EyezOn EVL-4EZR Operation" at https://www.home-security-systems-answers.com/eyezon.html

1. Disconnect the power from the Honeywell (now Ademco) Control Panel of the Alarm System by powering-down the main panel by disconnecting one battery lead and unplugging the low-voltage transformer. If the low-voltage transformer is not in reach, instead disconnect one of the two power leads from the main panel (Port Nr 1 or Port Nr 2). The system is now no longer powered and it is safe to continue.
2. Connect one end of the supplied 4-conductor cable to the four screw terminals on the EnvistaLink 4 (EVL) module. 

![xenvisalink-4-210](https://user-images.githubusercontent.com/1499433/213917359-beb0353a-a7b7-483e-80f9-9dcc39e40098.png)

EnvistaLink 4 Board

3. Install the EnvistaLink 4 (EVL) in the main panel enclosure. Use the double-sided tape to attach the EnvistaLink 4 board to the interior of the metal housing cabinet.

4. Attach the conneting cables of the opposite end of the cable to the Ports of the Honeywell/Ademco Vista main panel. The ports to connect to are Port 4 - Black, Port 5 - Red, Port 6 - Green, Port 7 - Yellow, colors should match the colors of the connecting cables. These are the same terminals used for keypad connections. Be careful not to dislodge any of the existing data wiring.

![xenvisalink-4-230](https://user-images.githubusercontent.com/1499433/213919012-138527ed-0e05-4a9e-b378-154ef7e3d8ab.png)

Honeywell / Ademco Vista Main Panel

5. Connect a data patch cord from the RJ-45 connector on the EnvistaLink 4 (EVL) module to an open port on your home network router or switch.

6. Restore AC and battery power to the system.

There are a number of LED lights located on your EnvisaLink 4 module. If installation and activation of the module was done correctly, you will see five solid green LEDs with the LINK LED being flashing occasionally to indicate network traffic. The KEYB LED may be off during the first 10 minutes after installation while the module 
downloads Honeywell firmware. Wait 10 minutes before troubleshooting. 

![EnvistaLink_4_LEDS](https://user-images.githubusercontent.com/1499433/213920610-d05e5a40-d4db-45a4-93a4-65a7bfe8e9ce.jpg)

EnvistaLink 4 LEDs

| LED Name | Description | 
| - | - |
| **OPER** | **SOLID GREEN** - Power and functioning. <br> **OFF** – Not functioning and not powered properly. |
| **KEYB** | **SOLID GREEN** – Panel connected correctly. <br> **FLASHING** - Panel not connected (DSC firmware installed). <br> **OFF** – Panel not connected (Honeywell firmware installed). |
| **NET** | **SOLID GREEN** – IP obtained through DHCP server (router). <br> **FLASHING** – Module programmed to static IP. <br> **OFF** – Module cannot obtain IP form DHCP server (router) |
| **ONLINE** | **SOLID GREEN** – Module is communicating with servers and account is properly set up. <br> **FLASHING** – Module is communicating with servers but no account exists. <br> **OFF** – Module is not communicating with servers |
| **LINK** | **SOLID GREEN** – Ethernet link established. Will flick with RX/TX. <br> **OFF** - No Ethernet link. |

**NOTE**: At this stage of the installation all LEDs should show **SOLID GREEN**, where as the **LINK** will **flick** with RX/TX, i.e. data transferring.

For Honeywell / Ademco systems, you’ll have to program the panel to enroll the EnvistaLink 4 (EVL). Follow the latest instructions in the the next section.

For this reason at this stage of the installation you may see the following warning on your [EyezON dashboard](https://portal.eyezon.com/app/index.php):

General Status **On-line**

```Error: Keypad Address Programming Not Completed.```

```Error: *29 Programming on panel not completed properly.```

Type:**EVL4 HW**

MAC:**001C2A03303E**

Version:**202**

Local IP:**192.168.68.112**

WAN IP:**217.103.138.72**

Last Update:** **

## 400 - Panel Programming

See also "EyezOn EnvisaLink Honewell Installation Guide 2018" at https://www.eyez-on.com/EZMAIN/EyezonEnvisalinkHoneywellInstallationGuide2018.pdf

Attached: [EyezonEnvisalinkHoneywellInstallationGuide2018.pdf](https://github.com/vanHeemstraSystems/ademco-vista-with-eyezon-envisalink/files/10474565/EyezonEnvisalinkHoneywellInstallationGuide2018.pdf)

Accessing EnvisaLink 4 Locally. Now that your Envisalink4 is connected to your Honeywell Panel and functioning, you may have to access the EnvisaLink 4 locally in order to program your EnvisaLink 4. The Envisa Link 4’s local web interface also allows you to view status and perform troubleshooting. For more information on accessing your Envisalink4 locally, please refer to the Accessing Envisalink4 for Status, Programming and Troubleshooting Application Note.

1. To access the EnvisaLink 4 web interface, type the EnvisaLink 4 IP address into any browser on the same internal network as your Envisalink4. For help on obtaining your Envisalink4’s IP address please refer to the Accessing Envisalink4 for Status, Programming and Troubleshooting Application Note.

```
http://192.168.68.112
```

EnvistaLink 4 Local Web Interface (Note: some browser settings will not allow access to a website with unsecure http, try opening the web interface from your smart phone in that case if it is connected to the same network).

2. Once entered, a login pop-up should appear. Enter ```user``` in both the User Name and Password fields and click Log In.

Once you have logged into the web interface, the local EnvisaLink 4 homepage will appear as seen below. This page allows you to assign and/or modify keypad addresses for each partition used on the system; as well as enable IP shadowing if the system has a Honeywell ECP IP/GSM or LRR already installed. 

![EnvistaLink_4_Home_Page](https://user-images.githubusercontent.com/1499433/213921580-b34d9519-d113-48d4-9079-1d853bf93847.jpg)

EnvistaLink Home Page (may differ from your home page)

### Envisalink4 Programming Options: Assign/Modify Keypad Addresses & Enable Shadowing

Honeywell Vista Panels require that each connected keypad has a unique address between 16 and 23. On all Honeywell systems, the first keypad uses the address “16” and is therefore reserved. The EnvisaLink 4 emulates a keypad on the system and by default uses the address “18”. By default all other partitions are disabled with address 
“00”.

The degree to which you need to assign and/or modify addresses depends on the number of partitions, communicators (e.g. a GSM backup), and keypads on your system. 

Generally, **if you only have one partition, no additional communicators, and less then three keypads, no modification to the default EnvisaLink 4 address settings is required.** 

In this scenario keypad 1 and 2 would typically have the addresses 16 and 17, and the EnvisaLink 4 would be addressed as “18”. 

However, you should verify that the keypads indeed are using addresses 16 and 17 by following the instructions in Step 1 and Step 2 below. 

If you have an additional c IP, GSM, or Long Range Radio (LRR) communicator already installed, you need to enable IP/GSM/LRR shadowing as outlined in Step 3 below.

For systems, with more than one partition and more than two keypads, additional address assignment is required. 

In order to assign keypad addresses correctly via the local web interface, you need to know how many existing keypads are on your system and what addresses they are using. Any duplication will cause issues when arming and disarming via the portal. To do this, follow the steps below:




More ...
