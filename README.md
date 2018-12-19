# Web-Components-Notes

### What are web components?
* When we build web components, there are 3 fundamental building blocks. (HTML, CSS, Javascript)
* Web components brings all these 3 technologies together to build truly encapsulated, self-containing components for the web.
* Some of the popular web components frameworks are 
  * Polymer
  * SkateJS
  * x-tag
* These components not only built on top of web-components, they also provide additional capabilities. For example, Polymer provides data-binding capabilities.
* But using 3rd party libraries, we will lose interoperability and portability.
* Web components does not rely on 3rd party libraries and only relies on Web standards. This means that web components are more portable and reusable.
* One of the other important features of web-component is the ability to create a **Sub DOM tree** exclusively for a single web component.
* This **Sub DOM Tree** does not inherit styles from other components and the component styling does not leak to the other outside components.
* Therefore the major advantages of web components are
  * Style Encapsulation
  * Fewer dependencies and pre-requisites
  * Framework / Library Agnostic
  * Longer Life components
  
* Web Component Specification consist of 4 major areas
  * Custom Elements
  * Shadow DOM
  * HTML Templates
  * HTML Imports
