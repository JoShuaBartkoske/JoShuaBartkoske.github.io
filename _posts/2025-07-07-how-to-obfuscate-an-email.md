---
layout: post
title: "How to obfuscate an email"
date: 2025-07-07
---

How many times have I received spammy emails? Too many to count.
As I have prepared my website for a final release before the [ICRC](https://indico.cern.ch/event/1258933/), I have been wondering how to best allow myself to be found and contacted by others.
The first way I thought was to put my email directly on my webpage, but I began to wonder if that was safe. I often receive spammy emails and I didn't want to offer another place on the internet for bots to collect my email address.

So how does one go about hiding or obfuscating their email? Well, I am not completely sure. But after trying to follow [Jonathan McGlone](https://jmcglone.com/guides/github-pages/) on his Github repository and follow along with his version of obfuscating (a simple trick with mirrors), I decided to venture out on my own.

I ended up finding a very useful website: [https://spencermortensen.com/articles/email-obfuscation/#text-display] that showed exactly which ways were most effective at prevent bots from getting your data. I used the method: 1.5 CSS Display None. For anyone who has got this idea in their head to use with their own email on their personal Github Pages website, I would simply recommend looking at their example and noticing that the text within the second "span" is omitted from the printed words. 
While this won't fool anyone with eyes (you can see the email) or anyone with a copy-paste tool (you can highlight the text and copy it), the website does say it fools bots. I don't know if it works yet, but time will tell. I simply hope it does fool the bots who are looking at my code and not simply copying stuff from the screen reader.
