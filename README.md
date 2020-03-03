# actor-lab
 A parallel, object-orientated, iconic control language designed to introduce the ideas of control technology and robotics.

Original Website:  http://actor-lab.open.ac.uk/

### Disclaimer

Actor-lab is made freely available for any non-commercial use. The software and
documentation are the copyright of the Open University, but may be copied and 
distributed freely provided that no change is made to them.

No fitness for any purpose is claimed for actor-lab and no responsibility is 
accepted for its use.

No guarantee of any support, explanation or guidance as to the use of actor-lab 
is given.

LEGO and RCX are trademarks/copyright the Lego Company, RoboLab is the 
trademark/copyright of Tufts University.

No connection of any kind with either the Lego Company or Tufts University is 
implied or claimed for actor-lab or its authors.


## Quick Start, July '04
- see the project manuals at actor-lab.open.ac.uk for examples of syntax use
- actor-lab works on Mac (OS 9 & OS X) and on PC  (Windows 98/2000 & XP)
- actor-lab requires a serial RCX tower connection (it can be via a USB-serial converter)
- the RCX brick must first have the RoboLab firmware downloaded to it
- actor-lab requires constant communication with the brick (ie vertical RCX for a buggy)
- actor-lab will work in screen mode when not communicating with a RCX brick 
- 4 green lights showing indicates you are connected to a brick
- actor-lab application has to be in a folder with projects, sounds etc
- double-click actor-lab application to begin
- to quit application: Command + Q on Mac, Control +Q on PC
- click to open objects
- objects have to be given a unique name to appear in the message list of other objects
- hold Alt down to move objects around
- overlapping objects are grouped and only shown as having one input/output path
- hold Alt down and drag on darkened overlap area to move grouped objects around
- hold Alt down to drag objects out of a group
- Alt click on background to dim/brighten paths
- Alt click to open up screen buttons at the bottom of the display
- serial port selection under OPTIONS (plus advanced mode scripting)
- load/save under PROJECTS
- click on the lights for info/cycle time (improved by disabling inputs)
- the POWER OFF button turns off all outputs, and sends a forget message to all actors
- Hold the Alt key down as you click on NEW (PROJECT) to be able to configure 
  the input and output objects,
  * to have a switch & light on the same input
  * to use a temperature sensor
  * to monitor the battery voltage
  * change the number of actors/counters.