# Spacex-Launch

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.2.

# App Overview

- The app contains one main module - Dashboard
- We have three components under the dashboard module(filter, home, launch list), and filter component is wrapped in home component.
- Landing page will be Home Component `/home`.
- Filters are all configurable and kept as Constants.
- Api has been made in the parent level and data served to child component.
- The app is following server side rendering.
- For fetching the data, simple http method is used with required query parameters.
- Application has targeted both the desktop and mobile view.

## Development server
To run the application on local, you need to give command - `npm install` to install all the required dependencies.
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
