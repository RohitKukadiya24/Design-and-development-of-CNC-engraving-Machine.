# Design-and-development-of-CNC-engraving-Machine.
ABSTRACT:

The CNC machine is abbreviated as Computer Numerical Control. The CNC machine is a
system that is able to accept numerical control inputs to machine a part specified by the
exact positioning of the inputs. It is referred to computer that changes the design in the
form of numbers and the computer functions to shape and cut the material. The CNC
machine includes three steps input, process and output. The production requires three
parts of the equipment. They are computer, an interface and computer numerical control.
This project would include building a machine which would perform functions like drilling,
boring, facing, engraving etc. It will be an automatic machine which would perform all the
above functions by automatically working according to the command given to the circuit.
These machines can be used to produce machine tools as well as control mechanism. This
machine includes some important parts such as stepper motor, a table, parallel port
breakout board, linear guide, spindle motor, etc. The software used to run this machine is 
EMC2 and MACH3. As name suggests the machine would be performing almost all
important functions so it would be an excellent substitute for various machines in one, it
would be the only machine which would do work of lathe, drilling, boring, etc. in one
machine. Thus it is very cost effective. This saves much of floor space compared to other
machines. The automatic system saves human effort and is easy to maintain. By using CNC
there is remarkable increase in the quality of products as well as it offers higher flexibility.
It increases the productivity and reduces the lead time. The production is economical in
nature and decreases the amount of scrap particularly for industries involved in mass
production.


INTRODUCTION:

The purpose of this project is to have a greater flexibility in operations. A CNC
machine is capable of doing operation with good efficiency. Computer Numerical
Control (CNC) is one in which the functions and motions of a machine tool are
controlled by means of a prepared program containing coded alphanumeric data.
CNC can control the motions of the work piece or tool, the input parameters such
as feed, depth of cut, speed, and the functions such as turning spindle on/off,
turning coolant on/off. This is a 4-axis machine.

