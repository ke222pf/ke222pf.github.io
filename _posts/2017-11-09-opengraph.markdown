---
layout: post
comments: true
title:  "How i did with opengraph"
date:   2017-11-09 10:37:27 +0100
categories: General
---


## Open graph
Open graph enables the possibility to create links with graphical content.
When I implemented Open Graph I created a new file in `_includes`,
`opengraph.html`. In `opengraph.html` I applyed Basic Metadata, with 
title, type, image and url. To make the Open Graph work I included
it in `head.html`. 
### My opengraph.html
```

<title>My blog</title>
<meta property="og:title" content="Site" />
<meta property="og:type" content="website" />
<meta property="og:url" content="http://ke222pf.github.io" />
<meta property="og:image" content="http://ke222pf.github.io/img/bakgrund.jpg"/>

```