# Class 5 Reading notes

## What is CSS

- Cascading Style Sheets
- Control how HTML elements look in your browser
- A browser is sometimes called a "user agent"
- rule-based language - change rules by specifying groups of styles that apply to particular selments or groups of elements
- CSS is broken down into modules
- All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs"), which are published by standards organizations (such as the W3C, WHATWG, ECMA, or Khronos) and define precisely how those technologies are supposed to behave.
- CSS is developed by a group within the W3C called the CSS Working Group

----

## How to add CSS

### Three ways to insert CSS

- External CSS
  - External style sheet fule that is referenced by each page and placed in the `<link>` element in the `<head>` section of an HTML page
  - external file must have a .css extension and should not contain any HTML tags
- Internal CSS
  - May be used if one single HTML page has a unique style
  - internal style is defined inside the `<style>` element inside the `<head>`head section
- Inline CSS
  - Apply to a unique style for a single element
  - add the style attribute to the relevant element.
  - Can contain any CSS property

### Multiple Style Sheets

- If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.
- ex. if an internal style is defined after the link to external style sheet it will take priority. If the internal style is before the external style sheet the external or latest style sheet will be used
- Q?: is this why external style sheet are in the head and above internal styling?

### Cascading Order

- All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:
  1. Inline style (inside an HTML element)
  2. External and internal style sheets (in the head section)
  3. Browser default

----

## CSS Color

- `color` property specifies the color of text
- `body {
  color: red;}
- h1 {
  color: #00ff00;}
- p.ex {
  color: rgb(0,0,255);}
- Tip: Use a background color combined with a text color that makes the text easy to read.