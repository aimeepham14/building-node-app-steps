# Building a New Node/NPM Project

## Setting up a Node Project
* Create a new folder for your project
* Initialize NPM inside the project folder with the command ``` npm init ```
* Make sure that the file ``` index.js ``` is created
* Run the file via the command line with the command ``` node index.js ```

## Creating Your Module
* Inside the folder created above, create a javascript file called ``` myModule.js ```
* Assign a key-value pair to ``` module.exports ```. For example:
``` module.exports.beBasic = () => console.log("That's so fetch!") ```
* To import your module in ``` index.js ``` write the following code in your ``` index.js ``` file:
```const myModule = require('./myModule.js') ```
* Utilize the module_name with the function or operation tied with it. For example:
``` myModule.beBasic(); ```
* Run ``` index.js ``` via the command line: ``` node index.js ```

## Node Packages
* To download a package and install it for a specific project, make sure you're inside the directory of the project you want to use the package in and in the command line type the code:
``` npm i [package name] ```
* To quit any program runnin in the terminal press CTRL+C
* Create a file called ``` .gitignore ``` to contain a list of files and folders that git should not be tracking

## Cloning and Setting Up a Repo That Uses Node Packages
* Fork and clone the repo with the command: ``` git clone [URL] ```
* Install the dependencies with the command ``` npi i ```
* Create a ``` .gitignore ``` file 