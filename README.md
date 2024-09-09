# Working-Mouse-Example-For-Pic32MX
This project is to serve as a working plug and play example of the Microchip PIC32 USK USB Device - HID Mouse Demo on the PIC32MX250F128D using the xc32 compiler.
The initial demo project can be found here at https://www.microchip.com/en-us/development-tool/DM320003-2 under the documentation tab.
The Debugger used is the SNAP Debugger.

The Dev board to be used in this example is the Fubarino Mini which can be purchased at https://www.fubarino.org/mini/
This dev board was chosen, because it is one of the cheapest Pic32 dev boards available on the market at $21.95.

The problem is the demo example was not meant to be run on the mcu that comes on the Fubarino Mini (PIC32MX250F128D).
The demo was meant to be run on the PIC32MX470F512L which appears on the DM320003-2 Dev board which starts at $92.90.

The only modification that needs to be done to MPLab is to install the PIC32 Peripheral Library for the xc32 compiler.
The download link can be found at https://www.microchip.com/SWLibraryWeb/product.aspx?product=PIC32%20Peripheral%20Library
Once it is downloaded it has instructions on how to install the extra libraries needed. 
NOTE: Some Fubarino Mini come equipped with the PIC32MX270F256D. This chip is essentailly identical to the PIC32MX250F128D, but it has greater amount of memory.
If you do have the PIC32MX270F256D just change the chip type in the project properties.
