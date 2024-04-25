# Snake_Water_Gun
simple "Snake Water Gun" game where the user can choose their option (Snake, Water, or Gun) either by typing it into an input field or by clicking buttons.
<!DOCTYPE html>: Declares the document type and version of HTML.
<html lang="en">: Defines the root element of the HTML document with the language set to English.
<head>: Contains meta-information about the HTML document, such as character encoding and viewport settings.
<meta charset="UTF-8">: Specifies the character encoding for the document as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport to the width of the device and initial zoom level.
<title>Snake Water Gun</title>: Sets the title of the HTML document to "Snake Water Gun".
<style>: Defines the CSS styles for the HTML document.
body: Styles applied to the entire body of the document.
h1: Styles applied to level 1 headings (the main heading of the game).
#container: Styles applied to the container div element.
input[type="text"]: Styles applied to text input fields.
button: Styles applied to buttons.
#result: Styles applied to the result display area.
The <body> section contains the main content of the HTML document:

<h1>: Displays the main heading of the game.
<div id="container">: Contains the input field, "Play" button, and result display area for manual input by the user.
<input type="text" placeholder="Enter S, W, or G" id="userChoice">: Allows the user to input their choice (Snake, Water, or Gun) manually.
<button onclick="play()">Play</button>: Calls the play() function when clicked to initiate the game.
<div id="result"></div>: Displays the result of the game (win, lose, or tie).
Next, there's a section for lazy users who want to quickly select their choice by clicking buttons:

<div class="container" align="center">: Another container div element.
<h1>: Displays a heading for lazy users.
<div id="game">: Contains buttons for Snake, Water, and Gun.
<button onclick="play('s')">Snake</button>: Calls the play() function with 's' (Snake) as the argument when clicked.
<button onclick="play('w')">Water</button>: Calls the play() function with 'w' (Water) as the argument when clicked.
<button onclick="play('g')">Gun</button>: Calls the play() function with 'g' (Gun) as the argument when clicked.
<div id="result"></div>: Displays the result of the game (win, lose, or tie) for lazy users.
Finally, there's a <script> tag containing JavaScript code:

function play() { ... }: Defines the play() function, which is called when the user clicks the "Play" button or any of the choice buttons. This function determines the result of the game based on the user's choice and the computer's randomly generated choice, and displays the result on the page.
Overall, this code creates a simple game interface for playing the "Snake Water Gun" game.





