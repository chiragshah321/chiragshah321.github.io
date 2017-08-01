---
layout: post
title: Bloccit
short-description: Bloccit is a reddit replica that allows users to create posts, upvote posts, and comment on posts
feature-img: "portfolio-kami/img/blocitt.PNG"

---

{:.center}
![]({{ site.baseurl }}/img/blocitt.PNG)


## Explanation

Bloccit is a replica to the classic Reddit. Like reddit, users can view an index of categories. Within each category, there are a number of related posts,
which can be commented on or upvoted. Moreover, users can also create new posts to add to the index of posts. There are a few restrictions as well, such as the ability to 
manage categories, posts, upvotes, etc. 

## Problem

The biggest problems within this project were related to the user profile and the identification of various users. 


## Solution

To solve these problems, I created a user profile, which was connected to the well-known gravatar solution. Utilizing this open solution allowed users to add 
some personality to their posts and also their profile. Within the profile I included all the users own posts, along with their upvotes. This allowed users to easily manage
everything they were working in one location. 

To identify various users I used [enum](http://edgeapi.rubyonrails.org/classes/ActiveRecord/Enum.html). This attribute was wondorous. Like the description, it allowed me to 
map integers to specific user types. For example, I could define as admin as '5', and that's the number that would be listed in the DB. Easy access and simple manipulation. 

## Results

After using enum and installing the profile, Bloccit became much more personal to the user. Without it, there would have been little distinction between users. Moreover, with
the profile function, I created the ability for users to centralize all their activity. 

## Conclusion

At the end of the day, this is much less robust then Reddit. But, that's primary due to server space. Ultimately, the functionality is very similar. I'm glad I had this
opportunity to build something with utility that mirrors the homepage of the intenet. 

If you want to fork the application for your own use, click [here.](https://github.com/chiragshah321/bloccit)

If you want to begin using the application, check it out [here.](https://radiant-wave-95164.herokuapp.com/)





