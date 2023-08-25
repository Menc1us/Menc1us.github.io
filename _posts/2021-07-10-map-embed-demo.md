---
layout: post
title: Map embed demo
categories: [map, demo]
---

You can easily embed a map in your posts. Here is an example,  

{% include map.html id="400&w=500&cp=52.192438262242455~-1.7097167968750004&lvl=16&typ=d&sty=r&src=SHELL&FORM=MBEDV8" %}

So how do you embed a map like this in your own Jekyll post?
<!--more-->

It's easy. All you have to do is,  
 - Go to [Bing Maps](https://www.bing.com/maps){:target="_blank"} and search your desired location.  
 - Click on **More**.  
 - Choose **Embed a map**.  

And from the map embed customization page uncheck following,  

 - **View Larger Map**.  
 - **Get Directions**.  
 - Click on **Generate Code** button.  

You'll get an HTML code like this,  

```html
<div>
     <iframe width="500" height="400" frameborder="0" src="https://www.bing.com/maps/embed?h=400&w=500&cp=52.193918309656475~-1.7079960000000072&lvl=15&typ=d&sty=r&src=SHELL&FORM=MBEDV8" scrolling="no">
     </iframe>
</div>
```

In the above code following is your map id,  

```text
400&w=500&cp=52.193918309656475~-1.7079960000000072&lvl=15&typ=d&sty=r&src=SHELL&FORM=MBEDV8
```

Now you can embed a map in your post by inserting this code in it,  

{% highlight html %}{% raw %}
{% include map.html id="400&w=500&cp=52.192438262242455~-1.7097167968750004&lvl=16&typ=d&sty=r&src=SHELL&FORM=MBEDV8" %}
{% endraw %}{% endhighlight %}

Easy, ain't it?  
