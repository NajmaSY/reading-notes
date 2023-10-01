# Audio, Video, Images

## Video and Audio Content

### Explain how the ability to use video and audio on the web has evolved since the early 2000s.

video> and audio> tags
e.g. video> scr="" controls -> like img
or add link to video
add captions and subtitles

- there used to be security and accessibility issues

### Describe the use of the src and controls attributes in the video> element.

- src -> source contains a path to the video you want to embed
- controls -> users to control video/audio playback - start/stop/adjust volume

### Why is it important to have fallback content inside the video> element?

e.g. use a p tag - if browser accessing the page does not support the video element, e.g. include a link/alternative access to video

## Grid - CSS

display: grid; - define container parent element
grid-template-columns/rows - set column/row sizes - child element
grid column/row - child elements into here

### How does Grid layout differ from Flex?

- source order of grid items doesnt matter
-

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

grid container - parent of all grid items
grid item - children of grid container
grid line - dividing lines of a grid - column/row

## Responsive Images

### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- images that work well on devices with widely differing screen sizes, resolution
- can display a cropped version of image with all the important details on a narrower screen - art direction problem
- no need to use a large image if its being viewed on a mobile - wastes bandwidth when downloaded
- pixelated when aimed at mobile users over desktop - called raster image
- The browser could then determine the optimal resolution to load based on the screen size of the user's device. This is called the resolution switching problem.

### Define the following img> attributes srcset and sizes. Write an example of how they are used.

srcset - defines the set of images we will allow the browser to choose between, and what size each image is, each set of image info is separated from the previous on by a comma
sizes - defines a set of media conditions e.g screen widths and indicates what img size would be bes to choose

- Look at its device width.
- Work out which media condition in the sizes list is the first one to be true.
- Look at the slot size given to that media query.
- Load the image referenced in the srcset list that has the same size as the slot or, if there isn't one, the first image that is bigger than the chosen slot size.

### How is srcset more helpful for responsive images than CSS or JavaScript?

- you cant load an img element, then detect the viewport width with JS, then change the source img to a smaller one
- the original img would already ahve been loaded, and you would load the smaller img as well

## Other Embedding Technologies - third party content

- iframe> - for embedding other web pages
- embed> + object> -> embed external resources such as PDF files

- Youtube - video/share/embed - iframe> code copy -> insert into input
- Google Maps - click on Hamburger Menu ||| -> share/embed map - copy iframe code - input
