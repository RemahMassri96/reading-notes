
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
   - `display :none` : hiding the elements , The element will be hidden, and the page will be displayed as if the element is        not there
` - `visability:hidden;` : hides an element. the element will still take up the same space as before. The element will be          hidden, but still affect the layout

    ####The position Property:
    The position property specifies the type of positioning method used for an element (static, relative, fixed, absolute or sticky).
   
- position: static;
HTML elements are positioned static by default. 
Static positioned elements are not affected by the top, bottom, left, and right properties.
An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page

- position: relative;
An element with position: relative; is positioned relative to its normal position.

- position: fixed;
An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.

- position: absolute;
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

- position: sticky;
An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed)

**Overlapping Elements** :
When elements are positioned, they can overlap other elements.

The z-index property specifies the stack order of an element (which element should be placed in front of, or behind, the others).

**Screen Sizes**:
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
- Grids help create professional and flexible designs.
**FUNCTI ON** :
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than rep eating the same set of st atements).
**Declering a Function**
![Declare function](data:image/png;base64,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)
