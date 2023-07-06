# Read: Class 11

This topic is important because audio and video as key aspects to any webpage.  It brings the page to life and allows th page to be accessible in different ways for different users.

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s. Video and audio were originally made possible with plugin-based technologies like Flash and Silverlight but both are now obselete due to security and accessibility issues in favor or native HTML solutions video and audio elements with the availability of JavaScript API.
2. Describe the use of the **src** and **controls** attributes in the **video** element? The **src** acts in the same was as the **img** element, the **src** attribute contains a path to the video you want to embed. **Controls** is used to control video and audio playback.
3. Why is it important to have fallback content inside **video** element? This is needed when the browser accessing the page doesn't support the **video** element allowing us to provide a fallback for older browsers.
4. Write a short story where **audio** and **video** are characters. The was once a singer name audio who was trying to tell her story and found a videographer name video to record her life.  Audio loved to sing cover songs and wanted to build her following up on social media so she had video record several videos to put on her page.  One of her cover videos was of Michael Jackson's "Butterflies".  This video end up going viral and she was noticed by a famous producer.

## A Complete Guide To Grid

1. How does Grid layout differ from Flex? Grid is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. Flex is a layout tool but its one directional flow has different use cases.
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms ina few sentences. Grid container is the direct parent of all the grid items. Grid item are the children of the grid container. Grid line is the dividing lines that make up the structure of the grid. Grid cell is the space between town adjacent rows and two adjacent column grids.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive? It helps with accessibility as the user may be visually impaired.
2. Define the following **img** attributes **srcset** and **sizes**. Write and example of how they are used. Img is used to display images in your HTML, srcset is used when you want to define the set of images we will allow the browser to choose between and what size each image is, sizes defines a set of media conditions and indicates what image size would be best to choose when certain media conditions are true.
3. How is srcset more helpful for responsive images than CSS or JavaScript? The browser starts to preload any image before the main parser has started to load and interpret the pages CSS and JavaScript.  That is useful in general for reducing page load times but it is not helpful for responsive images. 