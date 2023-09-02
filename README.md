[![Telegram](https://img.shields.io/badge/join-telegram-blue.svg?style=for-the-badge)](https://t.me/+W4rVVa0_VLEzYmI0)
 [![WhatsApp](https://img.shields.io/badge/join-whatsapp-green.svg?style=for-the-badge)](https://chat.whatsapp.com/FkNC7u83kuy2QRA5sqjBVg) 
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/PCB-Prototyping-Catalogue?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/l6unzfyg9q2db2xgpphl" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/AeonLabs-InnoTech-Intelligent-Weight-Scale.svg)

<p align="center">
   <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/smart_solar_cell.jpg" height="300">
</p>

[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>  [Home-Automation](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Home-Automation)  >>   Distributed Power Storage


# Distributed Power Storage

**The problem**

Now that a universal cable connector is a reality, the USB-C, the next big change is on how to remove all those power converters and inverters at home, vis-a-vis, " power bricks". These can waste up to 30% of electricity "converted". And in my professional opinion, the best and only way to do it is by adding a small mechanical switch, however, mechanical relays consume too much power (around 200mW). 

<br>

**The ideia**

To solve the 30% wasted on conversion, the only way is, to reduce to the minimum "power bricks" needed /required. This can be achieved by installing several electricity lines in parallel connected to each power outlet in a room, nowadays with built-in USB connectivity. USB-C power delivery is capable to manage automatically powerlines up to 20V 5A DC meaning all indoor LED illumination, laptop computers, smartphones & tablets, and all smart devices including big OLED TV screens.

One possible solution to solve electricity consumption in standby mode is by using a micro stepped DC motor connected to simple electronics with "deep sleep" with or without wireless capabilities. This way is possible to lower consumption to 2-8uA @ 3.3V DC.

The main objective of this project is to negotiate power delivery to each individual power outlet sockets from a master Distributed Power Management System. Is possible to achive this using only 2 wires where one of them is used for both power and data transmission. There's a really good one-wire library [here](https://github.com/M-o-a-T/owslave) that enables one to build such power delivery setup.

<br>

If you prefer, can read about my prototype iteration tests on Hackster.IO. Here's the [link](https://www.hackster.io/mtpsilva).

<br>

## Electronic Devices Prototyped
- [45,000mA Power Wall using 18650 Lithium Polymer Batteries](https://github.com/aeonSolutions/AeonLabs-HomeAutomation-45-000mA-Power-Wall-18650-Lithium-Polymer-Batteries)

  Here in Belgium, is often found all kinds of home appliances when walking on the sidewalk. And anyone is free to take them. Gratis. The other day i picked up on the street this blue ray device. And, as i always do, the first thing i did was to disassemble it to its individual parts and components. It has capacity for 45,000mA @ 4.2V DC, More than enough for powering of the grid all 5-9V DC  devices and appliances at any family home. During winter days , rainy days, this power 🔋 wall will charge itself from the main 220V AC but only during the night when electricity is much cheaper. The estimated savings on the electricity bill at the end of the month are expected to be between 10eur to 20eur. Payback time is only 10 months. The minimum efficiency of this power wall is 95%  With an LCD display for some cool consumption statistics and three buttons for ......I don't know yet ! 

<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-HomeAutomation-45-000mA-Power-Wall-18650-Lithium-Polymer-Batteries/blob/main/media/WhatsApp%20Image%202023-09-02%20at%2014.37.48.jpg" height="200">
</p>

<br>

- [Automatic Power Delivery USB DC Power Outlet]() ( soon. stay tuned)

This is a smart device made to fit this EU 220V power outlet with 2 USB A port selling [here](https://s.click.aliexpress.com/e/_DlU2D7j).  This smart device enables power delivery management on low powered DC lines, in the range of 3.3V to 20V DC and up to 100W. Each individual USB-A port can be setup to deliver individual DC output. For instance 5V DC on one port and 12V DC on the other.  The innovation on this particular smart electronics is in its ability to deliver USB power with the capability of automatic negotiation of voltage from anywhere between 5V and 20V and up to 100W.  While this project does not start, here's a great [video tutorial](https://www.instructables.com/DIY-USB-Type-C-Power-Delivery-Trigger-Board/) by GreatScott.  

<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-AeonLabs-HomeAutomation-Distributed-power_storage-Selectable-USB-DC-power-outlet/blob/main/media/power_outlet.jpeg" height="200">
</p>

<br>

- [78x39mm Solar Cell Management 5V, 9V, 12V DC up to 9A Max](https://github.com/aeonSolutions/AeonLabs-homeAutomation-78x39mm-solar-cell--Power_Management)

This PCB is for assembly with [79x38mm solar cells](https://github.com/aeonSolutions/AeonLabs-homeAutomation-78x39mm-solar-cell/tree/main). It features up to 6x independent solar cell power lines, with up to **97.1 % of efficiency**, that can be configured by a dip switch for 3 different DC outputs: 5V, 9V, and 12V ( 9A max).

<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-homeAutomation-78x39mm-solar-cell--Power_Management/blob/main/media/kicad_63WVZY1xpR.png" height="200">
</p>

<br>

- [Selectable USB DC Power Outlet](https://github.com/aeonSolutions/AeonLabs-AeonLabs-HomeAutomation-Distributed-power_storage-Selectable-USB-DC-power-outlet/tree/main)

This is a smart device made to fit this EU 220V power outlet with 2 USB A port selling [here](https://s.click.aliexpress.com/e/_DlU2D7j).  This smart device enables management of multi low powered DC lines, in the range of 3.3V to 24V DC. Each individual USB-A port can be setup to deliver individual DC output. For instance 5V DC on one port and 12V DC on the other.  

<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-AeonLabs-HomeAutomation-Distributed-power_storage-Selectable-USB-DC-power-outlet/blob/main/media/power_outlet.jpeg" height="200">
</p>


- [Smart Battery Management](https://github.com/aeonSolutions/AeonLabs-AeonLabs-HomeAutomation-Distributed-power_storage-Smart-Battery-Management)

This is a simple PCB for a direct fit on commercially available [blue solar cell tiles](https://s.click.aliexpress.com/e/_DCnJW0V) to do active solar cell tile and battery management up to 8 solar tiles conencted together intended for indoor usage. In particular to be installed on the top or downside of transparent glass windows at a home or office. This PCB, when assembled with a blue solar cell tile, can be used to power a low voltage 4.2V indoor illumination network using ultra-low power micro LED strips.  For insatnce [this one](https://s.click.aliexpress.com/e/_DCKg9xJ) sold on AliExpress.   

<p align="center">
<img src="https://github.com/aeonSolutions/AeonLabs-HomeAutomation-Power-Managment-Solar-Cell-offgrid-Power-Monitor-for-Indoor-Window-Tiles/blob/main/Designs/pcb_front.png" height="200">
</p>

<br>

## Compatibility

<p align="center">
 <a href"https://www.apple.com/shop/accessories/all/homekit">
<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_apple_home.png" height="50">
 </a>
<a href="https://home.google.com"> 
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_google_home.png" height="50">
 </a>
<a href="https://www.home-assistant.io">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_home_assistanr.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_matter.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/works_with_zigbee.jpg" height="50">
 </a>
</p>


<br />
<br />

## Author

You can get in touch with me on my LinkedIn Profile:

#### Miguel Tomas

[![LinkedIn Link](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/migueltomas/)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/aeonSolutions)

<br>

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
The PCB Desgin Files i provide here for anyone to use are free. If you like this Smart Device or use it, please consider buying me a cup of coffee, a slice of pizza or a book to help me study, eat and think new PCB design files.

<p align+"left">
<a href="https://www.buymeacoffee.com/migueltomas">
   <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="35" />
 </a>
<br>
<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/Designs/bmc_qr.png" height="130">
</p>

<br />

### Make a donation on Paypal
Make a donation on paypal and get a TAX refund*.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/paypal_small.png)](http://paypal.me/mtpsilva)

<br>

### Support all these open hardware projects and become a patreon  
Liked any of my PCB KiCad Designs? Help and Support my open work to all by becomming a LDAD Patreon.
In return I will give a free PCB design in KiCad to all patreon supporters. To learn more go to patreon.com. Link below.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/patreon_small.png)](https://www.patreon.com/ldad)

<br />
<br />

______________________________________________________________________________________________________________________________
### License
Before proceeding to download any of AeonLabs software solutions for open-source development and/or PCB hardware electronics development make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. 

