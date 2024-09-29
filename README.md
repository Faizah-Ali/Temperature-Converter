<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>README - Temperature Converter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f9;
        }

        h1, h2, h3 {
            color: #333;
        }

        ul {
            list-style-type: square;
        }

        .code-block {
            background-color: #f1f1f1;
            padding: 10px;
            border-left: 4px solid #333;
            margin-bottom: 20px;
            font-family: monospace;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Temperature Converter</h1>
        <h2>Project Overview</h2>
        <p>This is a simple <strong>Temperature Converter</strong> application built using <strong>React</strong> and <strong>CSS</strong>. The app takes temperature input in Celsius and converts it to Fahrenheit and Kelvin. It's designed with responsive UI features and a clean, easy-to-use interface.</p>

        <h2>Features</h2>
        <ul>
            <li>Converts Celsius to Fahrenheit and Kelvin.</li>
            <li>Responsive UI design for various devices (mobile and desktop).</li>
            <li>Real-time conversion with an easy-to-understand user interface.</li>
        </ul>

        <h2>Technologies Used</h2>
        <ul>
            <li>React (JavaScript)</li>
            <li>HTML</li>
            <li>CSS</li>
        </ul>

        <h2>How to Run the Project</h2>
        <ol>
            <li>Clone or download the project files from the repository.</li>
            <li>Ensure you have <strong>Node.js</strong> and <strong>npm</strong> installed on your machine.</li>
            <li>Open the terminal and navigate to the project directory.</li>
            <li>Install the required dependencies by running:
                <div class="code-block">
                    npm install
                </div>
            </li>
            <li>Start the development server by running:
                <div class="code-block">
                    npm start
                </div>
            </li>
            <li>Open your browser and go to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> to view the app.</li>
        </ol>

        <h2>File Structure</h2>
        <ul>
            <li><strong>src/App.jsx</strong> - Main component file for the Temperature Converter logic.</li>
            <li><strong>src/App.css</strong> - Contains the styling for the temperature converter UI.</li>
            <li><strong>public/index.html</strong> - Main HTML file for the app.</li>
        </ul>

        <h2>Formulas Used</h2>
        <ul>
            <li><strong>Fahrenheit:</strong> <code>(Celsius × 9/5) + 32</code></li>
            <li><strong>Kelvin:</strong> <code>Celsius + 273.15</code></li>
        </ul>

        <h2>Responsive Design</h2>
        <p>The UI is fully responsive, ensuring that the temperature converter looks good on both mobile and desktop devices. Flexbox is used for centering the content, and the app automatically adjusts to fit the screen size.</p>

        <h2>License</h2>
        <p>This project is open-source and available under the <strong>MIT License</strong>.</p>

    </div>

</body>
</html>
