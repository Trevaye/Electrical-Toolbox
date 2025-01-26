# Electrical Toolbox

Welcome to the Electrical Toolbox! This simple web application helps electricians and technicians calculate the required wire length for installations. It provides an easy way to include additional adjustments and accounts for vertical height if needed.

## Features
- Calculate wire length based on distance and optional height (using the Pythagorean theorem).
- Add extra wire length for corners or adjustments.
- Easy-to-use interface with no external dependencies.

## How It Works
1. Input the distance (in meters) from the power source to the installation point.
2. Optionally, input the height (in meters) for vertical installations.
3. Add extra length (in meters) if needed for adjustments.
4. Submit the form to calculate the total wire length required.

## Video Demo
Watch the demo and walkthrough of the code here: https://youtu.be/WELP7-aKag4

## How to Run
1. Download the `index.html` file from this repository.
2. Open the file in any modern web browser.
3. Use the form to input the necessary details and calculate the required wire length.

## Code Walkthrough
The application consists of a single HTML file:
- The **form** takes user input for distance, height, and extra length.
- A small JavaScript block processes the input and calculates the wire length using:
  - Basic addition for extra wire.
  - The Pythagorean theorem for installations that involve height.
- Results are displayed dynamically on the same page.

## Feedback
Feel free to report issues or suggest improvements by opening an issue in this repository.

---

Thank you for using the Electrical Toolbox!
