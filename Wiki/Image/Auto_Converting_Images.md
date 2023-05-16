---
title: Auto-converting images
subtitle: Automaticaly convert images to a better optimized format
metaDescription: Many still don't know about the WEBP and AVIF image format and their benefits. Automatically converting images in CMS systems will make the internet more sustainable
metaKeywords: CMS Auto-converting images, auto converting images, WordPress auto-converting images, automatically converting images to webp, automatically converting images to avif
lastEdited: 16/May/2023
---

# Auto-converting images
On the internet, we have been using image formats such as JPG, PNG, and GIF for many years, but newer and modern formats with better compression have shown up, and now it is time to start using them.

When switching to modern image extensions such as [WEBP](https://developers.google.com/speed/webp) and [AVIF](https://en.wikipedia.org/wiki/AVIF) we get better compression and the images come out in much better quality. WEBP for example has a great compression that even in lossless quality gives you a reduction in file size of between 25%-34%. The AVIF format is even newer and it supports HDR pictures which means you can even convert images on your machine and store even more high-quality images using less space.

## The problem
The problem today is that approximately 52% of all the websites on the internet is using CMS systems. A large portion of these websites are administrated and owned by people with no experience in sustainable practices and many of them probably also don't know that data pollutes. Digital sustainability is relatively new which means even many professionals working in digital design still haven't heard about it.

CMS systems make it easy to add content to the internet, which also means that it is easy and fast to add big and heavy images and videos to the Internet. This comes with a price, and it is one of the reasons that the internet has become such a big polluter. But what can we do about it? We could educate every single website owner on the planet and force them to use sustainable practices, but I bet you are already thinking about how hard that would be. Another angle is to change the tools that people are using.

## Change from within
As mentioned; Forcing everyone to educate themselves on the environment and use sustainable practices is difficult. But another way is to make the change from within. Since 52% of the websites on the internet are using CMS systems, then we can start by changing the tools that they are using.

Every single image that is uploaded to the website's file system could be saved in 2 formats (2 formats would of course only be needed if the optimized format isn't widely supported). One being the original format and the other being either WEBP or AVIF. Doing so would allow elements and modules to make use of these images which you will learn more about in the next section.

If images are automatically converted to WEBP there wouldn't be a need for the original fallback image since [WEBP has such good support in the major web browsers worldwide](https://caniuse.com/webp). If on the other hand, images are saved as AVIF, there could be a need for a fallback. Otherwise, images would break in browsers that don't support the specific image format.

## How to automatically convert images?
Once the websites have images saved in either an optimized format or with a fallback, then elements and modules can make use of them by always showing the most optimized image format.

Here is an example of how an element could show an image with a fallback in case the web browser doesn't support the chosen image format.

```
<picture>
   <source srcset="/path/to/webp/image" type="image/webp" />
   <img src="/path/to/fallback/image" alt="" />
</picture>
```

Using the example above will make the web browser try to show the WEBP image before showing the fallback in the image tag.