# Tarea-Examen2

Luis Aaron Nieto Cruz ([LuisAaronNietoCruz](https://github.com/LuisAaronNietoCruz))
 
National Autonomous University of Mexico (https://www.unam.mx/).

aaronnicruz@gmail.com

## Introduction

For this work it is intended to implement the command:

[Mb, time_up, time_download] = pingmb -n <Mb> -ip <dst>

Mb: file size in Mb
dst: destination IP

## Methodology 

Test for 2 interfaces from 192.168.0.200 from 1Mb, 10Mb, 20Mb,... up to 100Mb (in 10Mb steps):

10.99.1.138

132.247.186.67

Plot size vs time for up or download.

Steps:
1) Exchange keys between the web server and the storage server.
2) Copy the file to your account's public directory on the web server.
3) Use wget and scp for downloading and uploading data.
4) Upload everything to github.
5) 1Mb = 1024x1024 bytes.
 
## Requirements

For the realization of this project we import thread, sys, re.

We define a function called ping.

In another code we import the ping, sys and matplotlib functions for the graphical representation.
## Result 
![Alt text](https://github.com/LuisAaronNietoCruz/Tarea-Examen2/blob/main/Grafica.jpg 'Grafica')

31MB = 0.19, 41MB = 0.28, 51MB = 0.34, 61MB = 0.42, 71MB = 0.91, 81MB = 0.62, 91MB = 0.75

## References
https://classroom.google.com/u/0/c/NDY4ODc2ODY4MTA2
 
