Step-by-step example of simple JS backend and frontend with explanations
To properly view Markdown documents (*.md, like this one) in the VSCode you should press CTRL + SHIFT + V.

This manual consists of several sections. Each section is stored in a separate folder in its final state along with detailed manual describing how it was done in readme.md.

Every next section is based on the results of the previous section.

Contents are:

Simple frontend and backend
HTML and Stylesheet
Express HTTP service
NPM package's entry point and dependencies
Run and debug Node.JS service in the VSCode
Unit tests with Mocha and Chai
Creating a Node.JS module
Using our Node.JS module
Unit testing by Mocha and Chai
Debug Mocha tests in the VSCode
Browserify modules
Create a frontend code
Build the frontend code with Browserify and Watchify
Debug the frontend code in the browser
Dynamic pages and Socket.IO
Dynamic page
Communication between the frontend and the backend
Initial setup
Perform these steps to make initial setup of your work environment:

Install the VSCode
Install the Node.js, it comes with the NPM package manager
Open section's folder in the VSCode
Run code in folders
If you simply want to run the existing code do the following after the initial setup:

Open section's folder in the VSCode
Open View -> Integrated Terminal and run npm install command to install all required dependencies
Open View -> Debug, choose Launch in combobox and press F5 to run backend service
Open http://localhost:5000/ page to see client side (also http://localhost:5000/about in section 4)
