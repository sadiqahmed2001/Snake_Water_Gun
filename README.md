# Snake_Water_Gun
simple "Snake Water Gun" game where the user can choose their option (Snake, Water, or Gun) either by typing it into an input field or by clicking buttons.


<!DOCTYPE html> specifies the document type and version of HTML.
<html lang="en"> defines the HTML document's root element with English as the language.
The <head> tag contains meta-information about the HTML document, including character encoding and viewport settings.

<meta charset="UTF-8"> specifies the document's character encoding as UTF-8.
<meta name="viewport" Content="width=device-width, initial-scale=1.0">: Sets the viewport's width and initial zoom level.
<title>Snake Water Gun</title>: Changes the title of the HTML document to "Snake Water Gun".
<style> defines the CSS styles for the HTML document.
Styles applied to the full document body.
Styles applied to level 1 headers (the game's primary heading).
#Container: Styles for the container div element.
input[type="text"]: Styles for text input fields.
button: Styles for buttons.
#result: Styles applied to the results display area.
The HTML document's primary material is located in the <body> element.

<h1>: Displays the game's primary heading.
The <div id="container"> contains the input field, "Play" button, and result display area for the user to manually input.

<input type="text" placeholder="Enter S, W, or G" id="userChoice">: The user can manually enter their choice (Snake, Water, or Gun).
<button onclick="Play()">Play</button>When clicked, the play() method is invoked to start the game.
<div id="result">.</div>: Displays the game's outcome (win, loss, or tie).
The next part is for lazy users who wish to fast choose their option by clicking buttons:
<div class="container" align="center"> is another container div element.
<h1>: Shows a heading for lazy users.
<div id="game">: Includes buttons for Snake, Water, and Gun.
<button onclick="Play('s')">Snake</button>: When clicked, it calls the play() method with's' (Snake) as an argument.
<button onclick="Play('w')">Water</button>: When clicked, it calls the play() method with the parameter 'w' (Water).
<button onclick="Play('g')">Gun</button>: When pressed, the play() function is called with the parameter 'g' (Gun).
<div id="result"></div>: Shows the game outcome (win, loss, or draw) for inactive users.
Finally, the <script> element contains JavaScript code.

The function play() {... } defines the play() function, which is executed when the user presses the "Play" button or any of the option buttons. This function calculates the game's outcome based on the user's selection and the computer's randomly generated selection, and shows the result on the page.
Overall, this code provides a simple gaming interface for the "Snake Water Gun" game.

