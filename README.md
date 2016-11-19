Updated! UCSD-CSE-Magic-Checker

Lay out all the numbers and their positions

*Updated Content:
Nov. 19th. 2016:

Added "/**" into count

Improved number of header counter -- to be more precise

Added: lay out Line number of header counter elements, So you can see and compare them yourself

for example:

/** in line 5

*/ in line 8

public in line 9

very possible you have a full load of header of a method/class

Nov. 19th. 16

Removed the search function at the end.

Improved result display and filter. Almost no redundant output.

Added System.out.print(ln) check, in case of forgetting to remove

Added number of header check.

====================== Windows ==================================

Windows

.zip -- This is a .exe file to use in windows command line

How to use:

1. copy and extract the file into .java file's folder

2. In start, search cmd, OR press Win + X choose run and type cmd.

3. in command line mode, type "cd files'directory"

4. type "mgcheck(.exe) filename.[extension]"

5. For detailed usage, please double click the program and see.

==================== Linux(Unix) ==================================
  
Linux

command line program as well. This is a portable file, no installation necessary

How to use:

1. Download to target directory

2. In command line (just as compile a .java file) type "./mgcheck filename.[extensjion]". DONE!

3. For detailed usage, please use the command above without filename entered and see.

* Let me know if there is any significant bugs.


Here is the result of SnakeController.java

WORD/NUMBER    |  LINE # (seperated by comma)

0                 Line# 123, 124, 170, 172, 173, 178, 228, 229, 244, 245, 385, 433, 436, 440, 443, 454, 656, 668, 670,

1                 Line# 68, 290, 302, 304, 312, 320, 328, 386, 447, 450, 454, 457, 461, 462, 465, 472, 479, 493, 498, 594,

1.                Line# 27,

10                Line# 29, 71,

2                 Line# 69, 70,

200               Line# 73,

2016              Line# 5,

2500              Line# 36,

3                 Line# 17, 65, 67,

50                Line# 64, 66, 72, 75, 79, 656,

600               Line# 76,

800               Line# 74,

System.out.println                Line# 172, 471, 478,

You have (safe) 1         word/Number: 1.

You have (safe) 1         word/Number: 200

You have (safe) 1         word/Number: 2016

You have (safe) 1         word/Number: 2500

You have (safe) 1         word/Number: 600

You have (safe) 1         word/Number: 800

You have (Warning!!) 2    word/Number: 10

You have (Warning!!) 2    word/Number: 2

You have (Warning!!) 3    word/Number: 3

You have (Warning!!) 3    word/Number: System.out.println

You have (Warning!!) 6    word/Number: 50

You have (safe) 19        word/Number: 0

You have (safe) 20        word/Number: 1

======= Number of Header check below ==================

WORD/NUMBER    |  LINE # (seperated by comma)

*/		  Line# 49, 60, 112, 120, 196, 212, 264, 360, 371, 382, 394, 408, 424, 490, 544, 557, 568, 579, 591, 601, 617, 633, 647, 665, 680, 691, 

/**		  Line# 2, 58, 106, 117, 191, 206, 259, 354, 365, 376, 389, 400, 418, 483, 541, 552, 563, 574, 585, 597, 611, 629, 644, 654, 675, 686, 

private		  Line# 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 79, 80, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 94, 95, 96, 98, 100, 101, 103, 104, 

public		  Line# 61, 113, 121, 197, 213, 265, 361, 372, 383, 395, 409, 425, 491, 545, 558, 569, 580, 592, 602, 618, 634, 648, 666, 681, 692, 


You have 25	  word/Number: public

You have 26	  word/Number: */

You have 26	  word/Number: /**

You have 33	  word/Number: private

You should have 26 methods/classes . Please check if this is right.

