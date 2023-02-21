---
title: Image formats
subtitle: What are they, which are best for the internet, and which are best for the desktop?
metaDescription: This is a meta description used for meta
metaKeywords: Image formats for the web, Image formats, JPG, JPEG, PNG, GIF, WEBP, AVIF, AV1, Best image format for the web
---

# Image formats
Images are one of the big polluters on the internet, and one of the reasons is that people still use old and outdated picture formats. This article dives into the available image formats, and which are best to use on the internet and on your desktop.

## Available image formats/extensions
Over the years we have seen some new image formats surfacing, so now there are more formats than ever before. If you are not working with images on a daily basis it can be hard to figure out which are the best to use and what each of them is good for. Below you will find a description of the image formats and what to expect from them.

### JPG/JPEG
JPEG (often abbreviated as JPG) is a popular image file format for storing digital photographs. It stands for Joint Photographic Experts Group, the organization that developed the format.

JPEG is a lossy compression format, meaning that when an image is saved in the format, some of the image data is discarded to reduce the file size. This is achieved by using a compression algorithm that identifies areas of the image with similar colors or patterns and then groups those areas together into larger blocks. The result is an image file that takes up less space on disk but also has some loss of detail and quality.

JPEG images are widely supported by software and hardware devices, making them a versatile choice for storing and sharing digital photos. They can be displayed on a wide range of devices, from computer monitors to mobile phones, and can be printed at high resolutions for use in physical media such as magazines or photo prints. However, because JPEG is a lossy format, repeated editing of a JPEG file can result in a gradual loss of image quality, and therefore it may not be the best choice for the long-term archival of important images.

### PNG
PNG (Portable Network Graphics) is a popular image file format used for storing digital images, graphics, and icons. It was designed as an open, patent-free alternative to the GIF format with licensing restrictions.

One of the key features of PNG is that it supports lossless compression, which means that the image data is compressed in a way that does not result in any loss of detail or quality. This makes PNG a good choice for storing images that need to be of high quality, such as logos, graphics, and illustrations. PNG images also support transparency, making them popular for web design and other applications requiring images with transparent backgrounds.

One potential disadvantage of PNG is that it can result in larger file sizes than some other image formats, such as JPEG. This is because PNG images use lossless compression, which means that they cannot discard any information from the image data. However, the larger file size can be an acceptable trade-off for images that require high quality and transparency.

### WEBP
WebP is an image format developed by Google, designed to offer high compression efficiency and high image quality. It uses a combination of lossy and lossless compression techniques to achieve this goal.

WebP is rapidly gaining popularity in web design and development. The format supports both lossy and lossless compression, which means that users can choose between a smaller file size with some loss of image quality, or a larger file size with no loss of image quality.

One of the key advantages of WebP is that it offers significantly smaller file sizes than other popular image formats, such as JPEG and PNG, without sacrificing image quality. This makes it a good choice for websites. Additionally, WebP supports transparency and can display images with a larger color depth than JPEG, which makes it a versatile choice for a wide range of web and mobile applications.

One downside to WebP is that some older image processing software still doesn't support WebP. But as it becomes more popular it will gain more support generally. All modern web browsers today have the full support and embrace the use of WebP on the internet.

### AVIF
AVIF (AV1 Image File Format) is a newer image file format based on the AV1 video codec, which was developed by the Alliance for Open Media (AOMedia). Like WebP, AVIF is designed to offer high compression efficiency and high image quality, but with the added benefit of supporting HDR (High Dynamic Range) and wide color gamut images.

AVIF achieves high compression efficiency by using a combination of lossy and lossless compression techniques. It uses the same video codec technology as AV1, which is a next-generation compression technology that can provide up to 50% better compression than other popular codecs like H.264 and H.265/HEVC. This means that AVIF images can be significantly smaller than other popular image formats, such as JPEG and PNG, without sacrificing image quality.

One of the key advantages of AVIF is that it supports HDR, which allows for a wider range of colors and brightness levels than standard images. Additionally, AVIF supports alpha transparency and can display images with a larger color depth than JPEG, which makes it a versatile choice for a wide range of web and mobile applications. Overall you can have images with much better quality in a much lower file size.

### GIF
GIF (Graphics Interchange Format) is a popular image file format that was first introduced in 1987. GIF files are compressed images that can be animated or still images. They are widely used on the web for small animations, logos, and simple illustrations.

One of the key features of GIFs is their support for animation. By combining multiple frames of an image into a single file, GIF allows for simple animations to be created. These animations are often used for simple graphics, banners, and other decorative elements on websites.

Another key feature of GIFs is their support for transparency. GIF images can be made transparent so that only certain parts of the image are visible, which makes them a popular choice for web design and other applications where images with transparent backgrounds are required.

GIF supports up to 256 colors, which is a relatively low number compared to other image formats such as JPEG and PNG. This can result in a loss of image quality when compared to higher color depth formats. Additionally, the compression used in GIF images is lossless, which can result in larger file sizes than other formats that use lossy compression.

GIFs however are becoming an older format and also a heavier one, which means there are better solutions out there.

## Most used formats today
Still today most websites are using traditional image formats such as JPEG and PNG, but we see more and more switch over to WEBP. Since WordPress version 5.8 came out in 2021, a large portion of the internet has moved over to WEBP. One of the reasons is the increased website speed caused by the lighter images, and for some, it is also because of the reduced impact they have on the environment. The world is still transitioning into the WEBP era, but hopefully, soon we will see the entire internet use WEBP instead of heavier formats like JPEG, GIF, and PNG.

## Which format is the best to use?
Simply stating which image format is the best one to use is challenging, because it depends on your criteria. On the internet, we will most often have images that are as light as possible since it will reduce the environmental impact and also speed up the website significantly. Therefore if you are saving the images on the internet it is best to use the WEBP format, and then make sure to compress the image.

If you on the other hand are looking for a lighter image format for your pictures on your desktop, then AVIF is the answer. AVIF will in many cases also be better for the internet, but the global browser support is still relatively low compared to WEBP. If you want to save your images in high quality on your desktop, then AVIF is fantastic. It supports HDR and extremely high-quality images, but the compression is much better, which means the images come out lighter than they would using PNG. This means you can save much more images on your hard drive if you convert them to AVIF instead of HEIC, JPEG, PNG, and all the other used formats.

With that said, you can still use AVIF on the internet without any problems. Using this format will make your website ready for the future, and fallbacks can easily be made using the HTML5 picture element. The fallback image could for example be a WEBP version which would be used if the users' browser doesn't support AVIF/AV1.
