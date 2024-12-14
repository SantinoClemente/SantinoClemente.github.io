---
title: "Generative Design Truck Hanger and Motor Mount"
excerpt: "Lightweight and Integrated Truck Hanger for Electric Longboards"
header:
  teaser: assets/img/TruckHanger_Teaser.JPEG
gallery:
  - image_path: assets/img/TruckHanger_FrontView.JPEG
  - image_path: assets/img/TruckHanger_Render.jpg
  - image_path: assets/img/TruckHanger_Assembled.JPEG

---

# About the Project

(Don't grade me yet) This project focuses on designing a lightweight truck hanger, including a motor mount, for an electric longboard, using generative design and powder bed fusion printing.
# Design and Generative Process

Generative design was used to achieve a lightweight, structurally efficient geometry for the truck hanger, integrating the motor mount for a brushless DC motor.

### Key Design Features:
1. **Material Selection**:
   - Nylon 12: Lightweight and flexible.
   - ALSi10Mg: Strong and rigid, suitable for high-stress applications.

2. **Integrated Motor Mount**:
   - Slots for motor adjustment were made precise belt tensioning.
   - Fits a 6374 brushless motor and a 285 mm belt.

3. **Optimized Geometry**:
   - Clearance for 90 mm wheels, 608ZZ bearings, axle rod, kingpin and other obstacle geometries.
   - Structural support for torque transfer while minimizing mass.

4. **Parametric Design**:
   - Load cases based on rider weight, motor torque and weight, and other load scenarios.
   - Constraint placed on the kingpin through-hole to simulate real world forces.

### Embedded CAD Models
- **ALSi10Mg Outcome**:
  <iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a431c63c86a9627dda?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
- **Nylon 12 Outcome**:
  <iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a410c8fac79c32fb75?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

### Images and Renders
*Below are images of the rendered design and the physical ALSi10Mg model. The model was filament printed instead of SLS-printed.*

{% include gallery caption="Rendered and assembled generative design truck hanger" %}

# Discussion

## Powder Bed Fusion and Generative Design in Industry
Generative design and powder bed fusion have revolutionized industries like aerospace and automotive. A notable example is General Motors' use of generative design to consolidate eight parts into one for seat brackets, reducing weight and improving strength. This process generates complex geometries that are impossible to manufacture with traditional methods, reducing assembly steps and optimizing performance.

## Load Cases and Structural Constraints
Accurately defining load cases is essential to ensure the success of generative designs. For this project, multiple forces and constraints were considered:
- Forces Applied:
  - Rider weight (~80 kg) acting vertically on the truck axle.
  - Motor torque (~8 Nm) applied through the belt to the motor mount.
  - Shear forces due to acceleration and deceleration.
  - Impact forces during bumps or uneven surfaces.
  - Tension from the belt pulling on the motor mount.
- Constraints:
  - The kingpin through-hole was defined as a fixed point to simulate the base plate attachment.
  - Structural constraints were placed on the axle to simulate wheel loads and ensure smooth turning.
- Outcomes:
  - Generative design produced a lightweight solution while meeting all structural requirements. The optimized geometry supports the required forces while minimizing material use.

## Nylon vs. Aluminum Outcomes
This project explored designs for two materials with distinct properties:

1. Nylon 12:
   - Advantages:
     - Lightweight and easy to manufacture using SLS.
     - Cost-effective for rapid prototyping and testing.
   - Limitations:
     - Lower strength and stiffness make it unsuitable for high-stress applications like longboard trucks.
     - Poor thermal properties compared to metals, limiting its use in heat-generating assemblies.

2. ALSi10Mg:
   - Advantages:
     - High strength and stiffness, ideal for supporting rider loads and motor torque.
     - Superior thermal conductivity, making it suitable for high-performance applications.
     - Good fatigue resistance, ensuring long-term durability.
   - Limitations:
     - Higher cost and reliance on external manufacturers for metal SLS printing.
     - Heavier than Nylon 12, which may impact weight-sensitive designs.

## Critique of Generative Design
Generative design is a powerful tool for creating highly optimized parts, but it is not without limitations:
- Pros:
  - Material and cost savings. The ability to minimize material usage reduces waste and manufacturing costs in the long run.
  - Complex geometries. It enables designs that would be impossible to produce manually, such as internal lattice structures or multi-functional integrated components.
  - Performance improvement. Generative designs are often lighter, stronger, and more efficient than traditionally designed parts.
- Cons:
  - Computational intensity. Generative design requires significant processing power and time, making it less practical for small-scale projects.
  - Dependency on accurate input. The success of generative design relies heavily on the accuracy of applied loads, constraints, and manufacturing parameters.
  - Limited flexibility. Once a design is finalized, modifications can be challenging and time-consuming due to the complexity of the generated geometry.

## Applications
Generative design and powder bed fusion are particularly effective in industries requiring weight optimization, strength, and customizability:
- Aerospace: Lightweight brackets, structural frames, and turbine components.
- Automotive: Vehicle chassis, engine mounts, and battery enclosures.
- Medical: Custom prosthetics, implants, and surgical tools.
- Consumer Products: High-performance sports equipment and ergonomic designs.

By integrating generative design into more industries, manufacturers can achieve unprecedented levels of performance and efficiency, unlocking innovative solutions for complex engineering challenges.

---
