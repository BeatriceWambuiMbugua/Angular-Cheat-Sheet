# Angular-Cheat-Sheet
As a technical mentor, the angular cheat-sheet includes the things that are really necessary to understand in Angular

# Installation of Angular CLI (Command Line Interface)

`$ npm install -g @angular/cli`

###### Confirming the Installation

`$ ng`

###### To update your angular version

`$ ng update`

### Update Angular CLI version Globally

Steps To update Angular CLI version globally in your system.

* First uninstall the existing Angular cli packages.
* Then run `npm cache` verify command to clear the node packages cache.
* Then install latest Angular CLI version using `npm install -g @angular/cli@latest` command.
--------------------
* `npm uninstall -g angular-cli`
*  `npm cache clean or npm cache verify (if npm > 5)`
*  `npm install -g @angular/cli@latest`

### Creating Angular App

`$ ng new <app-name>`

### Running an Angular App

Cd into the directory and open it through your chosen editor: `$ code .`

In the terminal editor: 

`$ ng serve`

This command responds by compiling all the files and then starts the local development server with the following output:

` ** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **`

To see the actual app, let's open the URL `http://localhost:4200/` on the address bar of our web browser.

or 
 
 `$ ng serve -o` to open in a browser
 
 
