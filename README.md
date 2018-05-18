# LighthouseTesting

App was created following this tutorial https://angular.io/tutorial/toh-pt0

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.3.

The intention is to show how [GOOGLE LIGHTHOUSE](https://developers.google.com/web/tools/lighthouse/) can generate audits based on:
1. Performance
1. Progressive Web App
1. Accesibility
1. Best Practices
1. SEO
1. Custom audits

## To use the project

Make sure you `npm install` then run the server with `ng serve`.

## Creating custom audits on lighthouse

Under the lighthouse-test register your custom configuration according to this url [https://github.com/GoogleChrome/lighthouse/tree/master/docs/recipes/custom-audit](https://github.com/GoogleChrome/lighthouse/tree/master/docs/recipes/custom-audit)

## Running lighthouse

Run `npm run test-lighthouse` and an html report will be generated and opened on your browser. Take a look at the package.json file to see the command that is being run to execute the audit. Notice that a sleep command was used to wait for the server to be up first and then the tests to be run. If the server is already up remove the npm start and sleep commands.

## Development server

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


## NEXT STEPS
1. Polish the commands to run lighthouse.
1. Personalize the audits, right now the example audit is showing.
