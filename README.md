### **Group: IT1-2017**

**1. Shanazarova Nazmina**

**2. Askanbayev Daniyar**

**3. Kaysar Kazenov**


# **Sea battle**

Everyone's favorite game, which is familiar from childhood. In this variation, the game takes place between two people or a person and a computer

## **Disassembly of parts**

main.py - Creating a workspace

main_2.py - Draw a grid for ships and increase the workspace of our application/game for debugging and added 2 more buttons

main_3.py - Determine the number of the mouse button pressed and the coordinates of the mouse click within the playing field, determine which cell we click

main_4.py - Writing code to create and display enemy ships on the playing field

main_5.py - We are writing the code for the "Start again!" button, when you click on which the enemy ships on the playing field will be cleared and located in new places

main_6.py - We make it so that when you click on the cell with the mouse, a cross is drawn – if you hit the ship, or a zero – if you don't hit the ship

main_7.py - We remove the redundancy of the list of objects to be drawn on the screen and slightly change the function of drawing enemy ships

main_8.py - We make two functions of checking for victory

main_9.py - Expanding the playing field, now two players can play the game

main_10.py - We start creating ships for player №2 and add a button to display them on his playing field

main_11.py - We are starting to change the ship generation function for player №1 and №2. Now their number and size are the same for both players, but they are located in different places on the playing field

main_12.py - Learning to shoot at the second playing field - player №2

main_13.py - We are making a function to determine which player won: player №1 or player №2

main_14.py - We make a sign in the application window which player won: player №1 or player №2

main_15.py - We make the move of players №1 and player №2 alternate

main_16.py - Adding functionality to the game – man vs computer

main_17.py - Add a radio button to our game to switch game modes: human versus computer or human versus human

main_18.py - We adjust our code for the correct display of the interface depending on the size of the playing field

## **Scope of development**

PyCharm Community Edition 2022.3 

Download link: https://www.jetbrains.com/ru-ru/pycharm/

## **Tkinter module (Canvas)**

_Tkinter_ is a graphical cross-platform library based on Tk tools. This is free software that is included in the standard library of the Python programming language.

Tkinter includes many components. One of them is _Canvas_. Canvas is used in Python to output the following graphical primitives:

* Lines
* Rectangles
* Ellipses
* Text
* Windows
* Images

## **Example**

``` from tkinter import * ``` 

``` from tkinter import messagebox ``` 

In the first line, we import the _Tkinter_ module

Then we import the window, that is, our window should be able to close (warns about whether we want to close the window)
