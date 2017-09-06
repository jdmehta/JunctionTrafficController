# JunctionTrafficController
## What is it?
This is code for controlling a traffic junction written in Verilog. While the problem is really a simple one, this code aims to implement a design where all individual signals change states based on whether it is "safe" for them to be green, given the state of other signals. This is done based on rotating priority of individual lanes. The intent behind this code is also to write a generic code which can handle all possible conditions (delay adjustment, special arrangements for buses, U-turns, etc.) based on only a safety-check list.
