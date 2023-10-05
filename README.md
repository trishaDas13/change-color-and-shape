# change-color-and-shape

Hosted Link : https://trishadas13.github.io/change-color-and-shape/


<h2>HTML code explanation</h2>

Within the "body" of this HTML document, there's a "div" element with the class "container." This "div" serves as a container for organizing the content on the webpage.

Inside the "container" "div", there's another "div" with the class "round." This "round" "div" is likely going to be used to create a circular or rounded shape on the webpage.

Inside the "round" "div", there's a "div" element with the ID "square." This "square" "div" may be used to represent a square or rectangular shape on the webpage.

Following the "round" "div", there's another "div" with the class "btn." This "btn" "div" is expected to contain one or more buttons.

Inside the "btn" "div", there are two "button" elements. The first button has the label "Change Color," suggesting that it will likely trigger an action to change the color of some element on the webpage. The second button has the label "Change Shape," indicating that it might trigger an action to change the shape of an element.

<h2>CSS code explanation</h2>

The universal selector * is used to apply the following styles to all elements:

margin: 0; removes any margin space around elements.
padding: 0; removes any padding within elements.
box-sizing: border-box; sets the box-sizing model to border-box, which includes padding and borders within the element's total width and height.
The body element is styled:

width: 100%; sets the width of the body to 100%.
height: 100vh; sets the height of the body to 100% of the viewport height.
display: flex; uses flexbox for layout.
justify-content: center; horizontally centers its child elements.
align-items: center; vertically centers its child elements.
background-color: rgb(234,244,244); sets the background color to a shade of blue.

The .round class styles a circular shape:

width: 150px; sets the width of the shape.
height: 150px; sets the height of the shape.
background-color: green; sets the background color of the shape to green.
border-radius: 50%; creates a circular shape using border-radius.
display: flex; uses flexbox for layout.
justify-content: center; horizontally centers content within the shape.
align-items: center; vertically centers content within the shape.

The .container class styles a container element:

width: 400px; sets the width of the container.
height: 400px; sets the height of the container.
box-shadow: 0px 0px 51px -5px rgba(77,77,77,1); adds a box shadow to the container.
display: flex; uses flexbox for layout.
justify-content: center; horizontally centers its child elements.
align-items: center; vertically centers its child elements.
flex-direction: column; arranges child elements in a column.
gap: 40px; adds a gap between child elements.
border-radius: 20px; rounds the corners of the container.
background-color: white; sets the background color of the container to white.
Several shapes are styled with IDs (#square, #round, #diamond, etc.), and they are created using the clip-path property. Each shape has a specified width, height, and background color.

A button style is defined:

appearance: none; removes the default appearance of the button.
background-color: #000000; sets the background color of the button to black.
border: 2px solid #1A1A1A; adds a border with a specified color and width.
border-radius: 15px; rounds the corners of the button.
box-sizing: border-box; includes padding and borders in the button's total width and height.
color: #FFFFFF; sets the text color to white.
cursor: pointer; changes the cursor to a pointer when hovering.
font-family: ...; specifies the font family for the button text.
font-size: 16px; sets the font size.
font-weight: 600; sets the font weight to bold.
padding: 10px; adds padding inside the button.
text-align: center; centers the text horizontally.
text-decoration: none; removes text decoration.
transition: all 300ms cubic-bezier(...); applies a smooth transition effect.
user-select: none; prevents text selection.
-webkit-user-select: none; prevents text selection on Webkit browsers.
touch-action: manipulation; optimizes touch interactions.
width: 40%; sets the button width.
will-change: transform; prepares for the transformation effect.
The button:disabled, button:hover, and button:active pseudo-classes define styles for the button in different states.

The .btn class styles a container for buttons:

width: 100%; sets the width to 100%.
display: flex; uses flexbox for layout.
justify-content: space-around; evenly distributes buttons horizontally.
flex-wrap: wrap; allows buttons to wrap to the next line if necessary.

<h2>JavaScript code explanation</h2>
It selects an HTML element with the class "round" and stores it in a variable called round.

It selects all the HTML button elements and stores them in a NodeList called btn.

It selects an HTML element with the id attribute "square" and stores it in a variable called shape.

An event listener is attached to the first button (btn[0]), which triggers the changeColor function when clicked.

Inside the changeColor function, a random color is generated by calling the genarateColor function, which generates a random RGB color value. This color is then applied as the background color to the round element, effectively changing its background color to a random color.

Another event listener is attached to the second button (btn[1]), which triggers the changeShape function when clicked.

The changeShape function randomly selects a shape from an array called arr, which contains various shape IDs. It assigns the selected shape ID to the shape element's id attribute, changing its shape dynamically.

<h2>UI</h2>

[screen-capture (1).webm](https://github.com/trishaDas13/change-color-and-shape/assets/126088849/caf16290-4648-40f1-95b6-bce94cd16d49)
