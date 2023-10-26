### Explain how the ability to use video and audio on the web has evolved since the early 2000s.

The first online videos and audio were made possible by plugins like Flash and silverlight, Now, they are obsolete in favour of HTML.

### Describe the use of the src and controls attributes in the <video> element.

`<video>` - allows for the video to be embedded onto the page.
`<audio>` embeds a sound player onto the page.

### Why is it important to have fallback content inside the <video> element?

Fallback content is what is displayed on the page if the browser doesn’t support the video element. This can sometimes be a direct link to the video so the user can access it if something goes wrong.

### How does Grid layout differ from Flex?

Grid was made to specifically target the ways in which Flexbox’s use wavers. They can be used together. Grid is a way of creating a grid layout, and defining the element’s size within the grid.

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid container: this is the direct parent of all of the other grid items
- Grid item: the grid item is the direct descendant of the grid container.
- Grid line: this makes up the structure of the grid, like the lines in a grid. They reside on the rows and column parameters.

### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

1. User Experience - ensuring users can still access content on various devices and allows for a broader audience.
2. Bandwidth efficiency
3. Faster loading times
4. SEO benefits - search engines consider loading times a factor in search engine ranking
5. Accessibility
6. Cross-browser compatibility
7. Mobile-first approach - prioritising mobile users caters to the ever-growing mobile user base
8. Reduced maintenance

### Define the following <img> attributes srcset and sizes. Write an example of how they are used.

The attribute `srcset` allows the user to privde a list of sources along with a descriptor that indicates the image width, pixel density or media condition. The browser then selects the most appropriate sized image.

> img src="image-small.jpg”
> srcset="image-medium.jpg 1000w, image-large.jpg 2000w
> alt="Responsive Image"

Meanwhile, the attribute `sizes` tells the browser how the image will be displayed in the layout based on the viewport width.

> img src="image-small.jpg”
> srcset="image-medium.jpg 1000w, image-large.jpg 2000w”
> sizes="(max-width: 600px) 100vw, 50vw”
> alt="Responsive Image"

In summary, `srcset` helps the browser select the most suitable image source from a list based on the user's device and viewport size, while `sizes` instructs the browser on how the selected image should be displayed within the webpage's layout at different viewport sizes.

### How is srcset more helpful for responsive images than CSS or JavaScript?

`srcset` is more effective because it provides native browser support, enhances efficiency and performance by enabling the browser to select the right image variant before downloading, and reduces page weight, making it SEO and accessibility-friendly while simplifying implementation.
