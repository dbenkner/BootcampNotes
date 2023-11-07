Angular/Typescript
Know the purpose and use of the app.module.ts and app-routing.module.ts
App Moudle is a list of every component and pipe of the app. App routing moudle to define the route/url of the component you want to display.
Know what is required to add components to the app.module.ts
Add the class name to the delcrations key and to import it 

Know the proper way to generate components, the syntax and how they use services
ng g c componentname they use services by importing the service and injecting an instance of the service into the component in the constructor permater list.
Know the unique features of services and why they are used to make the calls to the back-end.
Services can be shared across components. 

Know the decorator names of the component, service, and pipe
component, injectable, pipe

Know the directives *ngIf, *ngFor, *ngSwitch, one-way binding and two-way binding and how to use each one
oneWay {{double braces}}
*ngFor="let line of lines";
[(ngModel)]="property"
*ngIf=property


Know the purpose and the use of pipes changing the display of data, search, sorting

Know how to define an route in the app-routing.module.ts {path:'route', component:classNameCompoenent}

Know the main purpose of the constructor in components.
To inject services
Know how a component gets access to a service.
By importing them and injecting them into the constructor parameter list
Know the syntax and differences between one-way and two-way binding.
{{oneway}}
[(NgModel)]="property"