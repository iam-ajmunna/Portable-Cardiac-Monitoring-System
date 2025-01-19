# Install ArduinoIDE
- Go to the [ArduinoIDE](https://www.arduino.cc/en/software) page
    - Click **Windows**
    - Click **Just Download**
    - Again, You don't need to enter or tick any information. Click **Just Download**
    - ***Done***

# Set Libraries on ArduinoIDE
- For STM32F103C8T6 Microprocessor
  - Launch Arduino IDE. Click on the "File" menu and then "Preferences".\
      The "Preferences" dialog will open, then add the following link to the "Additional Boards Managers URLs" field:
    ***"http://dan.drown.org/stm32duino/package_STM32duino_index.json"***. 
    
    Click "Ok"
  - Click on the "Tools" menu and then "Boards > Boards Manager." \
    _The board manager will open, and you will see a list of installed and available boards._ \
    Select the "STM32 F103Cxxx" and click on Install. \
    _After installation is complete, an "INSTALLED" tag will appear next to the core name._ \
    _You can close the Board Manager._ \
    _You can find the STM32 boards package in the "Board" menu._ \
    Select the desired board series: STM32F103Cxxx \
    Select the board. \
  > This instructions are taken from [**Autodesk Instructables**](https://www.instructables.com/Getting-Started-With-Stm32-Using-Arduino-IDE/)
