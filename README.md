# hinfinty_project
This repository contains the project performed in [Controle Hinf por Realimentação de Estados Aplicado a um Robô Omnidirecional](https://www.dropbox.com/s/hyhj96dbqk2cops/TFG_Cezar_Lemos.pdf?dl=0) in python. The code in this repository has some minor differences, as the sampling rate and some robot parameters, to the original project performed in the work.

## Robot

![Dynamic Diagram](https://raw.githubusercontent.com/czrcbl/hinfinity_project/master/figures/diagrama_dinamica_english.png  "Dynamic Diagram")

In the file `system_data.py` the robot parameters are defined and its state space representation is obtained.

## Project

![general_form](https://raw.githubusercontent.com/czrcbl/hinfinity_project/master/figures/forma_geral.png)

In the file `project.py`, functions to computer the H-infinty controller for an arbitrary system on the general form are defined.

## Simulation

In the notebook `evaluation_SCS` the results of projects with the SCS solver are analyzed, a controller is chosen and simulations are performed.

## Robot

The folder `robot` contains code for the communication with the robot.
