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

1) Exchange keys between the web server and the storage server.
2) Copy the file to your account's public directory on the web server.
3) Use wget and scp for downloading and uploading data.
4) Upload everything to github.
5) 1Mb = 1024x1024 bytes
 
## Requirements

For the realization of this project we import subprocess, sys, re

We define a function called pingmb and then import it along with matplotlib for plot rendering

## Result 
![Alt text](https://github.com/LuisAaronNietoCruz/Exam2_Dynamic-Systems/blob/main/Fractal-Square.png 'Fractal-Square')

## References
