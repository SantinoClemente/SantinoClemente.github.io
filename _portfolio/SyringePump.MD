---
title: "Syringe Pump"
excerpt: "Syringe Pump for Volumetric Flow Control"
header:
  image: /assets/img/LF3DP-Banner-2.jpg
  teaser: /assets/img/Large-Format-3D-Printer-Thumbnail.png
gallery:
  - image_path: assets/img/Slide-3.png
  - image_path: assets/img/Slide-2.png
  - image_path: assets/img/Slide-4.png
   
---

# About

Many medical situations require a device to administer specific doses of fluids to a patient over long periods. While this would be inefficient or impractically expensive for human nurses to accomplish, syringe pumps, or infusion pumps, provide a reliable and inexpensive way to supply these doses to patients reliably in a controlled manner.

# Features


* **Massive Print Area: 1140 x 1200 x 1100 mm.** With a build envelop just shy of 4 feet in all dimensions, the LF3DP is capable of printing furniture and other large objects.
* **High Volumetric Output Extruder: 1 kg/hr - 450 C.** This printer come standard with a MDPH2 extruder by Massive Dimension, which can extrude at a rate of 1 kg/hr. Unlike typical filament extruders, the MDPH2 uses a screw to convey and liquify plastic pellets before the molten material is pushed out of a large nozzle (1 to 5 mm extrusion diameter). Please note: This printer can also be configured for other high flow rate extruders, such as the Typhoon and Pulsar by Dyze Design.
* **Affordable Pellet Feedstock** Pellets are the cheapest form of feedstock for any plastic-based manufacturing process. Save 50-75% of material costs by using pellets instead of spools of filament. Concentrated colorant can be added to the virgin material to achieve any color in the rainbow without requiring large amounts of storage. Recyled material can also be used for sustainable material printing.

# Off-the-shelf parts required

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

{% include gallery caption="Large Format 3D Printer Gallery" %}

