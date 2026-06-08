===================================================================================================
**** If you like the programs i'm porting and you want to donate to me, see the following URL: ****
**** http://www.bitwiseworks.com/shop/index.php?id_product=38&controller=product& id_lang=1    ****
****             Or send directly to me using PayPal: tellie@elbertpol.nl                      ****
****                All the money you send will go to the QT5 project                          ****
===================================================================================================

iqpuzzle v1.5.1   

 CONTENTS OF THIS FILE
 =====================

1. INTRODUCTION

2. REQUIREMENTS

3. INSTALLATION

4. LICENSE, COPYRIGHT, DISCLAIMER

5. CONTACT

6. CREDITS

7. SUPPORT AND DONATIONS

8. HISTORY

9. RESTRICTIONS


1. INTRODUCTION
===============

Welcome to iqpuzzle v1.5.1 port for OS/2 and eComStation.

iQPuzzle is a diverting I.Q. challenging pentomino puzzle.
Pentominos are used as puzzle pieces and more than 300 different board shapes are available, which have to be filled with them.

2. REQUIREMENTS
===============
  The following requirements can be installed either by rpm or by zip files  
  

  RPM Installation (preferred):
  ============================
  klibc
  -----
   1. yum install libc
  
  
  --------
   1. yum install libgcc1
   2. yum install libssp
   3. yum install libstdc++6 libstdc++
   4. yum install libsupc++6 libsupc++
   5. yum install libgcc-fwd

  Qt5 dll
  -------
   1. yum install Qt5Core Qt5Gui Qt5Wdgt

    
  Zlib  
  ----
   1. yum install zlib
  

3. INSTALLATION
===============

  Iqpuzzle
  ---
  1. It's create a directory for iqpuzzle.
  2. It's create a WPS object for iqpuzzle.exe.
  

4. LICENSE, COPYRIGHT, DISCLAIMER
=================================

(C) 2007-2026 ElThoro <elthoro@gmx.de> https://github.com/ElTh0r0/iqpuzzle

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.


5. CONTACT
==========

if you find a bug, then add a ticket to the trac at http://svn.netlabs.org/qtapps

Only bug reports with a reproducable bug are accepted. :-)



6. CREDITS
==========

The port was done by: Elbert Pol aka TeLLie

Thanks go to:

  * ElThoRo
  * Dmitry A. Kuminov
  * Silvan Scherrer

They either helped me when I had some nasty questions or did some testing for me.


7. SUPPORT AND DONATIONS
========================

Tea is based on volunteer work. If you would like to support further
development, you can do so in one of the following ways:


  * Donate to the Qt5 project

  * While working on Qt 5 for OS/2, we are glad to know that our work is being partly sponsored by the grateful OS/2 community.
    Given the scale of this project and all other OS/2 projects that we work on, and also the fact that the OS/2 world has limited financial resources nowadays, every penny counts.
    We need to pay our full-time and part-time developers for their hard work. So any contribution is highly appreciated!
    To do so, please visit our online shop where you can buy development units of a preferred value.
    https://www.bitwiseworks.com/shop/index.php

  * Contribute to the project: Besides actual development, this also includes maintaining the documentation and the project web site as well as help for users.

8. HISTORY
==========
Compiled now with Qt v5.15.2

# iQPuzzle [![Build status](https://ci.appveyor.com/api/projects/status/wn8nxv8qt26j1eyh/branch/main?svg=true)](https://ci.appveyor.com/project/ElTh0r0/iqpuzzle/branch/main) ![CI Workflow](https://github.com/ElTh0r0/iqpuzzle/actions/workflows/ci.yml/badge.svg)
iQPuzzle is a diverting I.Q. challenging pentomino puzzle. Pentominos are used as puzzle pieces and more than 300 different board shapes are available, which have to be filled with them.

![Screenshot](https://user-images.githubusercontent.com/26674558/93668022-33d13180-fa8a-11ea-9279-b8f4d8c5c217.png)

## Help translating
New translations and corrections are highly welcome! You can either fork the source code from GitHub, make your changes and create a pull request or you can participate on Transifex: https://www.transifex.com/elth0r0/iqpuzzle/

Additionally see [this page](https://github.com/ElTh0r0/iqpuzzle/issues/10) at GitHub.

## Create your own level
Manual for creating own levels can be found in the wiki: https://github.com/ElTh0r0/iqpuzzle/wiki


