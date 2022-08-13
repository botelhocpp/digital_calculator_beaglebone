# Digital Calculator in BeagleBone Black 🤖👨‍💻
## Final project made for the "TPSE I" course, a basic bare metal embedded systems programming.

<p align="center">
 <a href="#about">About</a> •
 <a href="#features">Features</a> •
 <a href="#technologies">Technologies</a> •
 <a href="#team">Team</a>
</p>

### About

This small project was conceived as the final project of the <b>TPSE I</b> course (stands for "TÉCNICAS DE PROGRAMAÇÃO PARA SISTEMAS EMBARCADOS", or PROGRAMMING TECHNIQUES FOR EMBEDDED SYSTEMS), where a simple calculator was developed, using a Beaglebone Black with Cortex-A8, a matrix keyboard, an LCD display and an external button.

The code consists of several libraries for the board components, which allowed the code to be highly modularized and organized. The code itself is contained in the file "main.c" and "start.s", where the former contains the application itself and the latter contains the system's boot code.

### Features

Below are the operations performed by the calculator, as well as the system features used.

1) Use of <b>General Purpose I/O (GPIO)</b> for the <b>Clear Button (C)</b>, for the <b>Matrix Keypboard</b>, and for the <b>LCD display</b>, as well as using External Interrupts (IRQ) for the GPIO connected to the button and keyboard pins.
2) Use the DMTimer timer for accurate counting of display update times.
3) Use of an LCD display to show the user the current operation performed on the calculator.
4) Use of a matrix keyboard to enter the digits, select the desired operation or clear the last entry/operation, as well as an external button to clear all operations.
5) Operations of the Calculator:
- Sum;
- Subtraction;
- Multiplication;
- Operations with negative numbers;
- Clear last entry (number or operation);
- Clear all;

### Technologies

- C99 language.
- BeagleBone Black with Texas AM335x.

![BeagleBone Black](https://i0.wp.com/makezine.com/wp-content/uploads/2013/04/beagleboneblack01.png?fit=1349%2C900&ssl=1)

### Team

- Developer: Pedro M. Botelho
- Advisor: Prof. Dr.  Francisco Helder Candido

