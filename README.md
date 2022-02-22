## Smart-Home-Automation

The Home Automation System was made with Arduino based microcontroller Node-MCU coupled with a relay board 
and a few jumper cables. To top everything the output is presented in a way that shows how to project works and how 
the appliances can turn on/off according to the instruction we give to it.

# Components

+ Node-MCU
+ Relay Board
+ Jumper Wires
+ Micro USB Cable
+ Switches
+ Amazon Alexa (Optional)


# List of inputs / Output

+ Gather around all the components in the list
+ Go to the web browser and search for the latest tasmota firmware
+ Download the “tasmota.bin” file and the tasmota software itself
+ Open the software and plug your microcontroller to your computer
+ Press refresh in Select Port menu, it would automatically select the port for the board
+ Select the “self-resetting device” option
+ Upload the file and click the button which says “Tasmotize!”
+ Wait for it to upload then press on “Send config”
+ Enter your Wi-Fi Credentials and press save
+ Wait for about 5 to 10 seconds and press on “Get IP”
+ Copy the IP-Address for the field
+ Open your browser and paste the IP-Address you copied
+ Go to Configuration -> Configure Module -> select Generic (0) from the Module type
+ Click on save, Go to main Menu
+ Go to Configuration -> Configure Module -> and select the pins mentioned in 2.2.2
+ Press save and go to Main Menu

#  Setting up Alexa:

+ Go to Configure -> Configure Other -> Enter the Project name / Switch names
+ In Emulation select Hue Bridge and press save
+ Open your Amazon Alexa app and add devices
+ Follow the procedure in the app and you would be prompted with 4 devices
+ Set them up through the app

