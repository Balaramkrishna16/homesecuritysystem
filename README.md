# homesecuritysystem

define FIREBASE_HOST "your-project.firebaseio.com"  ** Remove "https:" 

delay(10000);  ** Lock remains active for 10 seconds

digitalWrite(RELAY_PIN, LOW);  ** Unlocks door again (optional) If you are in demo use this line 

delay(500); ** check every 0.5sn (Used to check the status)
