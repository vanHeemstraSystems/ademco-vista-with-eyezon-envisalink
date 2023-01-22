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

More ...
