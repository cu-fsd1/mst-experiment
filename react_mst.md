# React MST Coding Questions (useState + Events Only)

This document contains three **basic React coding tasks** based only on:

-   React Functional Components
-   useState Hook
-   Event Handling

Students will complete **two types of submissions**:

1.  **Hard Copy Submission (Written Explanation)**
2.  **GitHub Repository Submission (Code Implementation)**

Please read the instructions carefully before starting.

------------------------------------------------------------------------

# Submission Instructions

## 1️⃣ Hard Copy Submission (Written)

Students must submit a **handwritten or printed explanation** of the
code for the tasks given below.

You **DO NOT need to write full code** in the hard copy.

Instead, you must explain:

• The **folder structure** of the React application\
• **How the code works internally**\
• **Which React hooks are used** and why\
• The **logic behind the implementation**\
• **What problems could arise** if the code is written poorly or
structured incorrectly\
• **How the code can be improved** to follow better React practices

Example points students can discuss:

-   Separation of components
-   Proper state management
-   Avoiding unnecessary re-renders
-   Clean event handling
-   Code modularity and reusability

This submission checks your **conceptual understanding of React**.

------------------------------------------------------------------------

## 2️⃣ GitHub Code Submission

Students must implement the solution and upload the **working React
project to GitHub**.

Steps:

1.  Create the React project using **Vite**
2.  Implement the required functionality
3.  Push the project to **GitHub**
4.  Submit the **GitHub repository link in the Google Form** provided

The Google Form will contain **two submission fields**:

• GitHub Repository Link\
• Confirmation of Hard Copy Submission

This submission checks your **practical coding ability**.

------------------------------------------------------------------------

# Question 1 -- Simple Counter Application

## Task

Create a simple React Counter Application that:

-   Displays a number on the screen
-   Has two buttons:
    -   Increment
    -   Decrement
-   Updates the number when buttons are clicked

## Example Folder Structure

src/ ├── components/ │ └── Counter.jsx ├── App.jsx └── main.jsx

## Concepts Covered

-   React Functional Components
-   useState Hook
-   Event Handling (onClick)

## Logic Explanation

-   The useState hook stores the counter value.
-   When the user clicks the Increment button, the value increases by 1.
-   When the user clicks the Decrement button, the value decreases by 1.
-   React automatically re-renders the component when state changes.

## Functionalities

-   Increase counter value
-   Decrease counter value
-   UI updates dynamically

## Possible Improvements

-   Add a Reset button
-   Prevent negative values
-   Improve UI styling

------------------------------------------------------------------------

# Question 2 -- Text Input Live Display

## Task

Create a React component where:

-   A user types text in an input field
-   The typed text is displayed live below the input

Example:

User types: Hello\
Display: You typed → Hello

## Example Folder Structure

src/ ├── components/ │ └── TextDisplay.jsx ├── App.jsx └── main.jsx

## Concepts Covered

-   useState Hook
-   Event Handling (onChange)
-   Controlled Components

## Logic Explanation

-   useState stores the input text.
-   The onChange event captures what the user types.
-   The state updates whenever the input changes.
-   The typed text is displayed dynamically on the screen.

## Functionalities

-   Capture user input
-   Display text instantly
-   Dynamic UI updates

## Possible Improvements

-   Add character count
-   Convert text to uppercase/lowercase using buttons
-   Add input validation

------------------------------------------------------------------------

# Question 3 -- Toggle Show/Hide Message

## Task

Create a React application that:

-   Has a button labeled **Show Message**
-   When clicked, a message appears on the screen
-   Clicking the button again **hides the message**

Example:

Button: Show Message\
Message: Welcome to React

## Example Folder Structure

src/ ├── components/ │ └── ToggleMessage.jsx ├── App.jsx └── main.jsx

## Concepts Covered

-   useState Hook
-   Boolean State Management
-   Event Handling

## Logic Explanation

-   useState stores a boolean value (true/false).
-   When the button is clicked, the value toggles.
-   If true → message is shown.
-   If false → message is hidden.

## Functionalities

-   Toggle visibility of message
-   Button click events
-   Conditional rendering

## Possible Improvements

-   Change button text dynamically (Show/Hide)
-   Add animation effects
-   Separate button into reusable component

------------------------------------------------------------------------

# Evaluation Criteria

Students will be evaluated based on:

• Understanding of React concepts\
• Explanation of folder structure\
• Logic explanation\
• Code quality in GitHub submission\
• Suggested improvements and problem analysis
