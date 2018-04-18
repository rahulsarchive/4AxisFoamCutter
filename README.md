# 4AxisFoamCutter
A DIY open source 4 Axis Foam cutter using Ramps 1.4 + Arduino for cutting RC Wing Cores.

We wanted to build an UAV out of foam, since there will be many iterations of designs to get through before reaching our goal. We decided to make a device to help us get through the iterations an bit faster, A hot wire cutter is the most efficient and clean way to cut foam. A CNC hot wire cutter is even better! It is an awesome tool to have when you are building airplanes out of foam. A properlly configured machine can save you a lot of time and produce a buttery smooth cut.

Mechanically, its not complicated to make a CNC Hot wire cutter. All you need is 4 independed linear axes, two horizontal axes and two vertical axes stacked on top of it. This can be acheived by any means such as linear bearings, smooth rods and also drawer slides. The axes are driven by stepper motors. There are minimal cutting forces involved, the machine only needs to be rigid enough to witstand the tension of the wire streched between the towers.

The problem is how to control 4 independent axes at the same time. Most tutorials online are for 3-axis 3D printers. Then there are documentation on people using expensive software and difficult to find hardware for making their 4-axis foam cutter.There does not seem to be enough documentation on building a 4-axis machine using easily available parts such as parts from a 3D printer kit and open source sotware. We found some people who had done similar projects and decided to make a CNC hot wire cutter ourselves and try it out.

Hot wire CNC

## Hardware

1. Plywood (12mm)
2. Rails (Steel tubes, Smooth rods)
3. Stepper Motors (one for each axis)
4. Lead screw (M8 x 600mm, as long as you need the axis to be)
5. Ramps 1.4
6. A4988 Stepper driver (one for each axis)
7. Arduino Mega 2560
8. Nichrome wire (30 guage for smaller builds and 26 guage for larger ones)
