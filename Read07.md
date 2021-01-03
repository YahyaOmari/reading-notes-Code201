# Chapter 6 -HTML-
## Tables

HTML tables allow web developers to arrange data into rows and columns.

### Define an HTML Table

- The "table" tag defines an HTML table.

- Each table row is defined with a "tr" tag. Each table header is defined with a "th" tag. Each table data/cell is defined with a "td" tag.

- By default, the text in "th" elements are bold and centered.

- By default, the text in "td" elements are regular and left-aligned.

> Note: The <td> elements are the data containers of the table. They can contain all sorts of HTML elements; text, images, lists, other tables, etc.

## JavaScript Object Methods

### The "this" Keyword

In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

## Chapter 3 -JS-
### Accessing Object Methods

You access an object method with the following syntax:

- "objectName.methodName() "

You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().

This example accesses the fullName() method of a person object:

Example
- name = person.fullName();

If you access the fullName property, without (), it will return the function definition:

Example
- name = person.fullName;