![image](https://user-images.githubusercontent.com/95118920/143779719-615c3777-83a8-4493-b6ea-585c90b3ded2.png)
![image](https://user-images.githubusercontent.com/95118920/143779740-bbdf2fd2-6e44-4bd7-a697-116be304c016.png)
![image](https://user-images.githubusercontent.com/95118920/143779742-5c6744ac-a8cc-47ae-be21-f936e30c5264.png)
![image](https://user-images.githubusercontent.com/95118920/143779748-3d465510-fe67-4e0f-91af-5ac138ccca59.png)



PROBLEM
1. For mass production of intricate parts manual working becomes tedious. So optimization
of work should be needed. Thus automatic working is preferred over the manual work.
2. For making dyes or masterpieces a high level of acuity is required and as human work is
followed by some inaccuracies thus an automatic CNC machine is required.
3. In goldsmith works generally a goldsmith will consume more time in making a jewellery
and production rate will be low. A CNC machine would increase production rate by
increasing speed of production and accuracy is also high.
4. For manufacturing thousands of identical parts man working would not be able to
produce it, there would be some difference in each part. Thus automatic machine is
programmed in such a way that each part produced will be identical to each other.
5. Instead of using many men on different machine we could use single man on different
CNC machines which decreases labor requirement and reduces different machine
requirements for producing single part .

CNC MULTIMACHINE TRADITIONALLY CAN PERFORM FOLLOWING FUNCTIONS
1. Engraving purposes
2. Drilling purpose
3. Milling purpose
4. Side facing
5. Boring purpose


USES:-
1. This type of machine is used for engraving purposes to carve out masterpieces
automatically without intervention of human.
2. Used for making wood patterns for casting or other purposes.
3. Used for jewelry making and other gold smithy purposes.
4. The machine would be performing almost all important functions so it would be
an excellent substitute for various machines in one, it would be the only machine
which would do work of lathe, drilling, boring, etc. in one machine.
5. Used for dye making.
6. Used in industries for removing metal,
7. Used in automated industries for industries having mixed layout.

Advantages
1. Reduction in lead time.
2. More accuracy obtained in production.
3. Precision in work pieces.
4. Requires fewer workforces.
5. Reduction In floor space.
6. Reduction in cost.
7. Mass production.
8. Used for mixed type of plant layouts.
9. As 4 axes is used rounded parts can be operated which a conventional machine
cannot do.
10. Products with complex geometry can be produced.


COMPONENTS USED IN MACHINE
There are basically two types of components used in this machine that is electrical and
mechanical components

MECHANICAL COMPONENT
1. Ball screw of carbon steel
2. Guide way
3. SMA bearing
4. LMK bearing
5. Shaft end supporters
6. Coupling
7. SSV nut (square nut)
8. FSI nut (round nut)
9. Stepper motor bracket
10. Bed
11. Tool holder
12. Bright metal sheet
13. Carbon steel shaft
14. Aluminum plate
15. Bearing of ID 20 mm and OD 30 mm
16. L-N key bolt


ELECTRICAL COMPONENTS
1. Stepper motor
2. Controller board (breakout board)
3. Stepper motor driver
4. Limit switch


WORK ENVELOPE:- 600X450X300 mm

BRIEF PROBLEM SOLUTION OF PRESENT TECHNOLOGY:
In conventional CNC machine, the gantry mounting is lower mount which increases motion path . The tool motion is to be given to upper mount for increasing stability so in this project we will use upper mount of gantry so that the motion which is to be transferred to upper side will remain in upper side only.
In present type of CNC machine rigidity provided is little less due to use of less stable structure in manufacturing. While in this project we will use more stable structure by using C channel and upper mount gantry.
Mostly it is observed in conventional CNC machine that stability obtained is little less due to some unwanted tool motions or due to flexible structure of machine. Here in this project stability obtained is great due to balancing and eliminating unnecessary tool motion and necessary arrangement modification of parts in the machine.
A CNC machine available in market occupies more floor space while in this project we make our machine more compact and additional advantage of performing most of the functions in one machine.
In this project dual stepper motor is used which gives advantage of stability in Y axis while conventional machine is used only one stepper motor in one axis. The advantage of 4 axis over 3 axis is that in 4 axis we get benefit of operating round or circular parts while in 3 axis only flat surfaces are operated.
The controlling of this machine is done by USB which gives more advantages over conventional ones.


DESIGN: ANALYSIS, DESIGN METHODOLOGY AND IMPLEMENTATION STRATEGY

DESIGN OF MECHANICAL STRUCTURE
Decide to make 4-axis CNC multi machine. Decide work envelope of machine and further start design through solidworks 3D modeling software.

DESIGNING CIRCUITS AND ITS ASSEMBLY
The circuits like wires, motors and transformers are mounted and connected together and connected to PC via software which work according to the information given to the computer.

MANUFACTURING OF PARTS AND ITS FINAL ASSEMBLY
Some parts like frame body, plates and fixtures were ordered from various local vendors and then welded, drilled and processed to join together to form a firm and rigid structure. The frame structure was welded in shop by us this structure is very rigid and stable because we used C structure which is very stable when analyzed by the inertia forces and moments calculation. After forming frame of the machine the parts like plates, bearings, motors, linear guide ways, shafts and circuits were ordered then positioned together and assembled in proper way to form a complete automatic CNC multimachine which could perform all the functions in one floor.

PRODUCT DEVELOPMENT CANVAS

Electronics and Software:
The PBX-USB is a USB interfaced CNC controller that was developed specifically to work
with the CNC USB Motion Controller Software from www.planet-cnc.com. This Interface
sports 4x 10 pin PBX-Header Connections for interfacing to our existing stepper motor
drivers. It has an additional header for direct connection to our RBX-1 3 channel relay
board.
This software/hardware combination can be further expanded with jog key inputs and an
I2C bus for nearly unlimited additional I/O. This will allow the development of jog
pendants, digital readouts, and input/output cards for a variety of purposes.
The software runs on Windows and replaces Mach3 or EMC2. It can even be run through a
virtual machine on a Mac or Linux host.

Probo StepVX Uni-polar Microstepping Chopper Driver:
The ProboStep is a complete microstepping motor driver and control system with a builtin
translator. It is designed to operate uni-polar stepper motors in full-, half-, quarter-,
eighth-, and sixteenth-step modes with output drive capability of 44V and 3.0 A. This
driver utilizes the Sanken SLA7078MPR chip which includes built-in sense current
detection and load circuit short or open protection provide lower loss and lower thermal
resistance.

