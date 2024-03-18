# Intro to C with Visual Studio (Not VSC)

## How-to make C project

MS Visual Code has not have menu for C project, but it supports this language through C++ menu

1. Lets start Vusual Code

<img src=img/01.png>

Select "Create a new project"

2. Choose from down menus "C++" "Windows" "Console"

<img src=img/02.png>

Then choose "Empty Project"

3. Project name must begin with character not digit

<img src=img/03.png>

Uncheck box "Place solution .." if you planing to place in one solution several projects. Then click next.

4. Class could be added with to ways. First one through main menu "File -> Add Class..."

<img src=img/04_1.png>

The second way through "Solution Explorer"

<img src=img/04_2.png>

5. Pop up windows called "Add Class" appears

<img src=img/05.png>

You should give name to "Class name" and "h.file", and in ".cpp file" field you must type name with *.c extension! Ok.

6. Main working space will open with Main.h file in it. You need to delete all content inside it.

<img src=img/06.png>

7. Through the "Solution Explorer" open "Main.c" file

<img src=img/07.png>


8. And delete all content inside int except "#include 'Main.h'" if you planing to use header files

<img src=img/08.png>

9. At last you could start you program with "Local Windows Debugger" button

<img src=img/09.png>

Or with "Start without Debugging" nearby button 

10. Terminal popups and you will see output from you program.

<img src=img/10.png>

11. If you are planing to make project without header files, you could delete them.

<img src=img/11.png>

Through "Solution Explorer"

12. When popup window asks you about deletion or removing

<img src=img/12.png>

Choose "Delete" button

13. And now you could delete line with header file from you Main.c

<img src=img/13.png>

14. You could also start debuging or running program through main menu "File-> Start Debugging"

<img src=img/14.png>

Or you could use F5 and Ctrl+F5 buttons

15. To prevent terminal from closing after program completion
 
<img src=img/15.png>

16. Go to main menu "Tools->Options->Debugging" 

<img src=img/16.png>

and uncheck box "Automatically close the console when debugging stops