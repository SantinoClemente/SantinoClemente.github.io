---
title: "Bike Phone Holder"
excerpt: "Top-Down Modeled, Adjustable Phone Holder for Bikes and Scooters"
header:
  teaser: assets/img/PhoneHolder_Teaser.jpg
gallery:
  - image_path: assets/img/PhoneHolder_Verticaljpg
  - image_path: assets/img/PhoneHolder_Horizontal.jpg

---

# About the Project

This project involves designing and 3D printing a bike phone holder using a top-down modeling approach. The holder is optimized for secure attachment to a 25mm-diameter handlebar, and allows phones to rotate between landscape and portrait orientations.

# Top-Down Modeling and Design

Top-down modeling is a CAD methodology that ensures  components are designed in context, improving integration and functionality. The handlebars and a CAD model of the phone were imported and grounded to define the design space. All holder components were modeled in place, and as-built joints were used for precise assembly.

### Key Features:
1. **Secure Handlebar Attachment**:
   - A single clamp with a slit fits handlebars of 25 mm diameter. The clamp is tightened with M2 bolts.

2. **Quick Phone Installation**:
   - A phone mount designed for an iPhone 13 tightly holds the phone without covering ports or buttons.
   - The phone can be attached and removed within seconds.
   - This part of the prototype is directly attached to the ball hinge via an M5 bolt.

3. **Adjustability**:
   - A rotational ball hinge allows 360° rotation between portrait and landscape orientations.
   - A tight nut is used to lock the ball, securing the phone mount in the desired location without requiring tools.

# Design and Iterative Process

1. **CAD Modeling**:
   - The clamp and phone holder were designed in Fusion 360, using a top-down approach and parametric modeling for easy adjustments.
   - Key variables like handlebar diameter, clamp length and phone tilt angle a were incorporated for a precise design.
   - The ball joint design was chosen due to the extra degrees of freedom it provides in adjustments.

2. **Printing and Testing**:
   - The first prototype was printed with PLA to check for fits  and tested on a 25mm tube.
   - Adjustments were made to improve hinge rotation and phone grip.
   - The final prototype consists of three separate materials: PLA (ball joint, chosen for dimensional accuracy and heat set insert capability), TPU (phone holder, chosen for flexibility), and high temp resin (clamp and tight nut, chosen for high stregth and feature size)


# Fusion 360 CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a454b25e577f9993e7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Picture Gallery
*Below are images of the final bike phone holder prototype.*

{% include gallery caption="Iterations of the bike phone holder, from design to final implementation." %}
