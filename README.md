<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation Loading Bar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 5px;
            border-radius: 3px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
        }
        video {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <h1>Animation Loading Bar</h1>
    
    <p>A simple, elegant, and lightweight animation loading bar implemented using pure HTML and CSS. This project creates a smooth, infinite loading animation that can be easily integrated into any web project.</p>
    
    <h1>Output</h1>
    <video src="Output.mp4" controls width="640" height="360"></video>
    
    <h2>Features</h2>
    <ul>
        <li>Pure HTML and CSS implementation (no JavaScript required)</li>
        <li>Smooth infinite animation</li>
        <li>Responsive design</li>
        <li>Customizable colors and dimensions</li>
        <li>Cross-browser compatible</li>
        <li>No external dependencies</li>
    </ul>
    
    <h2>Installation</h2>
    <ol>
        <li>Clone this repository:
            <pre><code>git clone https://github.com/Shubham160600/Animation-Loading-Bar.git</code></pre>
        </li>
        <li>Open the HTML file in your web browser</li>
    </ol>
    
    <h2>Usage</h2>
    <h3>Basic Implementation</h3>
    <p>Copy the entire HTML file into your project. The loading bar will automatically center itself on the page.</p>
    
    <h3>Customization</h3>
    <p>Modify the CSS variables to customize the loading bar:</p>
    <pre><code>/* Change dimensions */
.loading-bar {
    width: 300px;    /* Adjust width */
    height: 20px;    /* Adjust height */
}
/* Modify colors */
.loading-bar {
    background-color: #e0e0e0;    /* Background color */
}
.loading-bar-progress {
    background-color: #76c7c0;    /* Progress bar color */
}
/* Adjust animation speed */
.loading-bar-progress {
    animation: load 2s infinite;    /* Change '2s' to desired duration */
}</code></pre>
    
    <h2>Browser Support</h2>
    <p>Works in all modern browsers:</p>
    <ul>
        <li>Chrome</li>
        <li>Firefox</li>
        <li>Safari</li>
        <li>Edge</li>
        <li>Opera</li>
    </ul>
    
    <h2>License</h2>
    <p>This project is open source and available under the MIT License.</p>
    
    <h2>Contributing</h2>
    <p>Contributions are welcome! Please feel free to submit a Pull Request.</p>
    
    <h2>Author</h2>
    <p>Shubham Saurabh</p>
</body>
</html>
