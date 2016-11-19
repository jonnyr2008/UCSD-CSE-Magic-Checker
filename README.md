
Updated! UCSD-CSE-Magic-Checker

Lay out all the numbers and their positions

*Updated Content:

Nov. 19th. 16

Removed the search function at the end.

Improved result display and filter. Almost no redundant output.

Added number of header check.

====================== Windows ==================================

Windows

.zip -- This is a .exe file to use in windows command line

How to use:

1. copy and extract the file into .java file's folder

2. In start, search cmd, OR press Win + X choose run and type cmd.

3. in command line mode, type "cd files'directory"

4. type "mgcheck filename.[extension]"

5. For detailed usage, please double click the program and see.

==================== Linux(Unix) ==================================
  
Linux

.out -- command line program as well. This is a portable file, no installation needed

How to use:

1. Download to target directory

2. In command line (just as compile a .java file) type "./mgcheck.out filename.[extensjion]". DONE!

* Let me know if there is any significant bug.

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

You have 25       word/Number: public

You have 26       word/Number: */

You have 33       word/Number: private

You have potential 26 or 25 methods/classes . Please check if this is right.

You have potential 32 or 31 outside decleared variables. Please check.

Press any key to continue...
