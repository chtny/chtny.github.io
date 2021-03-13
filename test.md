---
layout: page
title: Test
permalink: /test
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/ldU1WohPhIc" ></iframe>

<iframe width=700 height=500 src="https://www.youtube.com/live_chat?v=ldU1WohPhIc&embed_domain=chaitanya.page"></iframe>

<div class="iframe-container"><iframe loading="lazy" src="https://www.youtube.com/embed/ldU1WohPhIc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

```
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
```

<div class="iframe-container"><iframe loading="lazy" src="https://www.youtube.com/live_chat?v=ldU1WohPhIc&amp;embed_domain=chaitanya.page"></iframe></div>

```
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

<style>
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
	</style>