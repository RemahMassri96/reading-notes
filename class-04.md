
# HTML Links, CSS Layout, JS Functions:

Links are created using the <a> element. Users can click on anything
between the opening <a> tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.
 - The <a> element uses the href attribute to indicate the page you are linking to.
 - If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
  -  You can create links to open email programs with an email address in the "to" field.
  -  You can use the id attribute to target elements within a page that can be linked to.
  
  - Block-level elements start on a new line
  Examples include: heading , paragraoh , un-ordered list , lists 
  
  - Inline elements flow in between surrounding text :
  examples include :images 
  
  ## Containing Elements:
  
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.
### Controlling the Position of Elements:
  CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative   positioning, and absolutepositioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
  1. `Normal flow` : Every block-level element appears on a new line, causing each item to appear lower down
the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-by-side, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
  2. `Relative Positioning` : This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in
in normal flow.
  3. `Absolute positioning` :This positions the element in relation to its containing element
  
  
  #### The display property :
  The display property is the most important CSS property for controlling layout.
  `Display: none` : is commonly used with JavaScript to hide and show elements without deleting and recreating them.
  
  Override The Default Display Value
   every element has a default display value. However, you can override this.
   **display:none or visibility:hidden** 
   - `display :none` : hiding the elements , The element will be hidden, and the page will be displayed as if the element is        not there:
` - `visibility:hidden` : hides an element. the element will still take up the same space as before. The element will be          hidden, but still affect the layout:

