## update 21 mar 2023 - Latest PCB Renders!!
![octo-nail pcb render](https://user-images.githubusercontent.com/77303173/226526907-99108d75-a079-4c98-af4f-e84791d6e445.PNG)
![octo-nail pcb render -rear](https://user-images.githubusercontent.com/77303173/226526909-b35d7bec-a3cf-4b6a-98d7-42a5cf39cd9f.PNG)



## update 20 Mar 2023
rebuilt again on an even more compact breadboard. swapped out manual setup and v1 web server stuff for wifimanager. lost the ability to set temp via webui, and ota. but i think wifi manager will handle ota as well as config, and of course wifi setup

## update 10 Mar 2023
I rebuilt the circuit on a different breadboard, both to clean it up, and to make sure my documentation & pinout was accurate. I started porting the code to platformio, but at least one of the libraries has issues. They seem to be related to the order in which things are declared, which in Arduino IDE doesn't seem to matter.

# Introducing: octo-nail

<img width="1136" alt="Screenshot 2023-03-09 at 6 23 22 PM" src="https://user-images.githubusercontent.com/77303173/224183178-4bfc4e5c-6dd7-4ff2-a909-5440e30c8144.png">

[why octo-nail? I like octopuses]

Currently running on an ESP-32s2 (lolin s2 mini) devboard.

Supports OTA firmware updates, and setting the target temperature via a (rudimentary) web interface.

Still in the prototyping phase, but nearly ready to order PCBs.

This project is less an exercise in developing a revolutionary product, and more a learning experience. That being said I haven't seen any mains-powered e-nails that actually impress me. The gold standar seems to be slapping an OTS PID controller and (way over spec'd) solid state relay in a box with xlr and AC power jacks. The first time I had an idea to build an e-nail was about ten years ago, but beyond some basic googling it never went anywhere. 

More recently I've done a bit of hobby level work with ESP 32 (and previously 8266) boards, and have kind of been sucked in. I figured that an e-nail project would require me to learn a lot: embedded system/c/c++ development, open source code and licensing, code management, git, github, ota updates, schematic and pcb design, rotary encoders, thermocouples, heating coils, solid state relays, pid algorithms and tuning, spi, embedded display, embedded GUI, squareline studio, xlr connectors, mains voltage, effective prototyping, piezo buzzers, rtttl ringtones, larger-scale c/c++ projects, using open source libraries, web servers, input from web servers, esp-idf, youtube videos, sharing on social media, reliability, signal interference, Arduino_GFX and TFT_eSPI libraries, the list goes on...

If you've read this far thank you for your interest, I'd love to hear from you with comments, criticism or ideas. The sky is the limit with this project. 
