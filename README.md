# Assignment 06: Methods Are Your Madness

## Due: Friday, November 10, 2017 @ 11:59pm

Methods (or functions or procedures or subroutines or whatever you call them) are insanely useful. Without them, any codebase of any appreciable complexity becomes a nightmarishly long cerebellum-punch. Ow.

To get you used to writing methods, in this assignment you'll be writing some static method libraries – like the Math one you've used a number of times over the last few months. 

Oh, yeah – since reading documentation is something that you have to get used to if you want to be a developer, guess what you'll have to do in this assignment….

## The Challenges

In the each of the four classes (Banner, Depreciation, Dice, and MoneyFormat), there is documentation for two methods you will need to implement. Go read the documentation –  you can either read the docs directly in the code, or press Ctrl+J when in the editor to see the docs nicely formatted.

**MAKE THIS HAPPEN:**
1.	Implement each of the methods as a public static method. (This is fancy-speak for "enter code in each method so that it does what it's supposed to do".)

**NOTES:**
* Feel free to make your own class for trying out your methods – just put it in the BlueJ project, throw in a Java main() and call the methods you want to test. 
* You can use your library methods like you would any of the methods in the Math library – for example, if you wanted to try out the displayStandard method in the Banner class with the string "foo", you would call Banner.displayStandard("foo") in your code somewhere.
* If you want to make any helper methods for your public methods - and this is a **great** habit to start getting into -  please mark them as private.
* For the MoneyFormat methods, you might find using String.format() very useful. How does it work? It’s basically the same thing as System.out.format() … but it returns a formatted String instead of printing to the console. Further details can be found in the API.
