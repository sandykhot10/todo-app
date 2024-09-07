<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do App - README</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            padding: 20px;
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #4a90e2;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.1rem;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        code {
            background-color: #f9f9f9;
            padding: 5px;
            border-radius: 5px;
            color: #e74c3c;
        }
        pre {
            background-color: #f9f9f9;
            padding: 15px;
            border-radius: 5px;
            border-left: 4px solid #4a90e2;
            font-size: 0.9rem;
            overflow-x: auto;
        }
        a {
            color: #4a90e2;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .screenshot {
            text-align: center;
        }
        .screenshot img {
            max-width: 100%;
            border-radius: 12px;
            margin-bottom: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            color: #777;
            font-size: 0.9rem;
        }
        .footer a {
            color: #4a90e2;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>To-Do App</h1>
        <p>Welcome to the To-Do App! This simple and elegant application helps you manage your daily tasks effortlessly.</p>      
        <h2>Features</h2>
        <ul>
            <li>Add new tasks</li>
            <li>Mark tasks as completed</li>
            <li>Delete tasks</li>
        </ul>
        <h2>Screenshot</h2>
        <div class="screenshot">
            <img src="screenshot.png" alt="To-Do App Screenshot">
        </div>
        <h2>How to Use</h2>
        <p>Follow these steps to get started with the To-Do App:</p>
        <ol>
            <li>Clone the repository:
                <pre><code>git clone https://github.com/your-username/todo-app.git</code></pre>
            </li>
            <li>Navigate to the project directory:
                <pre><code>cd todo-app</code></pre>
            </li>
            <li>Install the dependencies:
                <pre><code>npm install</code></pre>
            </li>
            <li>Start the application:
                <pre><code>npm start</code></pre>
            </li>
        </ol>
        <h2>Built With</h2>
        <ul>
            <li>HTML5, CSS3, JavaScript</li>
            <li>React.js</li>
            <li>Node.js</li>
        </ul>
        <h2>Contributing</h2>
        <p>If you'd like to contribute to the project, feel free to create a pull request or open an issue on the <a href="https://github.com/your-username/todo-app">GitHub repository</a>.</p>
        <div class="footer">
            <p>Built with ♥ by <a href="https://your-portfolio.com">Your Name</a></p>
        </div>
    </div>
</body>
</html>
