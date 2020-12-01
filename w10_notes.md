## Reading

zyBooks Ch 10.1 - 10.5

Today an increasing amount of web traffic takes place on mobile phones rather than traditional desktops.  This has led to the development of mobile friendly websites, 
designed specifically for smaller screen sizes and touchscreen devices. The most popular technique for creating mobile friendly websites is Responsive Web Design. 
Using this technique developers create one website that looks good on various screen resolutions.

The three components of responsive websites are:

- Fluid grids relying on relative rather than absolute units.
- Scalable media such as images.
- Media queries, which are used to change how a layout looks at certain breakpoints, such as, medium width or mobile phone layouts.

A helpful tool for testing your website with multiple screen resolutions is Google's DevTools screen emulator, which can be accessed
with Shift+Ctrl+I on Windows and Cmd+Option on Mac.

The viewport is the visible area of the screen. Using the viewport meta tag allows develops to specify properties needed for mobile web development 
such as the standard settings:

```
<meta name="viewport" content="width=device-width, initial-scale=1">
```

CSS3 Media Queries Media allows for checking the width and height of a device and its viewport as well as the device orientation. 
Thus, the web page can provide a customized look for desktops, tablets, mobile phones and other types of devices.
For example, this query will change the nav links to vertical instead of horizontal positions on devices smaller than 490 pixels.

```@media screen and (max-width: 490px) {
  nav a {
    float: none;
    width: 100%;
  } 
  ```

Responsive Images can scale for different sized devices. They should be able to both scale up on higher resolution devices, so they don't look pixelated, but 
also be of the minimum device pixel ratio (DPR) in order to use less of the network's bandwidth.


## Reference
[MDN's Guide to the building blocks of responsive design](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Responsive/responsive_design_building_blocks)
[Google's mobile friendly test](https://search.google.com/test/mobile-friendly)


## Practice

ZyBooks 10.1 - 10.5

## Learning Outcomes
Upon successful completion of the material students will be able to apply the following concepts and techniques to their work:
- Familiarity with the differences between mobile and desktop browsers

- Use of mobile development tools such as a screen emulator
- Working with the viewport, media queries and responsive images

