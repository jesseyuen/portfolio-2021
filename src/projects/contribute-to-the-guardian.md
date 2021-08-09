---
layout: layouts/project.njk
title: Contribute to The Guardian
blurb: Stakeholders wanted to maximise revenue, though I felt our users deserved
  more too. A case study of design balancing both business and user needs on The
  Guardians contributions team.
permalink: /projects/contribute/index.html
roles:
  - itemText: UX design
  - itemText: UI design
  - itemText: Accessibility audit
employer: The Guardian
year: "2019"
leadImage: /images/contribute2.png
leadImageAlt: test
leadImageCaption: Bold typography and considered UI ensured the new contribution
  journey still felt 'Guardian' whilst also making it a far more inclusive
  experience.
outroHeading: Outcome
outro: >-
  We covered a lot of ground in this piece of work including fixing fundamental
  accessabiliy and usability issues, piloting new design sytem components and
  visually evolving our contrubution journey.


  The stakeholders were happing with postive revenue gains and our users were given a significatnly improved experince.
---
The Guardian does not have a paywall and instead relies on readers' contributions and subscriptions as a large part of its funding model. The Contributions team's roadmap understandably revolved around maximising revenue for the Guardian. 

Often user needs and business needs are complementary and in this project I felt there was a need to advocate for user focused work too.

![](/images/the-before.png "What the Contribution page looked like when I joined the team.")

### Accessibility audit

My initial piece of work involved an accessibility audit which included:

1. Manually testing the journey with keyboard navigation
2. Manually testing of the journey with a screen reader (Voice Over)
3. Automated testing for WCAG and validation errors

This was a new process for the team and having never run an accessibility audit, interesting results were quickly uncovered.

It turns out the journey was impossible to complete when using either keyboard or screen reader. Multiple form elements were keyboard traps, trapping focus so the user can’t progress. Other form elements were completely hidden from keyboard and assistive technology users.

Playing this back to the team, it wasn't hard to convince stakeholders to prioritise fixing these issues. When a product's primary purpose is to generate revenue, it’s helpful if your user base is as large as possible. Profits aside, I wanted to convey that as creators we have an ethical duty to make the web a positive experience for all users.

![](/images/breakdown.png "Detail of the original design highlighting four areas of focus from the usability review.")

### Usability review

Following was a usability review. For such a small amount of screen real estate, there was A LOT going on.

1. We were using a tab pattern to collect contribution frequency. The grail of user interface guidance, the GOV UK Design system docs, state that tabs should “let users navigate between related sections of content, displaying one section at a time.” These look like tabs but are they really? Under the hood they are radio buttons. Are users navigating different content? No, they are just choosing an option.
2. More radio buttons! Though these ones look totally different to the previous set of faux-tabs. Why? They also are significantly less prominent to the row above. My hunch was that we should be placing equal visual importance on both contribution frequency and amount options.
3. The three text fields were very busy. Was it really necessary to mark each as required? Did we need leading icons to help identify rather generic form fields? Probably not.
4. A third set of radio buttons, again with unique styling, although somewhat more traditional. The accessibility audit highlighted that these performed poorly in terms of contrast and also other colour checks.

### Design updates

I consolidated the three random radio button styles into one consistent pattern, a UI pattern that was eventually called <a href="https://guardian.github.io/source/?path=/story/choicecard--single-state-light" target="_blank">choice cards</a>.

I consolidated the three random radio button styles into one consistent pattern, a UI pattern that was eventaully called <a href="https://guardian.github.io/source/?path=/story/choicecard--single-state-light" target="_blank">choice cards</a>. At this time the Guradian Design System was in its infamacy and we used this project to publicly pilot the new component and also experiment with the workflow bewteen the product and design sytsem teams.

Sets of radios were also now clearly signposted by accessible labels.

![](/images/choice-cards.png "Increased consistancy within the UI with a focus on accessability.")

### Opportunities within contrsatints

Though much of this design process involved simplification we also wanted to accomodate bespoke marketing events at The Guardian. The updated design had a generous enough amount of realstate to offer bespoke opportunities within contrsatints.

![](/images/earth.jpg "Concept design with placeholder illustration.")

![](/images/free.jpg "Concept design with placeholder illustration. I've forgotten where I found this one now 😬")

### Measuring success

This team was obsessed with multi-varient AB testing. Like proper obsessed. I'm more a 'let's stick this in  front of users' type designer but I recognise the role AB testing can play, espcially when the key success metric is revenue. This design didn't radical shift in contributions but the trend was positive and that was enough for us at the time.