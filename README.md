UCSD-CSE-Magic-Checker

Lay out all the numbers and their positions

Windows

.zip -- This is a .exe file to use in windows command line

How to use:

1. copy and extract the file into .java file's folder

2. in start, search cmd
   ,OR press Win + X choose run and type cmd.

3. in command line mode, type "cd files'directory"

4. type "magicnumchecker filename.java"

* please note, at the end of the program you will be able to search.
  if you don't need, just press any key other than enter then press enter.
  Since you only have one shot of searching, this will help you exit from the program.
  
  
Linux

.out -- command line program as well. This is a portable file, no installation needed

How to use:

1. Download to target directory

2. in command line (just as compile a .java file) type "./mgcheck.out filename.[extensjion]". DONE!

3. This also has a search function, a one time search, but can be terminated as usual: CTRL+C

4. Compare to windows version, since this is a latest one, I made a little modification, so the filter here should be a little better.

5. Because "." is massively used in programming as well as a part of a number, I decided to keep it. If for any reason you see "." along in the result, don't worry. It should not be part of a number in the program.

* Let me know if there is any bug that I want to fix ;)

Here is the result of Linux Version:

Number: -1  is in Line# 9, 12, 

Number: .  is in Line# 23, 24, 28, 

Number: 0  is in Line# 9, 10, 11, 12, 

Number: 1  is in Line# 10, 11, 

Number: 1.2  is in Line# 3, 

There is/are 1  Number: 1.2

There is/are 2  Number: -1

There is/are 2  Number: 1

There is/are 3  Number: .

There is/are 4  Number: 0

Please Enter the word you want to search for...
