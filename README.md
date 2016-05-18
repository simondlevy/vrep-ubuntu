vrep-ubuntu
===========

Launch the V-REP robot simulator from a docked icon on Ubuntu

I love using the V-REP simulator from Coppelia Robotics, but in Linux they tell
you launch it from the directory in which it was installed.  As shown in this
video, I figured out a workouround:

<ol>

<li>Download / clone this repository

<li>Edit vrep.sh and vrep.dekstop,changing for your own directory structure

<li>Put vrep.sh in $HOME/bin (or whever you specified in vrep.desktop)

<li>Put vrep.desktop in ~/.local/share/applications

<li>Put vrep.png in ~/.local/share/icons

<li>Click on the Unity launcher (swirly Ubuntu icon in upper-left of your screen),  
type V-REP, and drag the icon into the launcher
</ol>
