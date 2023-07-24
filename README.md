# AngularCLIDemo

Practice Questions:

1. What is the basic building block of an AAngular application?

Answer:     
    Components are the fundamental building blocks of an Angular application.

2. How do we group components of similar functionality?

Answer:
    Components of an Angular application can be logically organized as a tree. Angular modules are used to group Angular components that share similar functionality. 

3. Who is responsible for handling business logic tasks in an Angular application?

Andrew: 
    Angular components should only be responsible for handling the presentational logic and delegating business logic tasks to service. 

4. Which Angular CLI command can we use to create a new Angular application?

Answer:
    The cli common to create a new Angular project is "ng new  my-angular" the my-angular represents the name of the project that will be displayed in the project manager. 

5. Which Angular CLI command can we use to serve an Angular application?

Answer:
    The cli command to serve an Angular application is "ng serve" This builds the Angular application and starts a built-in web server that we can use to preview it. 

6. How do we declare an Angular component in HTML?

Answer:
    selector: A unigue name that is used to identify and declare the component inside HTML content. 

7. How do we declare Angular components in a module?

Answer:
    To declare an Anglar component in a module, you need to follow these steps:
        1. Import the component class into the module.
        2. Declare the component in the declarations array of the module.

        import { NgModule } from '@angular/core';
        import { BrowserModule } from '@angular/platform-browser';
        import { AppComponent } from './app.component';

        @NgModule({
        declarations: [
            AppComponent
        ],
        imports: [
            BrowserModule
        ],
        providers: [],
        bootstrap: [AppComponent]
        })
        export class AppModule { }


8. What syntax do we use for text binding on HTML templates?

Answer:
    To bind text dynamically in an HTML template in Angular, you can use interpolation syntax, which is denoted by double curly braces {{}}

9. What is the benefit of using the Nx Console?

Answer:
    The Nx console is a command-line interface(CLI) tool that provides several benefits for developers working with Angular and other modern web frameworks:
        1. Faster development
        2. Improved code quality
        3. Better collaboration
        4.Simplified deployement

10. Which extension do we use to perform static analysis in our Angular code?


