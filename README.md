# AngularRevisingMaterials
In this repo, I will be revise the basics of the Angular Framework.

Why Angular,
<br>Angular is a single page application with a mvc (model-view-controller) architecutre.
<br>Angular is a framework that is using typescript.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Revised Materials:

<br>#Components:<br>Components are building blocks of the application's UI. <br>Components consists of 3 files, .html, .ts, spec.ts and optional .css file for styling.

<br>#Services:<br>In angular, a service is a class that contains bussiness logic, data retrival or shared functionality, <br>that can be used across multiple components.

<br>#Directive:<br>Directive is a feature that is allowing us to extend behaviour of the HTML elements while executing during rendering phase.

<br>#Pipes:<br> A Pipe in angular is way to transform data in templates.<br>Pipes are use to Format, Filter or Manipiluate data before displaying to user, without changing the original data.

<br>#Guard:<br>In angular, a guard is a type of service used to controll navigation, and access to routes.<br>Guards determine whether a route can be activated, deactivated, loadded or if data can be resolved before navigaiton.

<br>#Data Binding / Event Handlers:<br>It i a mechanism that allow applicaiton to respond to user interactions. Such as, cliks, key presses or mouse movements. Basically, it connects HTML template to a method in component, enabling the applicaiton execute logic when an event occurs.

<br>#Property Binding:

<br>#Two-Way Data Binding:

<br>#HTTP Module/Forms Module:

<br>#Routing:<br>Routing in angular allow us to create a single page applicaiton (SPA) by navigating between different views or components without reloading the entire page.<br>It manages the navigation and rendering of components based on the URL path.

<br>#State Management:<br>State management includes controlling and synchronizing the state(data) of the application acrooss components, services and other parts of the app. We can use input-output technic for vasic state management, particullarly for managinibg data flow between paranet and child components.
<br>1)@Input(): Pass data from a parent component to child component.
<br>2)@Output(): Emits event from a child component to a parent component.

<br>#Standalone:<br>A standalone component is a self-contained unit that does not requeire being declared inside an anuglar module.<br>It can directly import dependencies such as, other components, directives, pipes or services without being part of a module.

<br>#Dependency Injection:<br>It is a design pattern that makes it easy to manage and share dependenceis like services or components across the applicaiton. Basically, instead of creating onbjects manually, angular's DI framework provides these objects(called dependencies), to the needed parts. 

<br>#Signals:<br>Signals provide a reactive way to manage state and track changeces efficiently. Unlike traditional RxJs Observables, Signals offer synchronous and automatic reactivity without manual subscriptions. Basically, without signals, abgular detects changes automatically and render everythibg from scratch. However, with signlas, we are telling it where the change happened. So, instead of rendering every single UI element, it will render only connected ones to change.

<br>#Hydration:<br>Hydration is the process of revising server-rendered HTML on the client side instead of re-rendering it from scracth. This is used in Server Side Rendering (SSR) to improve performance. We can activate/deactivate this proccess in any component.
