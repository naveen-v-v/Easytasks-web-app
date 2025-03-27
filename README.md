# EasyTasks Web App

### Tech Stack:

Angular, HTML, CSS, Typescript

<hr>

### Website Output:

#### Home Screen

> <img src="https://github.com/naveen-v-v/Easytasks-web-app/blob/main/public/output_add_task.png?raw=true" alt="logo"/>

#### Add Task Pop-up

> <img src="https://github.com/naveen-v-v/Easytasks-web-app/blob/main/public/output_homescreen.png?raw=true" alt="logo"/>

### Concepts:

- Signals (supported since angular 16)
  A signal is an object that stores any value, when this value is changed angular is able to update that part that needs to be updated, like useState hooks in reactjs
- Directives are used to enhance elements. (useful for two way binding)
  Example: “ngModel” used in input tag for extracting user input values.
  “\*ngFor” directive is used in old angularjs version
  [We have to import FormsModule to use Directives]
- Pipes used to transform template data. Like date from DatePipe import, used to work with date values.
- String Interpolation
- Property Binding
  bind element properties to dynamic values.
  For example, <img [src]="someSrc"> binds the src property of the underlying HTMLImageElement DOM object to the value stored in someSrc.
- Services is a class that performs some operations that might be needed by one or more components.
- In conjunction with Services we use Dependency Injection, which is used to share an instance of a class. Without this different instances of a class will have different data, which inturn creates a problem of managing the data.
  [You tell which type of value you need and angular creates it and provides it as an argument]
