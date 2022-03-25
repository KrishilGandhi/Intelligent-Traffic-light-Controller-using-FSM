# Intelligent-Traffic-light-Controller-using-FSM
A Verilog HDL Code for an Intelligent Traffic Light Controller ( Using Moore State Machines)
Here is a code for an Intelligent Traffic Light Controller in Verilog HDL which is made for a crossroads with a high traffic Highway road and a low traffic Farm road which has a sensor which detects if there are any vehicles on the Farm road.There will be green light on the Farm Road only when there are vehicles on the Road in order to give the priority to the highway vehicles
The behaviour of the controller is as followed:
The highway light shall remain green as long as the sensor signal is LOW but must be green for at least 30 seconds at a time.
Once transitioned to green, the farm road light shall remain green for at least 3 seconds.
As long as the sensor signal is high, the farm road light shall remain green but not for more than 15 additional seconds in order to give priority to the highway.
All signal light transitions from green shall proceed to yellow and then to red.
When going from green to red, first the light will turn yellow from green for 3 seconds and then it will turn red from yellow for 1 second.
