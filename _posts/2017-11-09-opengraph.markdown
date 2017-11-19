---
layout: post
comments: true
title:  "How i did with opengraph"
date:   2017-11-09 10:37:27 +0100
categories: General
---


## Open graph
Open graph enables the possibility to create links with graphical content.
When i implementede Open Graph I created a new file in `_includes`,
`opengraph.html`. in `opengraph.html` I applyed Basic Metadata, with 
title, type, image and url. To make the Open Graph work i include 
it in `head.html`. 
### My opengraph.html
```
<html prefix="og: http://ogp.me/ns#">
<head>
<title>My blog</title>
<meta property="og:title" content="Site" />
<meta property="og:type" content="website" />
<meta property="og:url" content="http://ke222pf.github.io" />
<meta property="og:image" content="http://ke222pf.github.io/img/bakgrund.jpg"/>

</head>

</html>
```