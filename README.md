--------------------------------------------------------------
--------------------------------------------------------------
Desc: Tetris tutorial by Javier López
https://javilop.com/gamedev/tetris-tutorial-in-c-platform-independent-focused-in-game-logic-for-beginners/

Update 1: Tutorial updated for Visual Studio 2019 by Hristian Carabulea on February 13th, 2021 (carabulea.net)

I corrected two errors, which occurred in Visual Studio 2019:
    
    1. Edited the original .vcproj file and removed all the <Tool /> entries for VCWebServiceProxyGeneratorTool
    2. Recompiled.
    3. I edited the newly created .vcxproj file and added the following to each <link> tag:
           <ImageHasSafeExceptionHandlers>false</ImageHasSafeExceptionHandlers>
    4. I also changed the "Drop piece" key from x to v. It somehow feels better to the fingers. :-)

--------------------------------------------------------------

The sourcecode is under the "Creative Commons - Attribution 3.0 Unported". That means you can copy, distribute and transmit the work and to adapt it. But you must attribute the work (but not in any way that suggests that they endorse you or your use of the work). The way of attribute the work is up to you. You can just mention me (Javier López). A backlink would be also appreciated.

--------------------------------------------------------------
I uploaded the project under the GNU License.

--------------------------------------------------------------
Game Instructions: Use the following keys to play the game
--------------------------------------------------------------

    - ESC = Quit the game
    - y or z (bottom left, depending on your keyboard, e.g. US, German, etc.) = Rotate the piece
    - v = Drop piece
    - Left, Right, Down = rotate the pieces

--------------------------------------------------------------
The Windows game executable exists already in the Release folder under the name tetris_tutorial_sdl.exe.
--------------------------------------------------------------
To play the game you must have the following two files in the same directory of your choice. They both can be found in the Release folder:

    1. tetris_tutorial_sdl.exe
    2. SDL.dll
