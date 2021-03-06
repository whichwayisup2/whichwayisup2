Which Way is Up? README
=======================

You're playing version Beta 2.0.0pre.



CREDITS & CONTACT:

Current developer: Daniel Foerster (pydsigner)

----

Original developer: Olli Etuaho
Home page: http://www.hectigo.net/
E-mail: admin at hectigo.net

----

DEPENDENCIES:

You might need to install some of these before running the game.

  Python:     http://www.python.org/
  PyGame:     http://www.pygame.org/
  PyTMX



RUNNING THE GAME:

On Windows or Mac OS X, locate the "run_game.py" file and double-click it.

Otherwise open a terminal / console and "cd" to the game directory and run:

  python run_game.py



HOW TO PLAY THE GAME:

The game gives you some instructions as you start playing.

Controls reference:

KEYBOARD:

Left/Right or A/D       Move
Z or Up or W            Advance game dialogue
                        Jump - the longer you hold down the button, the higher the character jumps
Down or S               Interact with the environment, pick up objects
P or Pause              Pause game

JOYSTICK OR GAMEPAD WITH 2 OR MORE BUTTONS:

Left/Right       Move
Button 1         Advance game dialogue
                 Jump - the longer you hold down the button,
                 the higher the character jumps
Button 2         Interact with the environment, pick up objects

JOYSTICK OR GAMEPAD WITH LESS THAN 2 BUTTONS:

Left/Right       Move
Up               Advance game dialogue
                 Jump - the longer you hold the pad or joystick,
                 the higher the character jumps
Down             Interact with the environment, pick up objects


MENUS:

ESC                    Main menu / Quit
Up/Down                Navigate the menu
Enter/Z/Button 1 or 2  Choose menu option


Oh, and one more thing - if you don't find the game challenging enough as it
is, try maximize your score by getting through it without losing any health
at all. This could be hard at some points, but it's always possible!
Improving speed records also provides some additional challenge.


SPEEDRUNNING:

The game implements an accurate frame-based timer, which records the total
time player uses to complete all the levels in a world. The current FPS is set
at 24, so you get the time in seconds by dividing the final time in frames by
24. Fading effects and scripted events with dialogue don't increase the timer,
so the dialogue setting shouldn't considerably affect the final time. Of
course, mid-level events may still interrupt the gameplay.

At the moment the game is still in beta, so changes to the levels and gameplay
are possible. Thus, records made with the current version might be better than
what is possible with upcoming versions.



ADDITIONAL INFORMATION:

The game has a home page at
http://hectigo.net/puskutraktori/whichwayisup/

Information about creating your own levels can be found in
data/levels/creating_levels.txt

The game saves unlock data etc. to the user's home directory.

In Linux, this is usually:
~/.wwisup2

In Windows XP/2000, this is usually:
C:\Documents and Settings\User\Application Data\Wwisup2

COMMAND LINE PARAMETERS:

-l level_name           Start up from the level specified.
-v                      Verbose mode - error messages appear in the console,
                        not just the log file.
-dev                    Developer mode. Activates verbose mode automatically.

DEVELOPER KEYBOARD COMMANDS:

F10                    Rotate level - chooses direction automatically.
                       Only available in developer mode.



LICENSE:

All game code is licensed under the GPL 2.0.
http://www.gnu.org/licenses/gpl.html

All game content, sounds and graphics are licensed under
Creative Commons 3.0 Attribution license.
http://creativecommons.org/licenses/by/3.0/

The included Bitstream Vera font is licenced separately.
For more information, see http://www.gnome.org/fonts/



