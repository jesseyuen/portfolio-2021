---
layout: layouts/project.njk
title: Register teacher training
blurb: We redesigned their entire collection of interface components as well as
  developed infrastructure and logic around how they could create new,
  responsive and accessible layouts.
permalink: /register-teacher-training/index.html
roles:
  - itemText: Digital service delivery
  - itemText: Interaction design
employer: Department for Education
year: "2021"
leadImage: /images/demo-image-1.jpg
introHeading: The challenge
intro: This design project was completed while I freelanced remotely for Studio
  Papa, a digital agency based in Western Australia. The budget was (very) tight
  yet we wanted to deliver something that would be flexible enough to allow our
  client to scale their online presence and offerings.
outroHeading: Outcome
outro: This design project was [completed while](google.com) I freelanced
  remotely for Studio Papa, a digital agency based in Western Australia. The
  budget was (very) tight yet we wanted to deliver something that would be
  flexible enough to allow our client to scale their online presence and
  offerings.
---
Working closely with a creative director I designed and then developed a libray of components and patterns that is intended for an inhouse team of software engineers. We redesigned their entire collection of interface components as well as developed infrastructure and logic around how they could create new, responsive and accessible layouts.

We prioritised accessibility and semantic meaning when developing the system and relied heavily on modern techniques like CSS Grid for layout and CSS Custom Properties for presentation.

![](/images/demo-image-2.jpg "test caption")

### Heading

Working closely with a creative director I designed and then developed a libray of components and patterns that is intended for an inhouse team of software engineers. We redesigned their entire collection of interface components as well as developed infrastructure and logic around how they could create new, responsive and accessible layouts.

We prioritised accessibility and semantic meaning when developing the system and relied heavily on modern techniques like CSS Grid for layout and CSS Custom Properties for presentation.

test

> ![](/images/demo-image-1.jpg "test caption")

test test

{% import "macros/macros.njk" as macro %}

{{ macro.appProjectList({
  items: [
    {
      href: '/link',
      heading: 'Test title',
      desc: 'Desc',
      details: 'tag name, tag name'
    },
    {
      href: '/link',
      heading: 'Test title 2',
      desc: 'Desc',
      details: 'tag name, tag name'
    }
  ]
}) | safe }}

