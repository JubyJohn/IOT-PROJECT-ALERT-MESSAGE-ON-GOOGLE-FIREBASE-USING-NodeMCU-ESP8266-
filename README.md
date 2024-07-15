# IOT PROJECT: ALERT MESSAGE ON GOOGLE FIREBASE USING NodeMCU ESP8266


## AIM

To create a Firebase project with a realtime database and show alert messages of tilting in the database using the ESP8266 interfaced with tilt sensor


## COMPONENTS
1.	ESP8266 NodeMCU
2.	Tilt Sensor Module
3.	Jumper Wire
4.	USB cable 


## CONNECTION

### Tilt Sensor Module Pin Diagram

 ![Tilt-Sensor](https://github.com/user-attachments/assets/60f2b05e-430c-45cb-ab67-29e11d232db8)

<br> GND   = ground   ---->  GND
<br> +    = power supply  ---->  3V3
<br> S  = Output     ---->  D2


## PROCEDURE

<br> Step 1 : Create a Firebase Project
<br> Step 2 : Interface ESP8266 microcontroller to Arduino IDE using port.
<br> Step 3 : Interface ESP8266 microcontroller with tilt sensor to test tilt activation
<br> Step 4 : Install the Firebase-ESP-Client Library.Then, program the ESP8266 to Interface with Firebase
<br> Step 5 : Need to insert your network credentials, URL database, and project API key for the project to work.


## PROBLEMS FACED

### Error 1 -   Firebase-ESP-Client Library installation
<br> How to rectify:
<br> (1)  Need to find suitable library
<br> (2)  Open above link address -> download ZIP file
<br> (3)  Go to Arduino IDE -> sketch -> include library -> add ZIP file -> downloads -> select downloaded zip file -> close

### Error 2 -   Token info: type = id token, status = on request <br> Token error: message: is not connected  <br>  Token info: type = id token, status = error
<br> How to rectify: 
<br> This issue faced because of poor network connection. Try to find a stable network connection and upload.


## OUTPUT

![IMG 1](https://github.com/user-attachments/assets/eb8d831e-3bf7-468e-b1e4-ce3759237800)

![IMG 2](https://github.com/user-attachments/assets/d2e77ce7-f823-4b29-9f7a-f89ea0676b0c)


## REFERENCES

<br> Google firebase project creation : https://www.javatpoint.com/iot-project-google-firebase-nodemcu
<br> Google firebase using project : https://github.com/JubyJohn/IOT-PROJECT-GOOGLE-FIREBASE-USING-NodeMCU-ESP8266-
