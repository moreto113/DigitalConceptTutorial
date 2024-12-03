<h1>Tools and Setup</h1>

1. **A Plain Text Editor**
   - Examples: [Visual Studio Code](https://code.visualstudio.com/) or Notepad++.
   - Purpose: To write and edit the HTML and SVG code.

2. **A Web Browser**
   - Examples: Google Chrome, Mozilla Firefox, or Microsoft Edge.
   - Purpose: To preview your SVG design.

3. **Basic Knowledge of HTML**
   - If you're new to HTML, check out this website! [W3Schools HTML Tutorial](https://www.w3schools.com/html/).

<h1>Setting Up The Environment</h1>

1. **Install Visual Studio Code (VS Code)**
   - [Download VS Code](https://code.visualstudio.com/).
   - Follow the installation instructions for your operating system.

2. **Organize Your Workspace**
   - Create a folder for this project on your computer like `sunset-project`.

3. **Create an HTML File**
   - Open your text editor and create a new file named `index.html` inside your project folder.

4. **Add Code**
    - Add code to `index.html` like the code below:

    ```
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>SVG Sunset Over Mountains</title>
    </head>
    <body>
        <svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
            <!-- Gradient Sky -->
            <defs>
                <linearGradient id="skyGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                    <stop offset="0%" style="stop-color:orange; stop-opacity:1" />
                    <stop offset="100%" style="stop-color:purple; stop-opacity:1" />
                </linearGradient>
            </defs>
            <rect x="0" y="0" width="400" height="300" fill="url(#skyGradient)" />

            <!-- Sun -->
            <circle cx="200" cy="80" r="50" fill="yellow" />

            <!-- Mountains -->
            <polygon points="50,300 200,100 350,300" fill="#8B4513" />
            <polygon points="150,300 250,150 350,300" fill="#A0522D" />

            <!-- Ground -->
            <rect x="0" y="250" width="400" height="50" fill="#228B22" />
        </svg>
    </body>
    </html>
    ```


[Previous: Introduction](intro.md) | [Next: Final Code](final-code.md)
