# 4 channel home automation android app

This code uses a 4 channel relay, HC05 bluetooth module and arduino pro mini. Warning: This schematic requires you to open the electric sockets and change their wiring.
The best feature of this code is that it enables you to controll the appliances normally with switch too.

Once the switch has been turned on from the app you can turn it off from the app as well as toggling the main switch twice.(if applaince is on from switch but you turned it off from app then to turn it back on from the switch you will have to toggle it twice).

For the app I hace used taske app which you can fing on play store along with a plugin called 'Bluetooth Serial from tasker' which also you can fing on playstore.
Once you have installed both the apps, you can directly restore my tasker back attached which will create 6 commands for turning on and off 3 relays. You can then add widgets for these tasks easily from home screen.

Note: To restore the backup of tasker, place the backup file in the folder "/Tasker/configs/user/". Place the backup.xml file in 'user' folder.

You will have to pair to the hc05 module and edit each task's bluetooth device to your hc05 module... currently it is sending the commands to my hc05 module so configure it for your module. For this go to each task> got to Bluetooth serial > tap the edit icon on top right next to configuratio> Tap show all bluetooth devices> Select your hc 05 module.

Note: You can even change the command for each relay here.
