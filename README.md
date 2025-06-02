# tps25-W8D1-tkinter-advanced-breakouts

Breakout #1 – Personalized Greeting Form
Demonstration Overview
In this breakout, you’ll build a basic interactive form that accepts a user’s name and displays a personalized greeting. This hands-on exercise helps reinforce the relationship between Entry widgets, StringVar, and event-driven functions. It’s a practical introduction to using user input in a meaningful and dynamic way.

🛠️ Instructions
Build a GUI application with the following components:
Prompt Label


A Label that instructs the user to enter their name (e.g., "Enter your name:").


Entry Field


An Entry widget where the user types in their name.


Greeting Label


A second Label that will display a personalized greeting (e.g., "Hello, Alice!"), which updates when the user clicks a button.


Button


A Button labeled “Greet Me” that triggers a function to:


Read the input from the Entry


Create a greeting string


Update the greeting Label with the new message

Bonus Challenge
After displaying the greeting, clear the Entry field so it’s ready for the next input.


Set a default greeting like “Hello, friend!” when the input is blank or on program start.



--------------------------------------------------------------------------------------------


Breakout #2 – Demonstration Overview
In this exercise, you’ll build a basic calculator interface using Tkinter. This task reinforces your understanding of:
Entry widgets for accepting numeric input,


Button widgets for triggering actions,


Label for displaying results,


and conditional logic to perform calculations.


The goal is to build a GUI where a user enters two numbers and clicks a button to see the result of addition, subtraction, or multiplication.

🛠️ Instructions
Your GUI should include:
Two Entry Fields


One for the first number (num1)


One for the second number (num2)


Three Buttons


Add ➕


Subtract ➖


Multiply ✖️
 Each button should calculate and display the result in the Label.


Result Label


A Label widget to show the result of the operation.



Bonus Challenge
Instead of three separate buttons, use an OptionMenu to choose the operation (+, -, or *) and have a single "Calculate" button.


This improves UI scalability and reduces code duplication.



Example Expected Behavior
User enters 5 and 3


Clicks Add


Result label updates: Result: 8


If invalid input is entered (e.g., letters), display:
Please enter valid numbers.

