---
layout: post
title: *Personal Project* Blocipedia
short-description: Blocipedia allows users to create public and personal wikis 

---

{:.center}
![]({{ site.baseurl }}/img/myblocipedia.PNG)

## Explanation

The blocipedia is a light replica of wikipedia. But, it differs two ways. Users can upgrade their account and add collaborators. Hence,
they can restrict who edits their posts. Maybe this is the model for wikipedia? But, maybe it's a bit too restrictive. 

## Problem

Question was : How could I include payments, and how should I add the ability to add collaborators.

## Solution

Very simple - add stripe. The API provided the payment processor was easy to install as a gem and utilize in the application. Moreover, by using the enum
attribute, it was relatively easy to create restrictions based on stripe payments. For instance, if you paid via stripe, I'd consider that fact in a method 
and that upgraded your user type. If you met a specific user type, you'd be able to add collaborators. 

## Results

To ensure a simple user experience, I added the ability to 'upgrade/downgrade' an account right next to your account details. Adding collaborators was simple as well as I
included a input box to add/delete collaborators. 

## Conclusion

This was my first time integrating an API such as a stripe. I pushed a few payments to it after integrating it into my application, and as expected,
it worked. Look forward to using more APIs like this in the future.

If you want to fork the app, you can click [here!](https://github.com/chiragshah321/blocipedia)






