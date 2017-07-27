# Dev2050SimulateTheOpenGL
Just go to this "link http://wiki.codeblocks.org/index.php/Using_FreeGlut_with_Code::Blocks", this is pretty useful as a starting point.
In case the original link above does not work Code::Block windows users can read on from here.
A little Info on Glut32 and FreeGlut
The original Glut32 written by Mark Kilgard was ported over by Nate Robins. 
Download freeglut 2.8.1‑1 for MinGW --------> freeglut-MinGW-2.8.1-1.mp.zip
Copy and paste the gult32.lib to the ...\MinGW\lib folder, glut.h to the ...MinGW\include\GL folder and the glut32.dll file to the C:\Windows\System32 or C:\Windows\SysWOW64
After this you need to link the the gult32 library to your project before running and using this example. 
