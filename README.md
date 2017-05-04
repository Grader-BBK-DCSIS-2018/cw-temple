# Coursework 4 - PiJ 2016/2017 - cw-temple - Jake Holdom

## Overview

This project used a pre made game called 'Phillip Hammond and the temple of gloom' with the objective of moving a character around a map to reach certain tiles. There are two different rounds to the game these are Escape and Explore.

## Escape

The escape game provides no access to the map information other than which neighbour nodes are closer to the orb which the character has to reach. 
The algorithm that completes this works by seeing which neighbouring node of the current node is closest to the orb until it reaches the destination. Each node the character steps on is saved to a list as well as the neighbours of that node and the characters next move will always be a new node that the character has not yet stepped on before. If the character runs out of possible moves from its current location then the the algorithm goes back through the list of nodes for all neighbours that haven't been checked and filters out the one which is closest to the orb. 

# Problems

## Explore
