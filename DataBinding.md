# Data Binding in Angular
Data binding automatically keeps our page up-to-date based on our application's state. We use data binding to specify things such as the source of an image, the state of a button, or data for a particular user.<br>

### Types of Data Binding in Angular
1) One-way data binding
2) Two-way data binding <br>

### 1) One-way data binding <br>
One-way data binding is a simple type of data binding where you re allowed to manipulate the views through the models. <br>
This implies, making changes to the Typescript code will be reflected in the corresponding HTML. In Angular, One-way data binding is achieved through: <br>
- Interpolation or String Interpolation
- Property binding
- Event binding <br>

### - Interpolation Binding
Interpolation is used for one-way data binding in Angular. It embeds an expression into the HTML template. By default, expression should be surrounded by {{ and }}. This expression is also known as template expression.Angular evaluates an expression surrounded by {{ and }} and then converts a result to a string and assigns it to an element or directive property. <br>

### - Property Binding
Property binding in Angular helps you set values for properties of HTML elements or directives. Use property binding to do things such as set paths programmatically, and share values between components etc..<br>

### - Event binding
Event binding is used to handle the events raised by the user actions like button click, mouse movement, keystrokes, etc. When the DOM event happens at an element(e.g. click, keydown, keyup), it calls the specified method in the particular component. <br>

## 2) Two-way data binding <br>
- Two-way data binding refers to sharing data between a component class and its template. If you change data in one place, it will automatically reflate at the other end. For example, if you change the value of the input box, then it will also update the value of the attached property in a component class.<br>

- The ngModel directive with [()] syntax (also known as banana box syntax) syncs values from the UI to a property and vice-versa. So, whenever the user changes the value on UI, the corresponding property value will get automatically updated.<br>

- [()] = [] + () where [] binds attribute, and () binds an event.






