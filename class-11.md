# Class 11 Reading Notes - Audio, Video, Images

## Things I want to know more about

## Video and Audio Content

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.
  - early on bandwith limited the use of video content and relegated it to Flash and Silverlight
  - HTML5 added <Video> and <audio> elements and new JS APIs for controlling them.  
- Describe the use of the src and controls attributes in the <video> element.
  - src (source) attribute contains path to the video you want to embed
  - controls attribute includes the browsers own control interface
- Why is it important to have fallback content inside the <video> element?
  - the paragraph inside the <video> element is displayed if the browser doesn's support it
  - you can put a link to the video file so the user can access it in some way if browser doesn't support it
- Write a very short story where <audio> and <video> are characters.
  - Video Bear invited his sister the Audio hedgehog on an adventure. They went to HTML land to explore the rich landscape of embedded media. They realized they had most of the same features in HTML land like `autoplay`, `loop`, `muted`, and `preload`. Audio Hedgehog realized she didn't have `width` and `height` attributes or a `poster` to display but she was just fine with that. She was a bit of an audiophile herself so she didn't have a use for those things. Video Bear and Audio Hedgehog fell down a rabbithole of codecs and fileformats and got entangled in a web of patent law that put limits on how far they could wander. They were able to complete their adventure in HTML land and made it safely back to BrowserVille just in time for dinner.

## A Complete Guide to Grid

- How does Grid layout differ from Flex?
  - Flex has a one-directional flow that can be limiting but Flex can still work well together with Grid
- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
  - Grid container - The element on which display: grid is applied. It’s the direct parent of all the grid items.
  - Grid item - The children (i.e. direct descendants) of the grid container.
  - Grid line - The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”)

## Responsive Images

- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  - To avoid unnecessarily large images meant for small screens, and to avoid too small images intended for big screens
- Define the following <img> attributes srcset and sizes. Write an example of how they are used.
  - srcset - defines the set of images we will allow the browser to choose between, and what size each image is.
  - sizes - defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true. 
  - the media condition describes a possible state the screen can be in like max-width:600px would be a screen 600ps wide or less
- How is srcset more helpful for responsive images than CSS or JavaScript?
  - HTML starts to download (preload) images before the browser loads and interprets CSS and JS so srcset is useful for reducing page load times. 
- `<picture>` element is a wrapper containing several `<source>` elements that provide different sources for the browser to choose from.
