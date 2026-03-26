# Responsive--Calculator
using HTML | CSS | JavaScript

🧮 Best Calculator ✨

A simple, responsive, and interactive calculator built using HTML, CSS, and JavaScript.
It works directly in the browser, with no backend needed, and is safe because it does not use eval().

-> You can see a live demo here:
Live link of Calculator : https://akashking7.github.io/Responsive--Calculator

-> Why We Don’t Use eval()

eval() runs any code in a string, which sounds easy for a calculator, but it’s dangerous:

Security risk – Someone could type malicious code and hack your app.
Crashes easily – Wrong input can break your calculator.
Slow & hard to maintain – The app has to read and run the string every time.

-> Our solution:

We only allow numbers and math operators.
We calculate safely using JavaScript logic, not eval().
Invalid input just shows "Error".
This keeps the calculator safe, reliable, and professional.

-> Features
-> Addition, subtraction, multiplication, and division
-> Decimal numbers support
-> Responsive layout — works on mobile, tablet, and desktop
-> Click animations for buttons for a realistic feel
-> Attractive gradient background with heading and emojis
-> Safe JavaScript — no eval() used
 How It Works
The HTML provides the structure with a display input and buttons.
The CSS handles layout, colors, responsiveness, and button click animations.
The JavaScript:
Appends clicked buttons to the display
Clears the display when C is clicked
Calculates the result safely using Function() with input validation
Shows “Error” if the input is invalid or calculation fails
