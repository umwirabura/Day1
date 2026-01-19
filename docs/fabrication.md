# Fabrication Logic

## Overview

Documentation of fabrication methods, machine constraints, and material considerations.

## Fabrication Methods Used

### Additive Manufacturing (3D Printing)

**Machine:** [Specify model]  
**Materials:** PLA, ABS, PETG, etc.  
**Layer Height:** 0.2mm  
**Infill:** 20%

**Considerations:**
- Print orientation for strength
- Support structure requirements
- Post-processing needs

### Subtractive Manufacturing

**Machines Used:**
- Laser cutter
- CNC mill
- [Other tools]

**Materials:**
- Acrylic
- Wood
- [Others]

### Formative Processes

[If applicable - molding, bending, etc.]

## Material Selection

| Material | Properties | Use Case | Constraints |
|----------|-----------|----------|-------------|
| PLA | Biodegradable, rigid | Prototypes | Low heat resistance |
| Acrylic | Transparent, machinable | Enclosures | Brittle |
| Wood | Natural, workable | Structural | Grain direction matters |

## Tolerances & Constraints

**Key Learnings:**

!!! tip "Tolerance Planning"
    - Add 0.2mm clearance for snap-fit parts
    - Account for material shrinkage in 3D prints
    - Test fit before final fabrication

**Machine Limitations:**
- Laser cutter: Max thickness 6mm
- 3D printer: Build volume 200x200x200mm
- CNC: Minimum feature size 1mm

## Design for Fabrication

### Examples

**Before DFM:**  
![Complex geometry](assets/before-dfm.png)  
*Issues: Overhangs, unsupported features*

**After DFM:**  
![Optimized design](assets/after-dfm.png)  
*Improvements: Self-supporting, printable orientation*

## Safety & Best Practices

- Always use protective equipment
- Understand machine operation before use
- Material safety data sheets (MSDS) review
- Proper ventilation for laser cutting

## Sustainability Considerations

- Material waste minimization strategies
- Recyclable material selection
- Energy-efficient process choices
- Design for disassembly and repair
