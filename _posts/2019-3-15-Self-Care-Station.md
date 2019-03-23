---
layout: post
title: Self-Care Station
categories: Software
---

I recently responded to a job posting in the Computer Science newsletter for a website and logo design for Cal Poly PULSE (Peers Understanding Listening Supporting Educating). I got the job! PULSE provides health resources to students on campus, and my job was to help them design a self-care campaign. You can find the finished product [here](https://self-care-station.now.sh).

### Stickers
First and foremost, I designed stickers with a QR code on them that would lead to the "Self-Care Station", a website with podcasts recorded by the PULSE students. After testing several styles of stickers, we found that students preferred stickers that were unique to the San Luis Obispo area. So, I created three different "landmarks" of stickers: Bishop Peak, Morro Rock, and the Fremont Theatre.

![Logos]({{ site.baseurl }}/images/SelfCare/logos.jpg "Logos")

After another round of survey, we settled on the original Bishop Peak design, in three different colors.
![Final Logos]({{ site.baseurl }}/images/SelfCare/FinalThree.jpg "Final Logos")

### Web App
The bulk of the project was designing the [Self-Care Station web app](https://self-care-station.now.sh). I had been meaning to learn React.js, and this seemed like a perfect opportunity. So, I dove into React and designed the Self-Care Station to work entirely in the browser, no back-end required! Of course, the podcasts still had to be hosted somewhere that the PULSE students could easily access them, so I used Dropbox as a CDN. I set up a dropbox app account with a folder for podcasts, and subfolders for the different podcast categories. When the PULSE students drop podcasts into the categories, they are instantly live on the self-care station website. Also, I parse a markdown file, profiles.md, into responsive HTML for the "about" page.

The most challenging part of this build, besides learning React, was getting the audio working on mobile. All mobile browsers have intense restrictions around autoplaying audio, which is what the PULSE team wanted. Unfortunately, we were not able to get around this, so I added a splash screen inviting the user to "listen to an intro podcast" or "dive right in". If they click intro podcast, it plays the intro and takes them to the podcasts page. The other button also takes them to the podcasts page, but does not play the podcast. Since I was learning React as I went, I made several mistakes in the beginning that I had to completely rewrite in the middle of the project. But hey, such is Software Engineering.

### Takeaway
I learned a lot from this project (thanks, StackOverflow!), and was able to help the Cal Poly community at the same time! It was very rewarding to see the stickers around and see that people are actually using the Self-Care Station (thanks, google analytics!) All of the code for this project can be found on [my Github](https://github.com/WiFuchs/self-care-station).