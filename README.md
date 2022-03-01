# WLED Printer Install

## Prereq

 - ESP8266/ESP32 Style board compatible with WLED 
 - 5V shielded cable such as USB 2.0, or a twisted pair like ethernet (Other options are fine.)
 - USB cable for setup\*\*
 - Solder & Soldering Iron (*flux is a nice to have*)
 - Crimping Tool
 - JST or Dupont connectors suitable for PCB mount (*directly soldering wires to the board is possible but not adivsed*)
 - JST SH or Microfit connectors to simplifiy maintenence the LED strip
 - PC with Chrome or Edge browser.\*

Some tested/validated hardware reccomendations can be found linked in the [Recommended](#recommended) section.


## Hardware Setup

### Wiring the Board

### Wiring the LED Strip


  

## Software Setup
### 
#### Web Flash
1. Connect your D1 Mini to your computer via USB
  - Identify the COM port
  - Fixing Drivers [Fix Drivers](#driver-fix)
1. Navigate to https://install.wled.me/
1.
1.
1.

#### Moonraker 
https://moonraker.readthedocs.io/en/latest/configuration/#wled


### 

###




## Printer Setup
###

###

###




##### Recommended

Only links to items that have been tested are included in this section
There are no affiliate or tracking Links (screw that)

D1 Mini (clone's)
- [https://www.aliexpress.com/item/32651747570.html](Win Win - Aliexpress)
- [https://www.amazon.co.uk/AZDelivery-D1-Mini-Development-Compatible/dp/B0754N794H/](AZDelivery - Amazon UK)
**! Avoid ESP32-C RISK-V boards for now**

Shielded Cable / Twisted Pair

Shielded - [https://www.amazon.co.uk/gp/product/B00NH13DV2](Amazon Basics USB 2.0 Cable 3M/10feet - UK)
Twisted Pair -[https://www.amazon.co.uk/Snagless-Ethernet-Network-Compatible-Consoles-Grey/dp/B08DCQMKTC/](Cat 5e)



Connectors
- Cable connectors
  - JST SM (no link)
- PCB connectors
  - JST XH (no link) 


Crimping Tools
- IWISS IWS-2820M *or* ENGINEER PA-09 style 

Soldering Iron
- [https://pine64.com/product/pinecil-smart-mini-portable-soldering-iron/](PINECIL) - My personal preference 

Solder
- For this application 

Flux (optional)
- [https://www.amazon.co.uk/MG-Chemicals-Pneumatic-Dispenser-Dispensing/dp/B00425FUW2](MG Chemicals - Amazon UK)
- [https://www.amazon.com/MG-Chemicals-Pneumatic-Dispenser-Dispensing/dp/B00425FUW2](MG Chemicals - Amazon US)



##### Driver Fix



\* ESP32-C boards are not compatible at present
\*\* The USB cable can be used for power if using a limited number of LED's **OR** 


// WiFi Install (easiest)

#### 1
(asuming windows)
Connect D1 Mini to PC via USB 
Visit - https://install.wled.me/v2.htm  using Chrome or Edge 
Click Install - A pop up should appear to select your D1 Mini
    - Click ok and it should flash (if not you can try hitting the reset/boot button on the D1 Mini)

If there is no device OR the device has an error in Device Manager.

Download > The lates Zadig from https://zadig.akeo.ie/ 
    - Install the libusb-win32 option
    - Retry the web install

#### 2
Open your computer WIFI and connect to the WLED-AP network the ESP is now broadcasting.
 password is - wled1234

Once connected visit - http://4.3.2.1

Click the Cog and select WiFi Setup to add your home network.
Save

Connect to your home WiFi, and query your Router for the new IP (or try http://wled.local)


Full Docs: 
https://kno.wled.ge/


So done some basic fitment testing.
Galilleo is a no go as the planetary gear hub,  (pic to follow)
CW1 and By proxy LGX Lite (using MrgrMrgr's mounnt) are fine leaving 1-1.5mm between the Stepper and the Gland (when fitted)
CW2 - I dont have.



 using a CW1 as a standin for the LGX (they are <1mm difference once fitted.



Initial findings - any boards mounted to the back of the stepper will deflect or outright block the Gland