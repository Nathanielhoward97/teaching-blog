---
layout: post
title:  "Videos and Images with Jekyll"
date:   2022-07-13 10:40:30 -0400
categories: jekyll update
---

# Here's an example post for embedding video content and images from the web in jekyll.
You can use simple html for the purposes of both video and images - markdown won't interfere with code that it recognizes as html with proper syntax.

### An example video
My cat loves to watch birds on my second monitor. Here's an embed code for a video I pulled from youtube:

<iframe width="853" height="480" src="https://www.youtube.com/embed/xbs7FT7dXYc" title="Videos for Cats to Watch - 8 Hour Birds Bonanza - Cat TV Bird Watch" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

You can see there are several components to the code - some directions to set the video's frame height and width in pixels, as well as the video's source and title, along with permissions for youtube to play to the pages site.

Youtube and other video hosting sites often have a button on any video's page to allow you to copy the embed code. Depending on where you want to host video content for your blog, there may be differences in the particular permissions, but the basic syntax should be the same. 

### Making an Image Directory

What about an image? Like a video, an image needs a source - but unlike a video, markdown natively supports embedded images. To embed an image, all you need is to create a directory for assets in the same branch from which your pages site is hosted.
Upload an image file to that directory or a subfolder within specifically for images. Since jekyll pulls from the same repo, the code you need to reference that image in your post is pretty simple - 

![Arculf Map of Jerusalem](/teaching-blog/assets/images/jerusalem-map-arculf.jpg)
Looking spiffy. Markdown will support the conventional image file formats that html does, including .jpg and .png.
