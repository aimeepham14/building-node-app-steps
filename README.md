# NPM Project Steps

## Create a Project From Scratch
### Setting Up The JavaScript
* Mkdir and CD into a new project directory
* Run ``` npm init ``` to create a  ``` package.json ``` or use ``` npm init -y ``` to answer yes to all prompts
* Install needed packages with ``` npm install < package names > ```
* touch ``` index.js ``` (or other main entry point file)

### Setting Up the Git Repo
* Run ``` git init ``` to create a new repo in the project directory
* Create a ``` .gitignore ``` file and add ``` node_modules ``` to it. Be slick with ``` echo node_modules >> .gitignore ```
* Check to make sure node_modules folder is not being tracked with a ``` git status ```
* Add and commit your work

## Cloning a Project Down
* Clone the repo down to your local and cd into the new directory
* Run ``` npm install ``` or ``` npm i ``` to install the required packages from the package.json