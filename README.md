# EAGO-BOARD-RED- V 1.0 #
## Documentation for Eago Board v1.0 red board ##
### EAGO EVALUATION BOARD ###
Edited by Benson Muchemi
#### Description ###
The Eago development board contains a series of Microcontroller boards compatible with STM32Cube IDE and Arduino IDE.
Also contains ESP microcontroller(ESP8285) that are on-board and compatible with arduino with pinout extension and enables wifi connectivity.
Eago V1 kits and boards ship with an STM32F103 Chip packaged in a manner that is both beginner friendly and also feature-packed for intermediate hobbyists.
The Eago V1 board has its shield compatible with the board.
At the core is 72MHz ARM Cortex M3 with 64Kb of flash memory. The board ships with an inbuilt USB to Serial interface(cp2102) making it easy to program and SWD interface for easy debugging.

# Specification
* 32-bit ARM Cortex M3 clocked at 72MHz 3.3v logic
* 64 Kb of flash memory
* 20 Kb of SRAM
* 72 MHz clock and 32kHz clock for RTC
* 2 USART interfaces
* 7-channel DMA
* 5-90V DC input voltage
* On-board SIM Module with antenna
* USB Support (MAX3421E)
* On-board programming interface (CP2102)
* SWD Interface
* Wifi interface(esp8285) with antenna

## wifi specifcations ##
* ESP8285H16
* 2 MB flash memory 
* 802.11 b/g/n support
* 802.11n support (2.4 GHz), up to 72.2 Mbps 
* PCB Trace
* Embedded TCP protocol
* Interface: HSPI, UART, I2C, I2S, Remote Control IR Controk, PWM, GPIO
* Direct WiFi Support (P2P)
* Built-in Tensilica L106 ultra-low power 32-bit microprocessor, supporting 80MHz and
  160MHz at the main frequency, supporting RTOS
* Built channel 1 10 bit high precision ADC
* Peripheral interface HSPI, UART, I2C, I2S, IR Remote Control, PWM, GPIO
* Deep sleep keeps current at 10uA and shutdown current is less than 5uA
* Wake up, connect and pass packets within 2 mS
* Standby power consumption is less than 1.0mW (DTIM3)

     ## Eago group,Eago Developers’ Kit and Developers’ Board ##
The Eago Developer Boards and Kits aim to provide an easy path for IoT newbies and hobbyists to get started with easy tests for hardware development , firmware development , training and data publishing and subscription using GPRS and wifi chip on board.

   ### Getting Started ###
The Eris Developer Board and Kit can be programmed using [Arduino IDE](https://www.arduino.cc/en/software) ,[PlatformIO](https://platformio.org/) or [SMT32Cube](https://www.st.com/en/development-tools/stm32cubeide.html).
Select a preferred development environment and configure your setup as detailed below.

   ### Arduino IDE ###
Download and install Arduino IDE for your preferred platform by selecting an installable package from the [Arduino Software Downloads page](https://www.arduino.cc/en/software).
Learn more about setting up Arduino Cores by following the Arduino Guide [Arduino Guide](https://www.arduino.cc/en/guide/cores).

 __Setting up STM32Duino Core (recommended)__.
1. On Windows and Linux-based OS’es, to setup STM32Duino Core, launch the Arduino IDE and navigate to File > Preferences options on the Arduino IDE menu bar.
2. In the Preferences window, paste the link https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json inside the Additional Boards Manager URLs input box and save it by clicking OK.
On MacOS,the Preferences menu can be accessed by clicking on _Arduino > Preferences_ from the App menu.
3. Under the _Tools_ option in the menu bar, Select Board and on the resulting palette window select _Boards Manager...._
   For full instructions on using the "Boards Manager", see the [Getting Started page](https://github.com/stm32duino/wiki/wiki/Getting-Started).
4. On the _Boards Manager options_, set filter to _Contributed_ and type _STM32 Cores_ in the search box. Then click on _Install_ .
       If you run into any issues consult the[documentation](https://github.com/stm32duino/wiki/wiki/Getting-Started)..

__PlatformIO__
1. Install PlatformIO as detailed in the [installation options page](https://docs.platformio.org/en/latest/core/installation.html#installation-methods).
2. Install STM32 platform support by running the following command from your terminal.


    `pio platform install stm32`


https://docs.platformio.org/en/latest/core/installation.html#installation-methods
