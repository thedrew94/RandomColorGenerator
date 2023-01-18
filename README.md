# RandomColorGenerator
A button that on click generates a random color for the background

Step by step explanation of the code
The code first defines an array called "hex" that contains the values 0-9 and the letters "A" through "F".
It then declares a variable "btn" that gets the element with an ID of "btn" from the HTML document. It also declares a variable "color" that gets the first element with a class of "color" from the HTML document.
An event listener is added to the "btn" element that listens for a click event. When a click event occurs, the function inside the event listener will execute.
Inside the function, a variable called "hexColor" is declared and is initialized with the value "#".
A for loop is set to run 6 times, and in each iteration of the loop:
the function "getRandomNumber()" is called, which generates a random number between 0 and the length of the "hex" array.
The element in the "hex" array at the randomly generated index is added to the "hexColor" variable.
The current value of "hexColor" is logged to the console.
After the loop completes, the text content of the "color" element is set to the final value of the "hexColor" variable.
The background color of the body element is set to the final value of the "hexColor" variable.
The function "getRandomNumber()" is defined, which returns a random number between 0 and the length of the "hex" array.

2023/01/18 thedrew94
