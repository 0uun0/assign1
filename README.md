# CS 253 Assignment 1 – Journey to the Dark Side 🌘

Assignment instructions: 
We're doing client-side attacks! This assignment is all about Cross Site Scripting (XSS) vulnerabilities. Your goal is to come up with "attack inputs" that when entered into vulnerable websites allow you to execute code in the target's browser.

With Reflected XSS, you want to find a way to encode the attack input into a URL that can be sent to a target. When the URL is visited, your attack input is extracted from the URL by the server-side (or potentially client-side) code and executed in the target's browser.

With Stored XSS, you want to find a way to get your attack input stored more permanently, e.g. in the server's database, so that when your target visits a page constructed using this data at some point in the future, your attack code will execute in their browser.

The assignment takes the form of an interactive workshop that you'll run in your browser. This is what it looks like:
![assignment 1 screenshot](https://web.stanford.edu/class/cs253/journey-to-the-dark-side.png)


Prepare
Check your Node.js version
You should already have Node.js installed from the last assignment. For this assignment, it's highly recommended to use Node.js 16. Open your terminal and run this command to confirm you're running some version 16.x.x:

node --version
If not, you can install Node.js from the official site.

Get the starter code
Run this command to clone the code with git:

git clone https://github.com/stanford-web-security/assign1.git
Enter the folder you just created:

cd assign1
Install the necessary local dependencies with npm:

npm install
Start the assignment
Run the local server:

npm start
Your browser should open up to http://localhost:4000 where you can begin the assignment.
