---
title: Lazy Loading
subtitle: Lazy loading is a technique for optimizing web page
metaDescription: Lazy loading prevents images and videos that are off-screen from loading immediately.
metaKeywords: lazy loading, on-demand loading
lastEdited: 27/March/2023
---
# Lazy loading

Lazy loading (on-demand loading) is a technique for optimizing the loading of web content, particularly images and videos, by deferring their loading until they are needed.

When a page loads, lazy loading prevents images and videos that are off-screen or below the fold from loading immediately. Instead, they are only loaded when a user scrolls down and sees them or when they interact with the content that calls for them.

### Advantages of lazy loading:

- Faster page load times
- Reduced data usage
- Improved user experience
- Improved SEO
- Reduced server load


This strategy requires identifying resources as non-blocking (non-critical) which can be applied through multiple ways:

### Code splitting

JavaScript, HTML, and CSS can be broken down into smaller, more manageable chunks. When a user requests a page, only the minimum amount of code required to display the initial content is loaded. When a user interacts with the page, additional code may be loaded dynamically in the background to handle that interaction.

By using the script type module, you can optimize JavaScript because any script tag with type="module" is deferred by default.

CSS code is, by default, treated asa render blocking. It is possible to optimized CSS for rendering purpose by splitting into multiple files based on media queries. 


### Image /Frame

Lazy loading is implemented at the browser-level in modern browsers. This option can be easily enabled using the loading attribute in images and iframes.

```sh
<img src="image.jpg" alt="..." loading="lazy" />
<iframe src="video-player.html" title="..." loading="lazy"></iframe>
```
