## Chattrbox

<p> Web application that allows users to chat in real time.
This application is written in Javascript and uses WebSockets and Node.js as a custom back-end </p>

## Installation and Execution
### Prerequisites

* Node.js
    <p> For latest version download from https://nodejs.org/en/download/ </p>

* Atom text editor (Any Editor)
    <p> Install at > https://atom.io/ </p>

* Atom Plug-ins (Optional)
   <p> Open Atom and navigate to its Settings screen. On a Mac, this is done by choosing Atom → Preferences... On Windows, you can access it via File → Settings or using the keyboard shortcut Ctrl-. On the lefthand side of the Settings   screen, click + Install. Install emmet,atom-beautify, autocomplete-paths, api-docs, linter, linter-csslint, linter-htmlhint and linter-eslint. </p>

* Google Chrome Browser
    <p> For latest version > www.google.com/chrome/browser/desktop </p>

* Install `npm` Packages:
<p> Open your terminal and enter the following command </p>

    > npm install -g json-server
    > npm install -g browser-sync
    > npm install --save-dev nodemon
    > npm install --save ws
    > npm install -g wscat
    > npm install -g babel-cli
    > npm install --save-dev babel-core
    > npm install --save-dev babel-preset-es2015
    > npm install --save-dev browserify babelify watchify

### Running the application:
**Navigate to Project folder in the terminal-**

	> cd Chattrbox
**Type in the following command- to have npm create package.json**

	> npm init
**Open another terminal and use following commands**

	> cd Chattrbox
	> npm start

**Web server will be up and running on your local machine at -**

	> http://localhost:3000
