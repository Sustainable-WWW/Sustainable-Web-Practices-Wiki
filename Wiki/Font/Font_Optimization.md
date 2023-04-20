---
title: Font optimization
subtitle: Making your custom fonts the fastest version of themselves
metaDescription: Sometimes you need custom fonts for a website, but that doesn't mean they cannot be optimized. In this tutorial you learn how to optimize fonts to make them the fastest versions of themselves.
metaKeywords: Font optimization, FontSquirrel, WOFF, WOFF2
lastEdited: 20/April/2023
---

# Font optimization

Fonts are an integral part of any design project. They have the ability to set the tone and create the perfect mood for your content. However, not all fonts are compatible with all browsers and devices. That's where web fonts come into play. Web fonts are fonts that are specifically designed to be used on websites and can be easily downloaded by the browser. In this article, we will explore how to convert font files from TTF and OTF to WOFF and WOFF2 using FontSquirrel's web font generator.

FontSquirrel is a popular web font generator that allows you to convert fonts from one format to another. The service is free and easy to use, and it supports a variety of font formats including TTF, OTF, WOFF, and WOFF2. The best part is that FontSquirrel's web font generator offers an expert mode that allows you to customize your font conversion process to suit your needs.

**To get started with FontSquirrel's web font generator, follow these simple steps:**

1. Go to FontSquirrel's web font generator at **[https://www.fontsquirrel.com/tools/webfont-generator](https://www.fontsquirrel.com/tools/webfont-generator)**.
2. Click on the "Add Fonts" button to upload your TTF or OTF font file.
3. Once your font file has been uploaded, you will see several options for customizing your font conversion process.
4. In the "Expert" tab, you can remove unnecessary languages and characters that you do not need. This will help to reduce the size of your font file, which is important for faster loading times.
5. In the "Subsetting" tab, you can choose which characters to include in your font file. This is especially useful if you only need a specific set of characters for your website.
6. Once you have customized your font conversion options, click on the "Download Your Kit" button to download your WOFF and WOFF2 font files.

Now that you have converted your font files to WOFF and WOFF2, you can easily import and use them in your SCSS file. Here's a quick tutorial on how to do that:

1. Create a new folder in your project directory called "fonts".
2. Place your WOFF and WOFF2 font files in the "fonts" folder.
3. Open your SCSS file and create a new @font-face rule for each font format, like so:

```scss
@font-face {
	font-family: 'MyWebFont';
	src: url('../fonts/mywebfont.woff2') format('woff2'),
	url('../fonts/mywebfont.woff') format('woff');
	font-weight: normal;
	font-style: normal;
}
```

1. 1. In your CSS, apply the font to the relevant elements:

```scss
body {
	font-family: 'MyWebFont', sans-serif;
}
```

And that's it! You've successfully converted your font files from TTF and OTF to WOFF and WOFF2, and imported and used them in your SCSS file. Using web fonts is an essential part of modern web design, and FontSquirrel's web font generator makes it easy to convert your font files to the appropriate format for use on the web.

## Potential savings and benefits

Switching from TTF and OTF to WOFF and WOFF2 can result in significant savings in file size, which is important for faster loading times on your website. WOFF and WOFF2 are specifically designed for web use and are optimized for web browsers. They use a compression algorithm that reduces the size of the font file without compromising on quality.

According to Google, WOFF2 files are approximately 30% smaller than WOFF files, and up to 50% smaller than TTF and OTF files. This means that by switching to WOFF2, you could potentially reduce your font file size by up to 50%. This can have a significant impact on your website's performance, especially on mobile devices where network speeds may be slower.

The savings in file size will also benefit users who are on limited data plans, as it will reduce the amount of data that they need to download when accessing your website. In addition, smaller font files will result in lower bandwidth usage and reduced server load, which can help to improve the overall user experience on your website.

Overall, switching from TTF and OTF to WOFF and WOFF2 is a smart move for anyone looking to optimize their website's performance. By taking advantage of the compression and optimization benefits of WOFF and WOFF2, you can improve your website's loading times, reduce bandwidth usage, and improve the user experience for your visitors. And with FontSquirrel's web font generator, it's easy to convert your font files to the appropriate format for web use.