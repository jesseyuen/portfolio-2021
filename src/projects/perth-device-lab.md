---
layout: layouts/project.njk
title: Perth Device Lab
blurb: It was an open source project which centered around face-to-face human
  interaction rather than the impersonal act of forking someones repo.
permalink: /projects/perth-device-lab/index.html
roles:
  - itemText: Community facilitation
  - itemText: UI design
  - itemText: UX design
  - itemText: Frontend development
employer: Humaan
year: "2016"
leadImage: /images/device-lab-1.jpg
leadImageAlt: test alt
leadImageCaption: Opening week of the Perth Device lab in February 2016. So neat and tidy!
introHeading: Intro
intro: Test
outroHeading: Outcome
outro: Content here
---
The Device Lab was my passion project while working for [Humaan](http://humaan.com/ "Visit Humaan") and it was a great experience opening our doors to local developers, startups, students, educators, government agencies, suits, thieves and other curious visitors in my time as coordinator.

![](/images/device-lab-2.jpg "A welcoming and vibrant space to test your website or perhaps hot desk for a while.")

The lab is probably much like many other testing environments you might find in the web development industry. A collection of devices in a room. What make this lab different is that the doors are open to the public!

### Converasational

Before opened we dubbed the lab the *Device Lounge*. This reflected our intention for the space to be warm and welcoming for visitors. Somewhere you felt relaxed. Casual, conversational copy and a vibrant colour palette helped convey this online.

![](/images/lab-hero-desktop-2.jpg "An excerpt of the labs one-page site. A functional layout with a straightforward 2 column grid. It was designed with performance in mind.")

Functional design still has the opportunity for attention to detail, and here it presented itself in the sites header. The modular logo (designed by [Kylie!](https://twitter.com/kylietimpani)) is subtly animated and is a composite of svg assets and CSS shapes brought to life with `keyframe animation` and `blend modes`.

![](/images/urvin.jpg "Local startup Speqs testing in the lab pre-launch.")

We wanted the online and onsite experience to remain consistent (and positive) for our lab visitors. Someone making an online booking was greeted with a conversational form in an attempt to make the interaction feel as natural and engaging as a form can feel. Once submitted I would follow up with a phone call to quantify their needs and expectations, ensuring we could optimise the experience for them if possible.

![](/images/lab-booking.gif " Continuing the conversational tone during the booking process.")

### A performance budget you say?

Typically you might start a design project with some rough sketches or a moodboard. This project begun with a performance budget. On first load the site needed to weigh less than 1mb on the common mobile viewport and less 2mb for common desktop viewport.

To help achieve this the design remained lean, css written mobile first, we lazy loaded assets like large images and google maps and webpack bundle optimisation.