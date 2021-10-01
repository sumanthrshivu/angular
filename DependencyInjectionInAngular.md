

# Life Cycle Of Angular Components

* Every component has a life-cycle, a number of different stages it goes through from initializing to destroying. 

* There are 8 different stages in the component lifecycle. Every stage is called life cycle hook events.

* Since a component is a typescript class, for that reason every component must have a constructor method. The constructor of the component class executes first before the execution of any other life cycle hook event

* If we need to inject any dependencies into the component, then the constructor is the best place to inject that dependency. After executing the constructor, Angular executes its life cycle hook methods in a specific order.

  ### Stages of Life Cycle

  1. ngOnChanges

     This event executes every time when a value of an input control within the component has been             changed.

  2. ngOnInit
     This event initializes after angular first displays the data-bound properties or when the component has been initialized. This event basically is called only once just after the ngOnChanges() events. This event is mainly used for initializing data in a component.

  3. ngDoCheck
     This event is triggered every time when the input properties of a component are checked. We can use this hook method to implement the check with our own logic check. 

  4. ngAfterContentInit
     This lifecycle method is executed when Angular performs any content projection within the component views. This method executes only for the first time when all the bindings of the component need to be checked for the first time.

  5. ngAfterContentChecked
     This lifecycle hook method executes every time when the content of the component has been checked by the change detection mechanism of the Angular

  6. ngAfterViewInit
     This lifecycle hook method executes when the component’s view has been fully initialized. This method is initialized after Angular initializes the component’s view and child views.

  7. ngAfterViewChecked
     This method is just called after the ngAfterViewInit() method. It is executed every time the when the view of the given component has been checked by the change detection algorithm of Angular.

  8. ngOnDestroy
     This method will be executed just before Angular destroys the components. This method is very useful for unsubscribing the observables and detaching the event handlers to avoid memory leaks.

