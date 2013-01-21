Real_time_GPIO_driver
=====================

Filename: rt_gpio_driver_xenomai.c

Purposet: Test and demonstrate how to use the Real Time Driver Model (RTDM) of Xenomai

Date: January 2013

Comments: "Xenomai is a real-time development framework cooperating with the Linux kernel,
in order to provide a pervasive, interface-agnostic, hard real-time support to user-space 
applications, seamlessly integrated into the GNU/Linux environment." 
(source: www.xenomai.org). 
The Real Time Driver Model (RTDM) is Xenomai interface for real time device drivers.   
This module aims to demonstrate how to use RTDM for GPIOs. 
It is tested on a ARM developement platform embedding a minimal Linux-Xenomai system. 
A RS-232 to USB cable allows to controle the board from the development computer. 
The module is build using a cross-toolchaine created with Buildroot. 
