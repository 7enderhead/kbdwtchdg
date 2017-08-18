Welcome to kbdwtchdg's documentation!
=====================================

Overview
--------

A watchdog running V-USB on an Attiny85 that identifies itself as a USB keyboard and sends keyboard strokes.

What Can kbdwtchdg Do?
----------------------

It sends a defined message via USB to the computer. It does that either after a specific period of time after being plugged in,
or after a capslock trigger (pressing capslock x times). 

State Diagram by PlantUML
-------------------------

.. image:: ../images/StateDiagram.png
   :scale: 100%
   :align: center

.. toctree::
   :maxdepth: 1
   :hidden:

   setup
   main
   changelog
