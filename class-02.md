
# Reading Notes ( class 02 ):
 - HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).
 - They also provide semantic information (e.g. where emphasis should be placed, the definition of any
      acronyms used, when given text is a quotation).   
 - CSS allows you to create rules that specify how the content of an element should appear
 
 ## The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
 - Block level elements look like they start on a new line.
 - Inline elements flow within the text and do not start on a new line
 
 ### CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
 - Selectors indicate which element the rule applies to. 
 - The same rule can apply to more than one element if you separate the element names with commas.
 - Declarations indicate how the elements referred to in the selector should be styled
 - CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon.        You can specify several properties in one declaration, each separated by a semi-colon.
 
 - The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page
   It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element.
It should use three attributes:
  1. **href** :
  This specifies the path to the CSS file.
  2. **type** :
  This attribute specifies the type of document being linked to. The value should be text/css .
  3. **rel** :
  This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when
   linking to a CSS file.
  - CSS selectors are case sensitive, so they must match element names and attribute values exactly.
  #### Types Of Selectors // 
  `Universal Selector` : Applies to all elements in the document.
  `Type Selector` : Matches element names.
  `Class Selector` : Matches an element whose class attribute has a value that matches the one specified after the period (or      full stop) symbol
  `ID Selector` : Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol
  `Child Selector` : Matches an element that is a direct child of another
  `Descendant Selector` : Matches an element that is a descendent of another specified element (not just a direct child of
  that element)
  `Adjacent Sibling Selector` : Matches an element that is the next sibling of another
  ` General Sibling Selector` : Matches an element that is a sibling of another, although it does not have to be the directly
   preceding element
  ##### The ABC Of Programming :
  - It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and
     CSS style sheets), but they have the . j s extension.
  - The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like
       the <link> element can be used to load a CSS file).
  
  A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.
Statements should end with a semicolon.
 **JAVASCRIPT IS CASE SENSITIVE**
 
- You should write comments to explain what your code does. They help make your code easier to read and understand.
This can help you and others who read your code.
- A script w ill have to temporarily store the bits of info rmation it needs to do its job. It can store t his
data in variables.
**JAVASCRIPT DATA TYPE** 
1. NUMERIC DATA TYPE
2. STRING DATA TYPE
3. BOOLEAN DATA TYPE

**ARRAYS** 
An array is a special type of variable. It doesn't just store one value; it stores a list of values.
- Conditional statements allow your code to make decisions about what to do next.
- Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.
- Logical operators allow you to combine more than one set of comparison operators.
- if ... else statements allow you to run one set of code if a condition is true, and another if it is false.
- switch statements allow you to compare a value against possible outcomes (and also provides a default
option if none match).
