# EasyTasks Angular App

### Tech Stack:

Angular, HTML, CSS, Typescript

### Concepts:

- Signals (supported since angular 16)
  A signal is an object that stores any value, when this value is changed angular is able to update that part that needs to be updated, like useState hooks in reactjs
- Directives are used to enhance elements. (useful for two way binding)
  Example: “ngModel” used in input tag for extracting user input values.
  “\*ngFor” directive is used in old angularjs version
  [We have to import FormsModule to use Directives]
- String Interpolation
- Property Binding
  bind element properties to dynamic values.
  For example, <img [src]="someSrc"> binds the src property of the underlying HTMLImageElement DOM object to the value stored in someSrc.
