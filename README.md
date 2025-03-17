# JavaScript Applications

This repository contains a set of JavaScript-based applications, each demonstrating different interactive features and functionalities built using HTML, CSS, and JavaScript. The apps included are a Countdown Timer, a Drawing App, and a Quiz App. All of these applications are modular and can be run independently.

## Project Overview
The directory includes three primary applications, each with JavaScript functionality that showcases specific web development techniques.

**1. Countdown Timer**

A countdown timer that counts down to a specified time and displays a snow effect using JavaScript.
- Use of `setInterval` for updating the countdown timer at regular intervals.
- Manipulation of DOM elements to update the timer display dynamically.
- Simple animation using JavaScript to create a snowflake effect by manipulating the position of snowflake elements over time.

**2. Drawing App**

A simple drawing application that allows users to draw on a canvas element using their mouse.
- Utilizes the HTML5 `<canvas>` element and JavaScript's 2D canvas API (`getContext('2d')`) to draw shapes and paths.
- Event listeners (`mousedown`, `mousemove`, and `mouseup`) to detect user input and handle drawing actions.
- Functionality to choose different brush sizes and colors dynamically through JavaScript.

**3. Quiz App**

A quiz application that presents multiple-choice questions to the user and evaluates their answers.
- DOM manipulation to render quiz questions and options dynamically.
- Event handling for answering questions, tracking the score, and navigating between questions.
- Use of arrays and objects to manage question data and answer choices.

## App Functionality
**1. Countdown Timer**
- `startCountdown()`: Initializes the countdown using setInterval. It decrements the time every second and updates the display. When the timer reaches zero, it clears the interval and triggers an alert.
- **Snowflake Animation**: A dynamic snow effect is achieved by creating multiple `div` elements representing snowflakes and animating their movement across the screen using JavaScript's `setInterval` and `Math.random()` to randomize their positions.
**Key Concepts:** 
- DOM manipulation: Accessing and updating the inner text of elements.
- Timer functions: Using `setInterval` for continuous updates.
- Event listeners: Triggering countdown start on user interaction.
**2. Drawing App**
- `startDrawing()`: Begins drawing when the user clicks and drags the mouse, setting the initial drawing coordinates and connecting them with lines.
- `stopDrawing()`: Ends the drawing when the user releases the mouse button.
- `changeBrushSize()`: Dynamically adjusts the brush size based on user input from the interface.
- `changeColor()`: Changes the brush color when the user selects a new color.
**Key Concepts:**
- Canvas API: Use of `getContext('2d')` to draw paths, lines, and shapes on a canvas.
- Event handling: Responding to `mousedown`, `mousemove`, and `mouseup` events to track the user's actions.
- State management: Storing and updating variables for brush size and color.
**3. Quiz App**
- `loadQuestion()`: Dynamically loads the current question and its answer options into the DOM.
- `submitAnswer()`: Validates the selected answer and updates the score accordingly.
- `nextQuestion()`: Advances to the next question in the quiz.
- `showResult()`: Displays the total score once the user completes the quiz.
**Key Concepts:**
- DOM manipulation: Dynamically creating HTML elements based on question data.
- Event listeners: Handling user interactions for answer selection and navigation.
- Data structures: Using arrays or objects to store questions and answers.
## Technologies Used
- HTML: Provides the structure for each app.
- CSS: Used for layout and styling to make the apps visually appealing.
- JavaScript:
    - DOM Manipulation: For creating, reading, updating, and deleting HTML elements dynamically.
    - Canvas API: Specifically used in the Drawing App for rendering drawings.
    - Event Handling: To handle user interactions like clicks, drags, and selections.
