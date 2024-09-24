# Getting Started with HTML & JavaScript in Visual Studio Code

This guide will walk you through the process of setting up HTML and JavaScript in Visual Studio Code (VS Code). You'll learn how to install and configure **Live Server** to run your code and get started with basic JavaScript.

## Prerequisites

Before starting, make sure you have the following installed:

- [Visual Studio Code](https://code.visualstudio.com/) (VS Code)
- A web browser (Google Chrome, Mozilla Firefox, etc.)

## 1. Install Visual Studio Code

If you haven't installed VS Code yet, follow the instructions [here](https://code.visualstudio.com/Download) to download and install it on your system.

## 2. Install the Live Server Extension

The **Live Server** extension in VS Code allows you to run your HTML and JavaScript files in a local development environment and auto-refresh the browser when you make changes.

### Steps:
1. Open VS Code.
2. Click on the **Extensions** icon on the left sidebar, or press `Ctrl + Shift + X`.
3. In the search box, type `Live Server`.
4. Select **Live Server** by **Ritwick Dey** and click **Install**.

## 3. Create a New Project Folder

Now, let's create a folder for your HTML and JavaScript project:

1. Open VS Code.
2. Click on **File > Open Folder...** and choose a directory where you'd like to store your project.
3. Inside the folder, create a new file called `index.html`:
   - Right-click in the Explorer sidebar and choose **New File**.
   - Name the file `index.html`.

## 4. Create Your First HTML File

Here is a simple HTML file you can use to get started:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First HTML & JS Page</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is my first HTML page with JavaScript!</p>

    <!-- Add your JavaScript file here -->
    <script src="app.js"></script>
</body>
</html>
```

## 5. Create a JavaScript File

You’ll also need to add a JavaScript file (`app.js`) to your project folder.

1. In the same folder as your `index.html` file, right-click and select **New File**.
2. Name the file `app.js`.

Here’s an example of a simple JavaScript code you can add to `app.js`:

```javascript
// app.js
console.log("Hello from JavaScript!");
alert("Welcome to your first JavaScript page!");
```

This code will print a message to the browser console and show a pop-up when you load the page.

## 6. Open HTML File with Live Server

Now, you’re ready to run your code using Live Server.

### Steps:
1. Right-click on the `index.html` file.
2. Select **Open with Live Server**.
3. Your browser will automatically open the HTML file, and you should see "Hello, World!" on the page.
4. Open the browser's **Developer Tools** (`F12` or `Ctrl + Shift + I`) to view the JavaScript message in the console.

Alternatively, you can click **Go Live** in the bottom-right corner of VS Code to start Live Server.

## 7. Make Changes & See Live Updates

Whenever you make changes to your HTML or JavaScript files, just save them, and Live Server will automatically refresh your browser to display the updates.

### Example:
- Modify the text inside `<h1>Hello, World!</h1>` to something else.
- Add another `console.log()` in `app.js`.

Save the files and watch the changes instantly in your browser.

## 8. Additional Resources

Here are some additional resources to help you learn HTML and JavaScript:

- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs: JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [VS Code Documentation](https://code.visualstudio.com/docs)

