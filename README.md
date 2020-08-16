# -Healthy-Programmer-Application
Everyone needs a break during their work and in break time they will drink water and eat some foods, do some physical exercise to re boost their energy with respect to that i will create this application which is good for programmers.those programmer who spend their most of time with laptops and they don't realize how time going so fast and they don't do any type of exercise and don't drink to much water in a day.a

Application Introduction:
This program tell to programmers in a specific time he/she needs to do some exercises and drink water. I used .mp3 sounds to alert the programmer it's time do something drink water or exercise.whenever time comes to take a break and do something then the sound is automatically ringing and asked to programmer he/she did that or not.

Program Details: 
In this program i used three python modules and three mp3 sounds to create this application.when you start this application in your system background and you are doing your work.in this program programmer needs to drink water in every 20 minutes,do eye exercise in every 30 minutes and do some physical exercise in every 45 minute.If you want to change the time then you change it as you wish.
whenever time comes to take a break,do something then the mp3 sound is automatically ringing and asked to program if you complete your task then just give input to stop that sound.
if the water sound ringing,programmer needs to write 'drank' to water sound.
if the eye exercise sound ringing,programmer needs to give input 'eyedone' to stop eye sound
if both exercise come a same time then he/she needs to give input 'bothdone' to stop that sound.
if physical exercise time come and physical sound ringing then he/she needs to give input 'phydone' to stop physical exercise sound.

if want to change the sound then you need to download an mp3 sound and replace the existing mp3 with new one.
whenever the programmer complete any of task and he/she give an input to stop a sound after that his/her activity name,time and date is store in a text file.the text file named as 'myNote' if you want to change the file then go to the function writeNote() and change the text name.

Used modules:
I used three modules:
Time module (It is built-in module in python you don't need to install it)
Date-time module (It is also built-in module in python you don't need to install it)
Pygame module (It is not a built-in module so you need to install this module using your pycharm terminal or cmd or windows powershell)

Install Pygame:
you need to open any terminal and write 'pip install pygame' it will be install/add in python packages after that you can use this module in python by importing the module.


