# CodeClub Resources

## Scratch

* [CodeClub Teaching Materials](http://projects.codeclubworld.org/en-GB/)
  * [Beginner Scratch](http://projects.codeclubworld.org/en-GB/01_scratch_01/index.html)
    * [Lesson 1 - Rock Band(requires speakers)](http://projects.codeclubworld.org/en-GB/01_scratch_01/01/Rock%20Band.html)
    * [Lesson 2 - Lost in Space](http://projects.codeclubworld.org/en-GB/01_scratch_01/02/Lost%20in%20Space.html)
    * [Lesson 3 - Chostbusters](http://projects.codeclubworld.org/en-GB/01_scratch_01/03/Ghostbusters.html)
    * [Lesson 4 - ChatBot](http://projects.codeclubworld.org/en-GB/01_scratch_01/04/ChatBot.html)
    * [Lesson 5 - Paint Box](http://projects.codeclubworld.org/en-GB/01_scratch_01/05/Paint%20Box.html)
    * [Lesson 6 - Boat Race](http://projects.codeclubworld.org/en-GB/01_scratch_01/06/Boat%20Race.html)
  * [Advanced Scratch](http://projects.codeclubworld.org/en-GB/02_scratch_02/index.html)
    * [Lesson 1 - Memory](http://projects.codeclubworld.org/en-GB/02_scratch_02/01/Memory.html)
    * [Lesson 2 - Dodgeball](http://projects.codeclubworld.org/en-GB/02_scratch_02/02/Dodgeball.html)
    * [Lesson 3 - Brain Game](http://projects.codeclubworld.org/en-GB/02_scratch_02/03/Brain%20Game.html)
    * [Lesson 4 - Catch the Dots](http://projects.codeclubworld.org/en-GB/02_scratch_02/04/Catch%20the%20Dots.html)
    * [Lesson 5 - Clone Wars](http://projects.codeclubworld.org/en-GB/02_scratch_02/05/Clone%20Wars.html)
    * [Lesson 6 - Create Your Own World](http://projects.codeclubworld.org/en-GB/02_scratch_02/06/Create%20Your%20Own%20World.html)
  * [Beginner Python](http://projects.codeclubworld.org/en-GB/09_python/index.html)
    * [Lesson 1 - ASCII Art](http://projects.codeclubworld.org/en-GB/09_python/01/ASCII%20Art.html)
    * [Lesson 2 - The Year 2025](http://projects.codeclubworld.org/en-GB/09_python/02/The%20Year%202025.html) (*Note*: See notes below about the print and input functions)
    * [Lesson 3 - Quiz](http://projects.codeclubworld.org/en-GB/09_python/03/Quiz.html)
    * [Lesson 4 - Turtle Power](http://projects.codeclubworld.org/en-GB/09_python/04/Turtle%20Power.html)
    * [Lesson 5 - Gameshow](http://projects.codeclubworld.org/en-GB/09_python/05/Gameshow.html)
    * [Lesson 6 - Compliment Generator](http://projects.codeclubworld.org/en-GB/09_python/06/Compliment%20Generator.html)
  * [Intermediate Python](http://projects.codeclubworld.org/en-GB/10_python/index.html)
    * [Lesson 1 - Secret Messages](http://projects.codeclubworld.org/en-GB/10_python/01/Secret%20Messages.html)
    * [Lesson 2 - Teaching Turtles](http://projects.codeclubworld.org/en-GB/10_python/02/Teaching%20Turtles.html)
    * [Lesson 3 - Text-speak Converter](http://projects.codeclubworld.org/en-GB/10_python/03/Text-speak%20Converter.html)
    * [Lesson 4 - Pokedex](http://projects.codeclubworld.org/en-GB/10_python/04/Pokedex.html)
    * [Lesson 5 - RPG](http://projects.codeclubworld.org/en-GB/10_python/05/RPG.html)
    * [Lesson 6 - Minecraft2D](http://projects.codeclubworld.org/en-GB/10_python/06/Minecraft2D.html)
 * [List of Programming Resources](https://github.com/CodeNL/curated-programming-resources/blob/master/resources.md)


Note for Python Lessons
-----------------------

The lab computers we're using only have `Python 2.7` installed, but the lessons use `Python 3`. The two versions are mostly compatible, but there are two commands that won't work properly in the Python lessons.

 * print
  
  For the `print` command, it won't behave properly under some circumstances. To fix this, copy and paste this line to the top of the file:

   `from __future__ import print_function`
   
   Once that line has been added to the top of the file, the print function will work as shown in the lessons.
   
 * input
   
 The `input` function will not work as described in the lessons either. Instead, you should use `raw_input` in place of `input`. `raw_input` will behave as `input` does in the lessons.

