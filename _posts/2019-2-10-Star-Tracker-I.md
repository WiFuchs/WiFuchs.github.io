---
layout: post
title: Star Tracker I
categories: Other
---

Recently, I've been getting into astrophotography, and this next weekend I'm going to Death Valley to take pictures! Taking pictures of the stars poses several interesting challenges, the largest of which is "star trails". The earth is rotating, so the stars rise and set. This makes the nice pin lights that we see turn into streaks in long exposure photos. There are workarounds, like bumping up the ISO and taking a shorter exposure, but they all ultimately result in a lower quality photo. So, I'm building a barn door star tracker mount for my camera. The tracker is aligned with the north star, and it opens up at the same speed as the earth's rotation. This cancels out the stars rotation and makes them appear stationary, preserving the pin lights that we see without sacrificing quality. I have about a week, and I'm setting a \$30 budget for this project...

### Materials

Since I have access to the laser cutter through the Cal Poly machine shops, I'm going to design the entire system in illustrator and then laser cut it out of scrap plywood. I will also be laser cutting the gears that I need. Total materials comes out to:

- small hinge
- 1/4" threaded rod
- 4x 1/4" nuts
- camera ball mount
- 28byj-48 stepper motor with shield
- arduino uno
- 4xAA battery pack

### Design

I bought the motor and decided how fast I could turn it efficiently with the arduino. Then, I roughly estimated how much space I would need for the mounts on the top and bottom, and added a few inches because I always underestimate that stuff... Then, I did a bit of geometry to figure out how fast the rod needs to be spinning to open the door at the right speed, and I designed gears with that ratio. Eventually I ended up with this:

![Star Tracker Final Plans]({{ site.baseurl }}/images/StarTracker/StarTrackerPlans.png "Star Tracker Final Plans")

### Build

The build was pretty simple, all the work was in the design and sourcing the materials. HOWEVER, I did completely forget to make a hole for the tripod mount. By extreme fortune and coincidence, the tripod mount is the same thread as the 1/4" rod, so I was able to cobble together a mount with a scrap piece of plywood and an extra 1/4" nut. This was at 10PM the night before we left, so I didn't have access to any tools. However, I did have a pocket knife and some superglue! It's not the best, but it holds the camera!

![The Knife Drill]({{ site.baseurl }}/images/StarTracker/knifeDrill.png "Knife Drill")

![Finished!]({{ site.baseurl }}/images/StarTracker/finished.png "Finished!")
