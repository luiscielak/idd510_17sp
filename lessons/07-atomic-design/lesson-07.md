# Lesson 07 - Atomic Design

> We’re not designing pages, we’re designing systems of components. 
> —Stephen Hay


## Topics covered

* Atomic Design (Atoms, Molecules, Organism, Templates, Pages)
* Pattern Library ([Pattern Lab][2])

### Atomic Design

![Atomic Design](img/atomic-design.png)
[Source][1]


**Atoms**
Atoms are the most abstract elements. These are the _raw materials_.
Example: colors, typefaces and HTML tags such as buttons, forms, images, text.
![Atoms](img/atoms.jpg)


**Molecules**
Molecules are atoms combined to serve a specific purpose. These are the basic building blocks.
Example: form-fields, labels, lists, sections.
![Atoms](img/molecule.jpg)


**Organisms**
Organisms are molecules combined. These are reusable interface components. 
Example: a header nav that includes a logo, links, a button, and a search bar.
![Organisms](img/organism.jpg)


**Templates**
Templates are formed by combining multiple organisms together. These are the wireframes that convey a structure.
Example: a wireframe of a log-in screen, sign-up form, or checkout page.
![Templates](img/template.jpg)


**Pages**
Pages are the final result. These are high-fidelity mockups of the templates.
![Pages](img/page.jpg)


### Pattern Library

A pattern library is a collection of user interface design patterns. It serves as a reference and a set of reusable code that scales and adheres to the design guidelines of the system.


## Resources
* [Brad Frost - Atomic Design][1]
* [Pattern Lab][2]
* [Design to Code with Atomic Design Principles][3]



[1]: http://bradfrost.com/blog/post/atomic-web-design/
[2]: http://demo.patternlab.io/
[3]: https://medium.com/re-write/the-unicorn-workflow-design-to-code-with-atomic-design-principles-and-sketch-8b0fe7d05a37