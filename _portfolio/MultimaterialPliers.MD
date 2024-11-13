---
title: "Multi-Material Pliers"
excerpt: "Multi-Material 3D Printed Pliers for Precision Gripping"
header:
  teaser: assets/img/Teaser_Pliers.JPEG
gallery:
  - image_path: assets/img/Pliers1.JPEG
  - image_path: assets/img/Pliers2.JPEG
  - image_path: assets/img/FinalPliers.JPEG

---

# About the Project

This project focuses on designing multi-material pliers capable of gripping and manipulating delicate components, such as through-hole resistors. These pliers integrate a flexible spring component made from TPU to facilitate mobility, allowing continuous use.


# Print-in-Place and Multi-Material Printing

Print-in-place models enable functional, multi-component designs that work immediately after being removed from the print bed, requiring no post-processing or assembly. This is a powerful advancement in 3D printing, allowing for pre-assembled parts that can be printed as a single unit, which simplifies the assembly process and minimizes the risk of component misalignment. Common applications of print-in-place include gears, hinges, and tools where intricate motion is essential, like working wrenches or scissors. Due to lack of printer availability, this assembly was made by modeling and printing three separate components, to be printed from different materials and quickly assembled.

### Materials Used
For functional multi-material models, using a combination of rigid and flexible materials works well. In this design, we employed PLA for the plier jaws and handles, and 95A TPU for the spring element, balancing flexibility and durability.

# Design and Iterative Process

1. **Initial Concept and CAD Modeling**: 
   - The entire CAD assembly was created using Fusion 360. The first component designed was the spring center, to be printed out of flexible TPU. This component features a 30mm x 30mm center square hole, which allows for lateral compression which translates into rotation of the tips. It also contains four "C" shaped extrusions (one on each side of the square) which will allow it to fit tight with the other components. The handles and tips, to be printed out of rigid PLA, were designed around the center spring, aiming to optimize handleability. The first iteration was extruded to be 5mm tall, with a 0.2mm clearance between the center spring and each component around it.

2. **Testing and Refinements**: 
   - Once the first plier prototype was printed and assembled, it was tested to check its' performance. The pliers were able to pick up and hold through-hole resistors, but the fit between the components was loose so the pliers fell apart after a couple uses. For a second iteration, two modifications were made to the design to achieve a tighter and stronger fit: the plier height was increased to 10mm, and the clearance was decreased to 0mm. These modifications were easy to perform due to these two variables being added as parameters in the original design. This iteration was printed, assembled and tested, achieving much better results.

# Relevant Specifications

- **Jaw Length**: 12.4mm
- **Plier Height**: 10mm
- **Jaw Capacity**: 10mm

# Print Settings

| Setting         | Value      |
| --------------- | ---------- |
| Infill Density  | 20% (handles and tips), 10% (spring |
| Nozzle Diameter  | 0.6mm |
| Material        | PLA (handles and tips), 95A TPU (spring) |

# Fusion 360 CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a44bb592effdf42de0?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Picture Gallery
*Below are images documenting the iterative process and final design.*

{% include gallery caption="Iterations of the multi-material pliers, demonstrating design refinements and final functionality" %}

# Demonstration
![Working Pliers](/assets/img/WorkingPliers.gif)

