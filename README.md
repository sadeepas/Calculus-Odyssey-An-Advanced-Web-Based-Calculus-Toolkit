# Calculus-Odyssey-An-Advanced-Web-Based-Calculus-Toolkit
Calculus Odyssey is a powerful, all-in-one web application designed for students, educators, and professionals who work with calculus and advanced mathematics.

# Calculus Odyssey: An Advanced Web-Based Calculus Toolkit

## Description

Calculus Odyssey is a powerful, all-in-one web application designed for students, educators, and professionals who work with calculus and advanced mathematics. Built with modern web technologies, this interactive toolkit provides a suite of powerful utilities in a sleek, responsive, and user-friendly interface. From symbolic calculations and matrix operations to a highly interactive graphing canvas and a dedicated practice lab, Calculus Odyssey aims to make complex mathematics more accessible, visual, and intuitive.

The application is fully client-side, ensuring fast performance and privacy. It features a dark/light theme, multilingual support (English and Sinhala), and is designed to work seamlessly on both desktop and mobile devices.

## Features

Calculus Odyssey is organized into several distinct, powerful modules:

*   **📊 Interactive Graphing Lab:** A feature-rich graphing canvas that allows users to:
    *   Plot multiple functions simultaneously, including **Cartesian**, **Parametric**, and **Polar** equations.
    *   Visualize key calculus concepts in real-time, such as **tangent lines**, **derivatives**, and the **area under a curve** (definite integrals).
    *   Automatically find and display **critical points** (maxima/minima) and **intersections** between curves.
    *   Visualize **Newton's Method** for finding roots.
    *   Interact with the graph through panning, zooming, and inspecting coordinates.
    *   Save and share the graph state via a unique URL.

*   **🧮 Symbolic Calculator:** A robust calculator that can:
    *   **Evaluate** numerical expressions.
    *   **Simplify** complex algebraic expressions.
    *   Compute **derivatives** and **integrals** symbolically.
    *   **Solve** equations for a given variable.
    *   Keeps a persistent **history** of previous calculations for easy recall.

*   **🔢 Matrix Calculator:** A utility for performing common matrix operations, including:
    *   Calculating the **Determinant** and **Inverse**.
    *   Finding the **Transpose** of a matrix.
    *   Computing **Eigenvalues**.
    *   Adding and **Multiplying** matrices.

*   **✍️ Practice Lab:** A tool to sharpen your skills by:
    *   Generating random practice problems for **Derivatives** and **Integrals**.
    *   Providing instant feedback on user-submitted answers.

*   **⚖️ Unit Converter:** A handy utility to convert between various units of:
    *   Length, Mass, Time, and Angle.

*   **📚 Formula & Theorem Library:** A quick reference guide containing common derivative and integral formulas, as well as key theorems like the Fundamental Theorem of Calculus.

*   **✨ Modern User Experience:**
    *   **Light & Dark Mode:** Switch between themes for comfortable viewing.
    *   **Multilingual Support:** Easily toggle between English and Sinhala (සිංහල).
    *   **Fully Responsive:** A seamless experience on desktops, tablets, and smartphones.
    *   **Help System:** A built-in, context-aware help modal for each tool.

## How to Use

### Getting Started

1.  Open the `index.html` file in any modern web browser.
2.  Use the navigation sidebar on the left (or via the hamburger menu on mobile) to switch between the different tools.

### Using the Tools

*   **Graphing Lab**:
    1.  Click the **`+`** button to add a new function.
    2.  Select the function type by clicking the `C` (Cartesian), `P` (Parametric), or `R` (Polar) buttons.
    3.  Type your mathematical expression in the input field. The graph will update live.
    4.  Use the "Analysis" and "Applications" tabs to explore calculus concepts like tangent lines and definite integrals.

*   **Symbolic Calculator**:
    1.  Enter your mathematical expression (e.g., `x^3 - 4*x`) into the input field.
    2.  Select the desired operation (Simplify, Derivative, etc.) from the dropdown menu.
    3.  Click "Calculate". The result will appear below.
    4.  Click on any item in the "History" panel to reload a previous calculation.

*   **Matrix Calculator**:
    1.  Enter matrices in the format of nested arrays (e.g., `[[1, 2], [3, 4]]`).
    2.  Matrix B is only required for binary operations like multiplication.
    3.  Select an operation from the dropdown and click "Calculate".

*   **Practice Lab**:
    1.  Choose a topic (Derivatives or Integrals).
    2.  A problem will be generated. Type your answer in the input box using standard mathematical syntax (e.g., `4*x^3`).
    3.  Click "Check Answer" for feedback or "Next Problem" for a new challenge.

## Technologies Used

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+)
*   **CSS Framework:** [Tailwind CSS](https://tailwindcss.com/) (used via CDN for rapid UI development)
*   **Mathematical Engine:** [math.js](https://mathjs.org/) (for symbolic computation, matrix operations, and expression parsing)
*   **Icons:** [Font Awesome](https://fontawesome.com/) (for UI icons)
*   **Fonts:** Google Fonts (Inter, JetBrains Mono, Noto Sans Sinhala)

## Project Structure

*   `index.html`: The single HTML file containing the entire application structure, templates for each page, and all the CSS and JavaScript code.
*   `calculasico.ico`: The favicon for the application.

This project is self-contained in a single `index.html` file, making it highly portable and easy to deploy on any static hosting service.
