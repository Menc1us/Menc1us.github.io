---
layout: post
title: Spotify playlist demo
spotifyplaylist: 2iaDUy0RVHVy2XxvQFnEBc
categories: [playlist, spotify]
excerpt: You can tell a lot about a person by what’s on their playlist.
---

"You can tell a lot about a person by what's on their playlist."  
~ Dan Mulligan (Begin Again)  

Embeding a spotify playlist is easy.  
All you need to do is add the id of the spotify playlist in front matter block of your post like this,  
```
spotifyplaylist: 2iaDUy0RVHVy2XxvQFnEBc
```  
Where ` 2iaDUy0RVHVy2XxvQFnEBc` is the id of the playlist you want to embed.  

Next add following snippet at a place in your post where you want the playlist to appear,  
```
{% include spotifyplaylist.html id=page.spotifyplaylist %}
```  

And this is how it will look in your post,  

{% include spotifyplaylist.html id=page.spotifyplaylist %}  

Music is a healer for heart, body & soul.  
