---
layout: post
title: Blocjams
short-description: Blocjams is an online music app that plays your favorite music.
feature-img: "portfolio-kami/img/blocjams.png"

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Explanation

People want music at their fingertips, all the time, everywhere. Sure, there's YouTube, Spotify, and a variety of other music apps. But, with Blocjams, you can utilize a web application just for your music.

## Problem

Accessing music through a static website is almost impossible, and if it is, it's frustrating. For Blocjams, it was necessary to circumvent this frustration by allowing a user to simply enter the web app and begin playing music by pressing play. 
Additionally, accessing a web application that plays music on a mobile phone can be cumbersome and buggy, hence making the Blocjams player responsive was critical. In brief, the two problems I was trying to address in the project were:


* Static website music players, which only allowed access to one type of music and not a myriad of albums.
* A responsive audio player accessible anywhere. 

## Solution

Using a variety of images, music files, and JavaScript libraries, the Blocjams player was born. The assets included images of albums and audio files from those albums. jQuery was used to create dynamic movements within the Blocjams player bar and also allowed for simple selection within the album. 
Consequently, users could easily switch, play, or pause songs in the player bar. Lastly, the player bar itself was adjustable via jQuery selectors and handlers. The audio player song file was enabled via the Buzz API, which allowed users to better interact with the player bar and the volume of the song. 

## Results

The Blocjams static home page, album collection page, and also album contents page. The static page was an aesthetically pleasing introduction to the website and its capabilities. By selecting _collection_ users could access the entirety of the albums available. 
Thereafter, they could select the album of their choice. Once in the album, users could begin playing by simply selecting the play button. Switching was conducted via the player bar or by selecting a new song. And the user also had the option of changing the place in the song and the volume of the song. 

> The Blocjams player only had three pages, but due to its functionality, it provided the music obsessed listener with direct access to what matters most, the song. 

To ensure responsiveness, I used certain CSS styling that augmented the structure if the screen size changed. Hence, the music lover could find, select, and play the song of their choice anywhere. 

## Conclusion

I was surprised to discover how simple API plugins and jQuery could create such a dynamic webpage. Further, I learned the DOM, its magnificent usefulness, and how CSS selectors are used across an interface. 

 **I learned that labeling functions very specifically was key in efficiency as my codebase grew.**  


