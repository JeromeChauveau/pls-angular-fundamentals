# angular-fundamentals-files
This repo contains a few helper files for the Angular Fundamentals course at http://app.pluralsight.com/courses/angular-fundamentals

# General
- Typescript is transpiled to js
- AngularJS = version < 2.
Q: is static typing only for compilation, or does it also generate runtime errors?

Simplification:
`Class Cat {
  private name: string;
  constructor (name) {
    this.name = name;
  }
 }`
 can be simplified into : 
 `Class Cat {
  constructor (private name:string) {
  }
 }`


## Modules 
 - Components can be grouped in modules. 
 - Only files of targeted modules are loaded.
 - Objects from modules are only available in the module where they are registered.

Q : diff between `npm start` & `ng serve`?

## bootstrap
In angular.js, pointeur vers main.ts ("main": "src/main.ts").
In main.ts : 
`platformBrowserDynamic().bootstrapModule(AppModule)` --> shows that application is bootstrap with AppModule.

