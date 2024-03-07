# TutorialAppl

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## MockServer 

JSON-server was installed for mocking a database: Heroes.

    1- Create a JSON file e.i: `db.jason` where a data will located in a json format.
    2- Run `npm install -g json-server` or  `npm install json-server --save-dev`
    3- Run `json-server -- watch folder/db.json` or where the file is located. Check the directory Path.

    If you are in the correct Path try:
        `npx json-server --watch db.json`

    See example:    

    https://moduscreate.com/blog/how-to-mock-data-in-angular-applications/

    4-Open `http://localhost:3000` (or the setted port) 

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
