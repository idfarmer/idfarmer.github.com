---
layout: post
category : test_category
tagline: "WHAM!"
tags : [intro, beginner, jekyll, tutorial]
title: Check it Out
---

<a href="http://www.flickr.com/photos/idfarmer/6882093965/in/photostream/"><img src="http://farm8.staticflickr.com/7207/6882093965_d4237d0633_b.jpg"></a>
{% include postbody.html %}
This is what it looks like when you lead off with a big fat image. Isn't it nice?
Yeah, it's alright.

Boom! Ready for an inline carousel?


{% include carousel.html %}
<div class="item"><a href="http://www.flickr.com/photos/idfarmer/6882096993/in/photostream/"><img src ="http://farm8.staticflickr.com/7209/6882096993_633bc9a2c5_b.jpg"></a></div>
<div class="item"><a href="http://www.flickr.com/photos/idfarmer/6882097967/in/photostream/"><img src ="http://farm8.staticflickr.com/7198/6882097967_2c383d36c7_b.jpg"></a></div>
{% include endcarousel.html %}
{% include endpostbody.html %}