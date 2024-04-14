# <h1>CSS Cheat Sheet</h1>

# <h2> Selectors </h2>

- Universal Selector (`*`):

  - Selects all elements on the page.

- Type Selector (`elementName`):

  - Selects all elements of a specified type (e.g., `div`, `p`, `h1`).

- Class Selector (`.className`):

  - Selects all elements with a specific class attribute.
  - **Usage:** `.className { ... }`

- ID Selector (`#idName`):

  - Selects a single element with a specific id attribute.
  - **Usage:** `#idName { ... }`

- Attribute Selector (`[attribute=value]`):

  - Selects elements with a specific attribute and value.
  - **Usage:** `[attribute=value] { ... }`

- Descendant Selector (`ancestor descendant`):

  - Selects elements that are descendants of a specified ancestor.
  - **Usage:** `ancestor descendant { ... }`

- Child Selector (`parent > child`):

  - Selects elements that are direct children of a specified parent.
  - **Usage:** `parent > child { ... }`

- Adjacent Sibling Selector (`element + sibling`):

  - Selects an element that is immediately preceded by a specified sibling element.
  - **Usage:** `element + sibling { ... }`

- General Sibling Selector (`element ~ sibling`):

  - Selects sibling elements that follow a specified element.
  - **Usage:** `element ~ sibling { ... }`

- Pseudo-classes (`:pseudo-class`):

  - Selects elements based on their state or position in the document (e.g., `:hover`, `:active`, `:nth-child()`).

- Pseudo-elements (`::pseudo-element`):

# <h2>Properties and Values </h2>

- **Color and Text Properties:**

  - `color`: Specifies the text color.
  - `font-size`: Specifies the font size of text.
  - `font-family`: Specifies the font family for text.
  - `font-weight`: Specifies the weight (boldness) of text.
  - `text-align`: Specifies the alignment of text within its containing element.

- **Background Properties:**

  - `background-color`: Specifies the background color of an element.
  - `background-image`: Specifies the background image of an element.
  - `background-size`: Specifies the size of the background image.
  - `background-position`: Specifies the position of the background image.
  - `background-repeat`: Specifies how the background image should repeat.

- **Box Model Properties:**

  - `margin`: Specifies the margin of an element.
  - `padding`: Specifies the padding of an element.
  - `border`: Specifies the border of an element.
  - `width` and `height`: Specifies the width and height of an element.
  - `box-sizing`: Specifies how the total width and height of an element are calculated.

- **Layout Properties:**

  - `display`: Specifies the display behavior of an element.
  - `position`: Specifies the positioning method of an element.
  - `top`, `right`, `bottom`, `left`: Specifies the offset position of a positioned element.
  - `float`: Specifies whether an element should float to the left or right, or not at all.
  - `clear`: Specifies the behavior of an element concerning floating elements.

- **Flexbox Properties:**

  - `flex`: Specifies how a flex item will grow or shrink to fit the available space.
  - `justify-content`: Specifies the alignment of flex items along the main axis.
  - `align-items`: Specifies the alignment of flex items along the cross axis.
  - `align-self`: Specifies the alignment of a flex item along the cross axis.
  - `flex-direction`: Specifies the direction of the main axis in a flex container.

- **Grid Properties:**

  - `grid-template-columns` and `grid-template-rows`: Specifies the size of columns and rows in a grid container.
  - `grid-column` and `grid-row`: Specifies the start and end positions of a grid item along the column and row axis.
  - `grid-gap`: Specifies the gap between grid items in a grid container.

- **Miscellaneous Properties:**
  - `z-index`: Specifies the stacking order of positioned elements.
  - `opacity`: Specifies the transparency level of an element.
  - `cursor`: Specifies the type of cursor to be displayed when hovering over an element.
  - `transition`: Specifies the transition effects for CSS properties.
  - `object-fit`: Specifies how the contents of a replaced element should be resized to fit its container.
