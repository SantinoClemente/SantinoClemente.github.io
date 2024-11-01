---
title: "Microfluidic Homogenous Mixer"
excerpt: "Syringe Pump for Volumetric Flow Control"
header:
  teaser: assets/img/SyringePump.jpg
gallery:
  - image_path: assets/img/SyringePump_FrontView.jpg
  - image_path: assets/img/SyringePump_SideView.jpg
  - image_path: assets/img/SyringePump_TopView.jpg

---

# About

Many medical situations require a device to administer specific doses of fluids to a patient over long periods. While this would be inefficient or impractically expensive for human nurses to accomplish, syringe pumps, or infusion pumps, provide a reliable and inexpensive way to supply these doses to patients reliably in a controlled manner.

# Features

* Precision Fluid Delivery: The syringe pump allows for controlled and reliable dispensing of fluids, essential for various medical scenarios, with adjustable flow rates via a potentiometer and Arduino-controlled stepper motor.

* Multiple Syringe Compatibility: Designed to accommodate syringes of different diameters (10 mL and 20 mL), with staggered slits in the end support to ensure accurate stopping points for each syringe size.

* User-Friendly Interface: Features an LCD display for real-time monitoring of flow rate and time remaining, along with LED indicators for different operating states, enhancing usability and operational clarity.

* Safety Mechanisms: Includes a limit switch to automatically stop the motor when the syringe is empty, preventing overextension and ensuring safe operation.

* Robust Design and Construction: The syringe pump is enclosed to protect electronic components from liquids and user interaction, ensuring durability and safety in medical environments.

# Off-the-shelf required parts

| Off-the-Shelf Required Parts                                        | Quantity |
| ------------------------------------------------------------------- |:--------:|
| 250 mm lead screw with 2 mm pitch and 2 mm lead                     |    1     |
| 1/4” x 8mm Flexible Coupling                                         |    1     |
| 200 mm linear rod with 8 mm diameter                                 |    2     |
| LM8UU Linear bearing for 8 mm diameter rod                          |    2     |
| 2040 Aluminum Extrusion 1’ Length                                    |    1     |
| Nema 17 Stepper Motor                                                |    1     |
| MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp |    1     |
| Arduino Uno                                                          |    1     |
| A4988 Stepper Driver                                                 |    1     |
| Small Breadboard                                                     |    1     |
| Panel Mount Latching Push Buttons                                    |    1     |
| Panel Mount Momentary Push Buttons                                   |    3     |
| LCD Display                                                          |    1     |
| Limit Switch                                                         |    1     |
| RGB Common Cathode LED                                               |    1     |
| Potentiometer                                                        |    1     |

# 3D printed parts required

| 3D Printed Required Parts | Quantity |
| ------------------------- |:--------:|
| Carriage                  |    1     |
| Enclosure Top & Bottom    |    1     |
| End Support               |    2     |
| Motor Mounting Plate      |    1     |


# Arduino Code

The Arduino code can be found [here](https://github.com/SantinoClemente/SantinoClemente.github.io/blob/main/assets/img/SyringePump_code).

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a43a7ed807993c6119?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# How to Operate
* Ensure that the pump is paused by pressing the leftmost button, the LED turns yellow when the pump is paused.
* Place the syringe with the desired amount of liquid to pump on the end support.
* Using the switches on the right of the display, adjust the carriage so that it touches the end of the syringe plunger.
* Use the potentiometer to adjust as desired the flow rate as seen on the display. 
* Press the leftmost button again to start the pump, the LED should turn green.
* As the pump runs, the display will show the current flow rate and time remaining.
* When the plunger reaches its limit, the carriage actuates a limit switch to stop the motor. The LED turns red to indicate that the run has ended.

{% include gallery caption="Syringe Pump for Volumetric Flow Control" %}
