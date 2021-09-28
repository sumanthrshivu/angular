# Data Binding in Angular
Data Binding is the mechanism that binds the applications UI or User Interface to the models. <br>
Using Data Binding, the user will be able to manipulate the elements present on the website using the browser. <br>
Therefore, whenever some variable has been changed, that particular change must be reflected in the Document Object Model or the DOM.

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
Interpolation binding is used to return HTML output from TypeScript code i.e. from the components to the views. <br>
Here, the template expression is specified within double curly braces. Through Interpolation, strings can be added into the text that is present <br>
between HTML element tags and within attribute assignments. These strings are calculated using Template expressions. <br>

### - Property Binding
In Property binding, value flows from a component’s property into the target elements property. Therefore, Property binding can’t be used to <br>
read or pull data from the target elements or to call a method that belongs to the target element. The events raised by the element can be <br>
acknowledged through event binding which will be covered later on in this article. <br>

### - Event binding
The Event binding feature lets you listen to certain events such as mouse movements, keystrokes, clicks, etc. <br>
In Angular, event binding can be achieved by specifying the target event name within regular brackets on the left of an equal to ( = ) sign, <br>
and the template statement on the right side within quotes (” “). <br>

## 2) Two-way data binding <br>
- Two-way data binding, on the other hand, allows synchronization of data in such a way that the views can be updated using the models  <br>
   and the models can be updated using views. This means that your application will be able to share information between a component class
   and its template. <br>
- Angular allows two-way data binding that will allow your application to share data in two directions i.e. from the components to the templates
  and vice versa.This makes sure that the models and the views present in your application are always synchronized. Two-way data binding will perform
  two things i.e. setting of the element property and listening to the element change events. <br>

The syntax of two way binding is – [( )}. As you can see, it is a combination of the property binding syntax i.e. [ ] 
and the event binding syntax ( ). 






