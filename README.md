# Visual-Interaction-Selector
This GitHub repository contains a mock webpage with interactive elements. The page includes three buttons, two links, a dropdown, and a video.
The main feature is the "Selection Mode" button, allowing users to select, deselect, and track interactive elements. When in selection mode, elements get highlighted when hovered over, and their interactions are logged to the console. Clicking on any interactive element triggers an alert.
 

# HTML Structure:
This code defines the structure of a basic webpage. It includes a title, a heading, and a container with interactive elements such as buttons, links, a dropdown, and a video.

# Selection Mode Button:
The "Selection Mode" button toggles a mode that allows users to select, deselect, and track interactive elements. It changes its text to "Enter Selection Mode" or "Exit Selection Mode" when clicked.

# JavaScript Functions:
•	showAlert(element): When any interactive element is clicked, this function displays an alert showing the element's label.
•	selectionMode(): This function is currently empty, but it's intended for managing the selection mode.

# Event Listeners:
Event listeners are used to respond to user interactions:
•	On clicking the "Selection Mode" button, it toggles selection mode and updates the button's text.
•	When the mouse hovers over an element, it gets highlighted with a blue border if selection mode is not active.
•	When the mouse hovers over an element, and it's selected for tracking, the element's tag and content are logged to the console.
•	When an interactive element is clicked, it toggles its "selected" state and logs a message indicating it's selected for tracking.

# CSS Link: 
This code links to an external "style.css" file to apply styles and enhance the webpage's appearance.

# CHALLENGES FACED DURING PROJECT
Receiving the project earlier than anticipated, I encountered challenges but successfully made significant progress, ensuring a successful completion.

# USAGE
To make the most of this Visual Interaction Selector webpage, follow these steps:
•	Clone or download this repository to your local machine.
•	Open the index.html file in a web browser of your choice to explore the interactive elements.
•	Click the "Selection Mode" button to enter or exit selection mode.
•	Interact with the elements to observe the highlighting and console logs.
•	Click on an interactive element to trigger an alert displaying the element's label.
