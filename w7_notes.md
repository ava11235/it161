
## Reading

In addition to styling elements, CSS is used for creating page layouts. 
There are several techniques to choose from when creating page layouts, such as floating elements, flexbox or grid layouts.
In addition, HTLM 5 provides elements that are used specifically for creating page layouts, such as header, footer, nav, aside, section and article.
These elements provide clearer code compared with multiple <div> elements used as containers. 
  
Responsive web design is used so that pages look good on differently sized devices, from a phone all the way up to a desktop.
There are 3 components to Responsive design:
1. Use Fluid layout to adjust the width of a page and its elements to the size of the screen.
2. Use media querrie to adjust appearance of the web page to different device sizes.
3. Use scalable images so that the size of the image can be scaled to the size of the element that contains it.

Formula for converting pixels to percents:

target divided by contnext times 100 = result
e.g. 930px div 960px (body) times 100 = 96.875%.

When working with responsive layoutws, you must set the meta element's viewport properties. 
e.g. 
```
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Media query is a CSS technique. The @media rule is used  to include a block of CSS properties only if a certain condition is true.
For example, you can use a media query to check the width of the viewport is 767 pixels or less.
```
@media only screen and (max-width: 767px) { img { width:100%; }}
    
```

zyBooks Ch 5 5.1-5.4

## Reference
[W3Schools HTML Layout elements and techniques](https://www.w3schools.com/html/html_layout.asp)

[W3Schools Responsive design media querries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)

## Practice

zyBooks Ch 5.1- 5.4 Practice (graded participation activity)
zyBooks Code lab 5.9

## Learning Outcomes
Fixed vs. Fluid layout

Page layout with Flexbox

Page layout with Grid layout

Positioning elements

Responsive layout

Special effects


## Fixed vs. fluid width layout 
[here](https://github.com/ava11235/it161/blob/master/images/layouts.JPG)

## Responsive example
[here](https://stanimeredith.dreamhosters.com/responsive/index.html)


