# Slider

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

## Overview

This project gives you a ready-to-integrate Angular component for an Angular Material Slider, mainly using the example code from the official Angular site. When originally researching sliders, I realized that there are more steps that you need to do after obtaining the mat-slider example code. This project has all of the module imports needed to get up and running quickly. The project also includes Hammer JS, Bootstrap and default Material themes.

## Deployment Steps

1. Inside your Angular CLI project run `ng g c slider` and copy the <b>slider.component.xxx</b> file content into your automatically generated files.

2. Copy the contents of <b>styles.css and app.module.ts</b> to your respective project files. Switch the pre-built Material Theme in the styles file if needed (all options are included in comments). The module file includes all Material imports needed for the component to work.

3. Add `import 'hammerjs/hammer';` to <b>polyfills.ts</b>. This allows the slider to animate as you drag the mouse along it and prevents any delay.

4. Add `<app-slider></app-slider>` inside of <b>app.component.html</b> or the HTML file of the parent component.

5. `ng serve`

If you encounter any issues, run `npm install --save hammerjs bootstrap @angular/material @angular/cdk` inside your project directory.

**To-do: See if [ng-packagr](https://medium.com/@nikolasleblanc/building-an-angular-4-component-library-with-the-angular-cli-and-ng-packagr-53b2ade0701e) can export this component as CLI library instead with Angular 6

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
