---
layout: page
title: Test
permalink: /test
---
```html
<div class="iframe-container"><iframe loading="lazy" src="https://www.youtube.com/embed/VIDEOID" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

.iframe-container {
	overflow: hidden;
	padding-top: 56.25%;
	position: relative;
}
.iframe-container iframe {
	border: 0;
	height: 100%;
	left: 0;
	position: absolute;
	top: 0;
	width: 100%;
}

<div class="iframe-container"><iframe loading="lazy" src="https://www.youtube.com/live_chat?v=VIDEOID&amp;embed_domain=ishanya.design"></iframe></div>

.iframe-container {
	overflow: hidden;
	padding-top: 100%;
	position: relative;
}
.iframe-container iframe {
	border: 0;
	height: 100%;
	left: 0;
	position: absolute;
	top: 0;
	width: 100%;
}
```