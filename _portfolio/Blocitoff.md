---
layout: post
title: Blocitoff 
short-description: Blocitoff that allows users to create self-destructing to-do lists
feature-img: "img/blocitoff_2.png"

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff_2.png)


## Explanation

The Blocitoff application permits users to easily create an account and keep track of all their to-dos. More importantly, it creates a ticking to-do time bomb, meaning
that each to-do must be done within 10 days or it will be automatically deleted. It's great for procrastinators and even the responsible ones. 

## Problem

The biggest problem I faced within this build it how to create the ticking to-do time bomb and also create a seamless user interface. Both would be critical in the 
user experience. 

## Solution

For the first obstacle, I decided to create a custom rake task. We use rake for administrative tasks within rails, but in my situation, I used to automatically delete
expired to-dos. 

Secondly, I used AJAX. By doing this, the user would never have to refresh their page when deleting any item they completed before it exploded.  

## Results

With the use of AJAX and a custom rake administrative tool, users could create to-do time bombs with ease.

## Conclusion

This project was very informative in terms of introducing me to AJAX. I was always curious how other web apps create such a seamless experience, and with some
basic learning, I now know how to as well!

If you want to fork the application for your own use, click [here.](https://github.com/chiragshah321/blocitoff)

If you want to begin using the application, check it out [here.](https://damp-hamlet-24832.herokuapp.com/users/sign_in)

