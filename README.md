# 3 main building blocks

## Custom Elements

### Create custom HTML tags

### Create custom class

### Lifecycle methods available

- construct - when an instance is created or upgraded
- connectedCallback - every time when the element is inserted into the DOM
- disconnectedCallback - every time the element is removed from the DOM
- attributeChangedCallback(attributeName, oldValue, newValue) - when an attribute is added, removed, updated or replaced

## Shadow DOM

- self contained components
- encapsulate styles and markup
- create with element.attachShadow({mode: open})
- creates a "shadowRoot" that we can reference and interact with

## HTML Templates

- define encapsulated markup of our web component
- template tag stores markup on page
- include both HTML and CSS in template
- use slots to add custom text
