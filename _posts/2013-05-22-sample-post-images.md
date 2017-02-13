---
layout: post
title: "A Post with Images"
date: 2013-05-22
excerpt: "Examples and code for displaying images in posts."
tags: [sample post, images, test]
comments: true
---

### Figures (for images or video)

#### One Up

<figure>
	<a href="http://imgur.com/IDDBcbd"><img src="http://imgur.com/IDDBcbd"></a>
	<figcaption><a title="package example">imgurl example</a>.</figcaption>
</figure>


#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
    <a href="http://imgur.com/5QpqdOS"><img src="http://imgur.com/5QpqdOS"></a>
    <a href="http://imgur.com/gtLoMeg"><img src="http://imgur.com/gtLoMeg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}


#### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

{% highlight html %}
<figure class="third">
	<img src="http://imgur.com/x10ylMD">
	<img src="http://imgur.com/cGN9T9K">
	<img src="http://imgur.com/EH8SgaL">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
{% endhighlight %}

