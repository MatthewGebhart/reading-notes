# Class 8 Reading Notes

## Things I want to know more about

## Learn CSS - Flexbox

- Flexbox is a layout mechanism designed for laying out groups of items in one dimension.
- Flexbox is designed for one-dimensional content. Explain what this means.
 - it can only control alignment in one axis like a row or column, not both together like a grid
- Explain the difference between the main axis and cross axis.
  - main axis is the main direction set usually right to left but can be changed, cross axis is the opposite direction from the main axis
- How can using certain properties of flexbox negatively impact accessibility?
  - if you reorder elements from right to left it only affects the way they are displayed and not how the HTML elements are arranged which is what screen readers are looking at so it can cause confusion
- If you are working on the main axis then the properties begin with `justify-`. On the cross axis they begin with `align-`.

## CSS Layout - Flexbox

- What are some advantages of using flexbox over float?
  - flexxbox makes it easier to center content inside its parent, and to make children take up an equal amount of space, or to make columns the same height with varying amounts of content
- How does this topic connect with your long term goals?
  - I often find that I am trying to center things, this will make that much easier while still remaining responsive for different screen sizes. Flex seems like a great took to have.