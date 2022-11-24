Information about this fork
=============================

This is a fork of https://github.com/geoffreymbrown/STM32-Template.
The goal is to build and debug the template with current toolchain and
libraries under Visual Studio code. Target hardware is a STM32VLDISCOVERY board.

The book to the orginal repository can be found at https://legacy.cs.indiana.edu/~geobrown/book.pdf.
In the following the readme of the orginal repository:



STM32-Template
==============

A Build template for projects using the stm32vl discovery board,
CodeSourcery gnu toolchain, and the STM32F10x Standard Peripheral Library.

To test:

   (1) install the toolchain and libarary.
   (2) change the TOOLROOT and LIBROOT paths in Makefile.common
   (3) cd to Demo
   (4) type make

To create new projects

   (1) clone the Demo directory (name the directory appropriately)
   (2) change TEMPLATEROOT in the cloned makefile to point to the
       template directory
   (3) modify as needed, adding any needed library objects to the OBJ
       list in the Makefile
