# Class 5 Reading Notes

## Things I want to know more about

- should we size images in the HTML or the CSS?
- when should we use ems instead of pixels for sizing?
- I'm curious about how standards have changed for things like image sizes and compression since this book was written. Are things different now because of the prevalence of high resolution (retina) screens?

## HTML Chapter 5: “Images” (pp.94-125)

- `<img>` -  self closing element doesn't need a closing tag
  - needs src(source) - usually relative URL to your images directory
  - needs alt="text description of the image"
- height and width can be defined here but more commonly in CSS
- save as .jpeg for images with lots of different colors (like photographs)
- save as .png for logos or images with fewer colors or large areas of the same color
- save images with transparent backgrounds as .png
- `<figure>` - the element to contain images
- `<figcaption>` element to add captions to images `</figcaption>`

## HTML Chapter 11: “Color” (pp.246-263)

- Color can be in RGB values, Hex codes, or 147 predefined color names
- colors can also have a HSL(A) value for Hue, Saturation%, Lightness% (and alpha - transparency)
- Background-color for the whole element box

## HTML Chapter 12: “Text” (pp.264-299)

- serif - has extra details on the ends of main strokes; sans-serif - straight lines without details; monospace - each letter is the same width (often used for code)
- font-family: - recommended not to use more than three typefaces on a page
- font-size: (browser default is 16px). can be pixels, percentages, or ems
- text-transform: uppercase or lowercase
- text-decoration;: underline, overline, line-through, blink
- text-align: left, right, center, justify
- text-shadow: (1px 1px 0px #000000) how far to left or right, how far up or down, amount of blur, color
- :link (set styles for links not yet visited and :visited (links that have been clicked on)
- also :hover and :active classes for styling links and :focus for elements 

## Blog Post - JPEG vs PNG vs GIF

- Use JPEG format for all images that contain a natural scene or photograph where variation in color and intensity is smooth
- Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos
- Use GIF format for images that contain animations
- JPEG can support 16mil colors, PNG8 (8bit can support 256 and PNG24 can do 16mil) IMO - go with PNG24 the file size difference is worth it.
