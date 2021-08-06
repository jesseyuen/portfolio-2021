---
layout: layouts/project.njk
title: Contribute to The Guardian
blurb: Stakeholders
  understandably wanted to maximise revenue, though I felt our users deserved
  more too. A case study of design balancing both business and user needs on The Guardians revenue and Subscriptions team. 
permalink: /projects/contribute/index.html
roles:
  - itemText: UX design
  - itemText: UI design
  - itemText: Accessibility advocacy
employer: The Guardian
year: "2019"
leadImage: /images/contribute2.png
leadImageAlt: test
leadImageCaption: Bold typography and considered UI ensured the new contribution
  journey still felt 'Guardian' whilst also making it a far more inclusive experience.
outroHeading: Outcome
outro: |-
  We covered a lot of ground in this piece of work including fixing fundamental accessabiliy and usability issues, piloting new design sytem components and visually evolving our contrubution journey.

  The stakeholders were happing with postive revenue gains and our users were given a significatnly improved experince. 
---

Joining a new team well can be hard work. Your entry style speaks volumes about who you are, how you work and creates a lasting impression on the team. When I joined this team I set out to win trust with stakeholders and form healthy realtionships with people I'd be working closely with.    

Due to the nature of the product, the teams roadmap understandanly revolved around maximising revenue for the Guradian. Often user needs and businsess needs are complimentary and in this project I felt there was a need to advocate for the user focused work too.  

![](/images/the-before.png "What the Contribution page looked like when I joined the team.")

### Accessibility audit

An initial piece of work involved an accessability audit which:

1. A manual testing of the journey via keyboard navigation alone
2. A manual testing of the journey with a screen reader (Voice Over in this instance)
3. Testing with automated tools for WCAG errors

This was a new process for the team and having never run an accessability audit, some interesting results were uncovered. 

It turns out the journey was impossible to complete when using either keyboard or screen reader, with mutiple form elements creating keyboard traps, trapping focus so the user can't progress. Other form elemrts were hidden commpletely from keyboard and assistive technology users. 

Playing this back to the team, it wasnt hard to convince stakeholders to prioritise fixing these isuses. When a products primary purpose is to generate revenue, you want you user base to be as large as possible.

![](/images/breakdown.png "Detail of the original design highlighting four areas of focus from the usability review.")

### Usability review

Following was a usability review. For such a small amount of real estate, there was A LOT going on.

1. We were using a tab pattern to collect contribution frequecny. The grail of UI guidence, the GOV UK Design system docs, state that tabs should "let users navigate between related sections of content, displaying one section at a time." These look like tabs but are they really? Under the hood they are radio buttons. Are users navigating different cotent? No, they are just choosing an option. 
2. More radios! Though these ones look totally different to the previous set of faux-tabs. Why? They also are significantly less prominent to the row above. My hunch was they we should be placing equal visual importance on both contribution frequency and amount options.
3. The three text fields were very busy. Was it really necessary to mark each as required? Did we need leading icons to help identify rather generic form fields? Probably not.
4. A third set of radio buttons, again with unique styling, although somewhat more traditional. The accessability audit hightlightend that these performed poorly in terms contrast and also other colour checks. 

### What we did

Based on the accessbility and usability reviews, we got buy in for a significant design overhaul.

I consolidated the three random radio button styles into one consistent pattern, a UI pattern that was eventaully called <a href="https://guardian.github.io/source/?path=/story/choicecard--single-state-light" target="_blank">choice cards</a>. At this time the Guradian Design System was in its infamacy and we used this project to publicly pilot the new component and also experiment with the workflow bewteen the product and design sytsem teams.

Sets of radios were also now clearly signposted by accessible labels.

![](/images/choice-cards.png "Increased consistancy within the UI with a focus on accessability.")

### Opportunities within contrsatints   

Though much of this design process involved simplification we also wanted to accomodate bespoke marketing events at The Guardian. The updated design had a generous enough amount of realstate to offer bespoke opportunities within contrsatints.

![](/images/earth.jpg "Concept design with placeholder illustration.")

![](/images/free.jpg "Concept design with placeholder illustration. I've forgotten where I found this one now 😬")