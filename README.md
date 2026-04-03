# VeloXY
A CoreXY 3d printer with a heated chamber and bed. It has 300x300x320 print volume and 3 point bed-levelling. I made this project to be able to print higher quality materials.
<img width="735" height="647" alt="image" src="https://github.com/user-attachments/assets/385adadf-e649-4300-a40a-f17bd95f0326" />

## **Assembly**
The assembly is centered around a frame made of galvanised square steel (40x40). The frame is essentially a cube, where the square steel is welded together, so no connectors are needed. Two cross bars at the top are lowered by ~60mm to provide clearance for the extruder and filament path. 
<img width="664" height="552" alt="image" src="https://github.com/user-attachments/assets/a28636d7-5706-4919-b470-e64de117bcff" />
Components are mounted onto the square steel using rivet nuts. 

### Z axis

The Z axis uses 3 independent motors to enable 3 point bed-levelling. At each motor, there is a T8 leadscrew to drive motion, and an 8mm smooth rod for support. The smooth rod is press fit into the 3d printed brackets through small slits in the brackets for compliance. The nema 17 motor mounts to the bracket, and secures the leadscrew with a 5x8 shaft coupler. At the idler, the leadscrew is held in place with a 16x8x5 bearing, allowing rotation. 
<img width="497" height="656" alt="image" src="https://github.com/user-attachments/assets/cb3de026-7f92-486f-8ac8-630fae88cff9" />
<img width="338" height="663" alt="image" src="https://github.com/user-attachments/assets/dbfb0f09-ef67-4bd4-9f1d-04c91f2ed438" />
<img width="404" height="480" alt="image" src="https://github.com/user-attachments/assets/e56827a9-7d5b-4bab-b928-b0bb11b5bdb0" />
<img width="673" height="571" alt="image" src="https://github.com/user-attachments/assets/54c94a77-ca22-4c96-9eb9-6f4d289b769e" />

The intersection of the corner Nema 17 motors with the square steel is not an error, as a section of the square steel will be cutout (a rectangle just bigger than the motor) so that the motor sits in there without touching any of the steel.

Bed supports hold an LM8UU bearing and a anti-backlash nut. This transfers motion to the bed. The bed sits on these supports through a threaded steel ball (Vcore system) which rests on metal dowels in the bracket.
<img width="1010" height="522" alt="image" src="https://github.com/user-attachments/assets/a9f7664e-df64-4d4e-a4eb-051bda2caf60" />
<img width="468" height="398" alt="image" src="https://github.com/user-attachments/assets/28b0d046-74de-4921-af33-bfb9e364f0b7" />
<img width="714" height="520" alt="image" src="https://github.com/user-attachments/assets/7dab5e24-1807-44ad-9f7c-22d6642edfc0" />
<img width="975" height="676" alt="image" src="https://github.com/user-attachments/assets/e1b7ce9b-7495-419b-b667-54d585e8bf11" />
<img width="905" height="333" alt="image" src="https://github.com/user-attachments/assets/c21dea53-6fb2-486f-a384-096008269bee" />

### Gantry (X and Y)
The gantry is the 2020 T slot profile that moves back and forth along the Y axis. The gantry is supported by two 3d printed brackets, one at each end, that connect it to the MGN12H carriages. The Y linear rails are mounted on the underside of the frame.
<img width="1028" height="615" alt="image" src="https://github.com/user-attachments/assets/fe3b677c-50ca-4df9-ab3f-1f66d33fd302" />
<img width="371" height="384" alt="image" src="https://github.com/user-attachments/assets/f99bcd45-c866-45e1-b099-ccee0bf033e0" />

 The gantry has a linear rail along the top face of the profile, this is the X axis.
 <img width="1164" height="474" alt="image" src="https://github.com/user-attachments/assets/e5e30fd2-82ff-4255-afaf-f1e6320dd34e" />
 <img width="913" height="324" alt="image" src="https://github.com/user-attachments/assets/13d656db-4ace-49af-ab15-9e9940f202d2" />

The extruder runs along this linear rail for the X axis. The extruder is sat on a MGN12H carriage, and holds a nema 17 motor for the extruder and the hotend. Two blower fans cool the nozzle/part.
<img width="423" height="452" alt="image" src="https://github.com/user-attachments/assets/86877108-49be-443d-9860-0815944aab25" />
<img width="425" height="379" alt="image" src="https://github.com/user-attachments/assets/1f88c3ce-30a9-426f-8af4-ca47d1775ed6" />
<img width="873" height="583" alt="image" src="https://github.com/user-attachments/assets/3c258d18-e89e-4391-80dc-781bb42e9ec3" />

