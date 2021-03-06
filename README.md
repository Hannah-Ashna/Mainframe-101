# COBOL Exercises
As part of my placement role I have had to learn several different Mainframe based languages these include: COBOL, JCL, and DTB. As I progress through the tasks I have been given I'll be updating this repository to include my completed code/solutions for anyone else interested in learning the language.

-------------------------------
### Exercises:
The specficiation for each of the exercises can be found in this [document](https://github.com/Hannah-Ashna/COBOL-Exercises/blob/main/Exercises.pdf) while the input files and output samples can be found in this [resource](https://github.com/Hannah-Ashna/Mainframe-101/tree/main/Exercise%20Resources) folder. They were created by my mentor Ben. All my solutions for them can be found in either the [COBOL](https://github.com/Hannah-Ashna/COBOL-Exercises/tree/main/COBOL) or [DTB](https://github.com/Hannah-Ashna/COBOL-Exercises/tree/main/DTB) folders.

#### COBOL:
* EXPPROG1 - Moving Exercise
* EXPPROG2 - Arithmetic Exercise
* EXPPROG3 - Subscripting/Indexing Exercise
* EXPPROG4 - Extraction Exercise
* EXPPROG5 - Update Exercise
* EXPPROG6 - VSAM Mayhem Exercise
* EXPPROG7 - Conversion of a C++ Program to COBOL
* IMDPROG1 - Reworked EXPPROG1 to use IOMOD

#### DTB - Decision Table COBOL:
* DTBPROG1 - Rewriting EXPPROG1 using DTB
* DTBPROG3 - Rewriting EXPPROG3 using DTB
* DTBPROG5 - Rewriting EXPPROG5 using DTB

-------------------------------
### Templates:
A lot of stuff on the Mainframe is based off of pre-existing templates that have been modified to fit the purpose of one's code. I have included some [JCL](https://github.com/Hannah-Ashna/COBOL-Exercises/tree/main/JCL) and [Linkparm](https://github.com/Hannah-Ashna/COBOL-Exercises/blob/main/PROGNAME) templates that I used to link and run the exercises mentioned above. Different organisations will obviously have different standards so the templates may need to be modified to fit your organisation/team's standards.

#### JCL - Job Control Language:
* SAMPLE  - Basic template used for most of the Cobol Programs to handle file inputs and outputs
* VSAMDEF - Basic template for creation a VSAM
* GDGDEF - Basic template for the creation of a GDG Base
* GDGDEL - Basic template for deletion a GDG base
* COPYFILE - Basic template for copying (and overwriting) one file's contents into another
* MERGSORT - Basic template for merging the contents of multiple files into one single file with the addition of a sort by statement to organise the records based on a specified criteria
