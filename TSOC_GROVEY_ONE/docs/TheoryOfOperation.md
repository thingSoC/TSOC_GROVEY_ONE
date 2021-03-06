# TSOC_GROVEY_ONE Theory of Operation

**TSOC_GROVEY_ONE** is a ATMEGA328 based board, an Embedded Module for thingSoC compatible with the Arduino IDE.

The **TSOC_GROVEY_ONE** allows you to connect [thingSoC](http://thingsoc.github.io/), [Mikrobus](http://www.mikroe.com/mikrobus/), 
and/or [Grove System](http://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/) 
Modules all at the same time, using the Arduino Development environment, with the the ATMEGA328P processor.
This gives you maximum flexiblity for sensor and actuator, selection and reuse. 

[![thingSoC GROVEY_ONE](https://github.com/thingSoC/TSOC_GROVEY_ONE/blob/master/TSOC_GROVEY_ONE/images/TSOC_GROVEY_ONE_top.png?raw=true)TSOC_GROVEY_ONE](https://github.com/thingSoC/TSOC_GROVEY_ONE/)

The thingSoC "Grovey Series" was designed as "Everyday Electronics", a no-frills, low cost, approach to modular embedded product design.
thingSoC boards are similar in size to most break-out-boards (BOBs), but feature a standardized stacking pinout, as well as an I2C metadata store (EEPROM)
to indicate what peripherals are installed.

* [Supported by the Arduino IDE](https://www.arduino.cc/) 
* [thingSoC Compliant Module](http://www.thingsoc.com)
* [Mikrobus Compatible Module](http://www.mikroe.com/mikrobus/) 

---------------------------------------

## Theory of Operation <a name="theory_index"/>

The **TSOC_GROVEY_ONE** supports a single "thingSoC" socket with 3.3 Volt Level signaling.

### Page A : ThingSoC Interface <a name="PAGEA"/>


![Schematic Page A](https://raw.githubusercontent.com/PatternAgents/TSOC_GROVEY_ONE/master/TSOC_GROVEY_ONE/docs/images/sch_page_1.png "Schematic Page A")

Limitations: 

   
   
### Page B : I2C Hub Controller <a name="PAGEB"/>


![Schematic Page B](https://raw.githubusercontent.com/PatternAgents/TSOC_GROVEY_ONE/master/TSOC_GROVEY_ONE/docs/images/sch_page_2.png "Schematic Page B")

### Page C <a name="PAGEC"/>

![Schematic Page C](https://raw.githubusercontent.com/PatternAgents/TSOC_GROVEY_ONE/master/TSOC_GROVEY_ONE/docs/images/sch_page_3.png "Schematic Page C")

### Page D <a name="PAGED"/>

![Schematic Page D](https://raw.githubusercontent.com/PatternAgents/TSOC_GROVEY_ONE/master/TSOC_GROVEY_ONE/docs/images/sch_page_4.png "Schematic Page D")

---------------------------------------

## Documentation Index <a name="documentation_index"/>

[[TSOC_GROVEY_ONE Quick Start Guide](https://github.com/thingSoC/TSOC_GROVEY_ONE/blob/master/TSOC_GROVEY_ONE/docs/QuickStart.md)

[TSOC_GROVEY_ONE User Guide](https://github.com/thingSoC/TSOC_GROVEY_ONE/blob/master/TSOC_GROVEY_ONE/docs/UserGuide.md)

[TSOC_GROVEY_ONE Theory of Operation](https://github.com/thingSoC/TSOC_GROVEY_ONE/blob/master/TSOC_GROVEY_ONE/docs/TheoryOfOperation.md)

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)
[ESP8266 Community](https://github.com/esp8266/Arduino)

---------------------------------------

[![Image](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true)  
*thingSoC*](http://thingsoc.github.io) 
 