### Chamber
The chamber is mounted around the frame, aiming to create a closed off area that can be heated for better printing. The enclosure is made up of ACM, mounted on the top, back, bottom and sides using rivet nuts.
<img width="449" height="451" alt="image" src="https://github.com/user-attachments/assets/2e104ea1-369d-4e37-9983-1b4e4c342cef" />
A hole is drilled in the back panel so that wires for electronics can enter the chamber.
<img width="545" height="546" alt="image" src="https://github.com/user-attachments/assets/3a3fd509-e0a5-47f9-8f1b-63f1690a5b00" />

The enclosure is finished with a polycarbonate door on a hinge mounted to the frame, with a 3d printed handle.
<img width="537" height="561" alt="image" src="https://github.com/user-attachments/assets/ae34793b-0460-4739-a36b-52a75d68111a" />

The chamber is heated by a PTC heater in the bottom corner, mounted to a base tube of square steel, and a vertical post using a small metal rectangle with mounting holes drilled.
<img width="588" height="534" alt="image" src="https://github.com/user-attachments/assets/dd2fc66f-a6ef-40b4-9ff3-9a926d60edff" />
<img width="578" height="569" alt="image" src="https://github.com/user-attachments/assets/e99c0f7a-fe44-4826-8e77-1b77f1edfb91" />

### Motion
The printer is based on a coreXY motion system. The belts are stacked on top of each other, so there is no need for a crossover system.
<img width="474" height="521" alt="image" src="https://github.com/user-attachments/assets/d75f6584-459f-4abf-8a38-382a9f9186c0" />
There are pulleys on the idlers and belt post on the gantry. The belts connect to a post/screw on the extruder.
<img width="523" height="479" alt="image" src="https://github.com/user-attachments/assets/ab2ad822-17bd-45c8-aee9-7d646b55998b" />



## **Electronics**
I designed a PCB motherboard around the mega2560 that will control the printer. The motherboard is 2 layers and uses A4988 footprint drivers. Power for the motors and heaters enters the board with a screw terminal from the 24v 600w PSU. There is also an 5v screw terminal input which powers the motor driver logic, lcd and if needed the arduino. The 5v comes from the psu but with a buck converter between. There is a third power input for the arduino vin pin which can be used if needed, but the arduino can also be powered by the 5v supply and usb. The LCD connects to a 4 pin header, with RX, TX, 5V and GND. All three heaters (Hotend, bed and chamber) are controlled through TO-220 mosfets, but the chamber has its own PSU. There are also fuses for the power inputs.
<img width="788" height="591" alt="image" src="https://github.com/user-attachments/assets/f4315b25-3a0e-49f0-9ef4-c23d9584b01f" />
<img width="1238" height="875" alt="image" src="https://github.com/user-attachments/assets/a5982b7a-af14-43aa-93e1-4948464d47d2" />

## **BOM**

**Components**


**Printed parts**
| Part | Quantity | Picture |
|------|----------|---------|
| A bottom corner | 1 |<img width="766" height="750" alt="image" src="https://github.com/user-attachments/assets/4daf3f85-3890-480b-b72c-51cbe87b5e7c" />
 | A bed support | 1 | <img width="740" height="776" alt="image" src="https://github.com/user-attachments/assets/ffe08260-ad90-4f92-9e3f-ec08b9152e0c" />
| A idler | 1 |<img width="485" height="390" alt="image" src="https://github.com/user-attachments/assets/9cd2553c-3501-47f3-af36-4f164e5c51fc" />
| A motor | 1 | 
| A gantry belt post | 1 |<img width="831" height="618" alt="image" src="https://github.com/user-attachments/assets/77093554-7aaa-453d-907c-185ac4fe5801" />
| A gantry mount | 1 | 
| B bottom corner | 1 | 
| B bed support | 1 |<img width="696" height="433" alt="image" src="https://github.com/user-attachments/assets/fa579b06-e6f8-4bd5-b5a9-50daae67202a" />
| B idler | 1 | 
| B motor | 1 | 
| B gantry belt post | 1 | 
| B gantry mount | 1 | 
| Z front bracket | 1 |<img width="438" height="375" alt="image" src="https://github.com/user-attachments/assets/7b3adafe-e1e2-44d3-bb61-4893fba1059b" />
| Front bed support | 1 | <img width="875" height="566" alt="image" src="https://github.com/user-attachments/assets/e32b74ad-b8dd-4418-947b-23fe84f2afb2" />
| Front top support | 1 | 
| Handle | 1 | 
| Extruder | 1 | <img width="840" height="742" alt="image" src="https://github.com/user-attachments/assets/8319fd63-f792-4cea-b59b-8958e5c29b7f" />
| Electronics case | 1 | <img width="991" height="675" alt="image" src="https://github.com/user-attachments/assets/1295f7fd-9a0f-44dc-9b77-717166f3ab0a" />
 
