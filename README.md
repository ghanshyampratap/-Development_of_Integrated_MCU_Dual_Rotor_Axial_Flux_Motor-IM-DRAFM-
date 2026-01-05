#  Development of Integrated MCU Dual Rotor Axial Flux Motor (IM-DRAFM)

---

##  Introduction
This project focuses on designing and developing an **Integrated MCU Dual Rotor Axial Flux Motor (IM-DRAFM)**.  
Axial flux motors are gaining popularity in **Electric Vehicles (EVs)**, **Aerospace**, **Robotics**, and **Renewable Energy Systems** due to their:
- High torque & power density
- Compact size
- Advanced thermal management
- Better efficiency


##  Problem Statement & Objectives

###  Problems:
- Existing motors face poor torque-to-weight ratio.
- Space utilization issues in EV drivetrains.
- Costly & environmentally harmful materials.

###  Objectives:
- Achieve high efficiency, torque & power density.
- Reduce & optimize form factor and flux topology.
- Integrate control systems into a single unit.
- Make the design scalable & affordable.


##  Proposed Solution
- Use **Axial Flux Motor Technology** with **dual rotors**.
- Flux lines run parallel to the shaft for shorter magnetic path → higher torque.
- Modular design allows various stator-rotor combinations.
- Integrated MCU for advanced control and sensorless operation.
  
![image](https://github.com/user-attachments/assets/5f0ee27e-faa8-45cd-818e-755062ca1b5a)![image](https://github.com/user-attachments/assets/9892c8b3-d40e-4777-a07e-5b869c9b7514)


![image](https://github.com/user-attachments/assets/050348b3-cc2b-4633-a588-598b3f24101f)

![Screenshot 2025-07-09 113440](https://github.com/user-attachments/assets/3de2c714-05ac-4a8e-bdc8-adfdc46b47ca)


![Screenshot 2025-07-09 113126](https://github.com/user-attachments/assets/24972d46-bbf2-41ed-8a5a-d23167f939c5)



---

##  Project Specifications

###  **Stator & Winding**
- **Material:** PETG (3D-printed)
- **Wire:** 29 AWG, 10 strands parallel
- **Slots:** 12 slots, star (Y) connection
- **Turns:** 8 turns per slot per phase
- **Winding Factor:** 0.966

###  **Rotor & Magnets**
- **Configuration:** Dual rotor, 100 mm diameter
- **Magnets:** Neodymium N35, 25×10×5 mm, 10 poles per rotor

###  **Mechanical Details**
- **Axial Gap:** 2.25 mm
- **Weight:** ~2.5 kg
- **Shaft:** Steel/Aluminum

###  **Magnetic Circuit & Performance**
- Flux loop travels axially between two rotors.
- Estimated air gap flux density: 0.7 – 0.9 T.
- Estimated torque: ~0.03 Nm @12A.
- Power: ~500 W peak, ~350 W continuous.
- Efficiency: ~85–90%.


---

##  Hardware & Software Tools

**Hardware:**  
- Enameled copper wire, NdFeB magnets, 3D-printed parts, MOSFETs, PCB, ESP-32, connectors.

**Software:**  
- Autodesk Fusion (3D Design)  
- Ansys Workbench (Simulation)  
- ESP-IDF (MCU Programming)


##  Advantages

-  Higher torque & power density.
-  Improved thermal management.
-  Compact & lightweight design.
-  Smooth operation with reduced vibrations.
-  Modular & flexible design.


##  Applications

- Electric Vehicles (EVs)
- Aerospace propulsion
- Robotics & high-performance industrial machinery
- Wind turbines & other renewable energy systems

---

##  Expected Outcome

- Higher torque density in compact size.
- Improved efficiency & lower losses.
- Better thermal management.
- FOC & CAN-enabled controller for optimal performance.

https://github.com/user-attachments/assets/50808f6f-b5eb-465f-b91e-68d358a1b7e4






##  Work Progress

-  Dual rotor design and PETG stator fabricated.
-  Sensorless control with integrated MCU implemented.
-  Proprietary self-starting tested.

###  Upcoming Tasks
- Develop FOC & CAN-enabled motor controller.
- Add advanced soft-start & operational modes.
- Optimize torque & speed control (Clarke-Park transform).

---
