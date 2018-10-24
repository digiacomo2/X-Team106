# X-Team 106 Quickest Route

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

While traveling by bus whats the quickest way to get from point A to point B?
We would have a program the implements a weighted directed graph data structure that calculates the quickest route from one point to another. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Quickest route


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Initial bus and stop, then any intermediate bus switches with stop number and new bus number, final stop.
Example:
Bus 3 Stop 5
Bus 6 Stop 8
Stop 10


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Starting location(stop number) and desired destination(stop number)

Starting Location: 3
Desired Location: 11


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

We would use a simple GUI that would display a map that could be clicked on to determine the start and stop locations



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

RouteMap
Bus
Stop
UserInterface



Name each interface or class and briefly describe its function or purpose.

RouteMap: stores information location of all stops
Bus: stores all stops for each bus(subgraph of travel)
Stop: stores information about time to next stop depending on bus
UserInterface: used to make the userinterface described earlier

## Edit and Submit this file and any figures referenced by this document.

