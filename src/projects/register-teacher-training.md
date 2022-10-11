---
layout: layouts/project.njk
title: Register trainee teachers
blurb: Designing a digital service to support school staff across England.
permalink: /projects/register-teacher-training/index.html
roles:
  - itemText: Digital service design
  - itemText: Interaction design
employer: Department for Education
year: 2020 to 2021
leadImage: /images/register-hero.png
leadImageAlt: "Screenshots from the Register service "
leadImageCaption: A functional prototype of the digital service meant it felt
  and worked like the real thing in user research.
introHeading: ""
intro: ""
outroHeading: Outcome
outro: >-
  I saw this project from initial prototype design, through the private beta
  which involved piloting the service with a sample group of live users to
  public beta where the service was officially public. 


  <br><br>In contrast to the legacy product, our service was insignificantly more usable and accessible. A metric we used to measure success was time to create a record. In the original product a record would take up to 20 minutes to create while we observed first time users creating records in 6-7 minutes.
---
Register Trainee Teachers does what is says on the tin, register trainees with the Department for Education and record the outcome of their training. Teachers across England will have their progress tracked using this service. 

## Where we started

We were replacing a legacy product which was relatively new but not at all designed or developed with users in mind. The existing product was inaccessible, and users complained of usability issues.

![The original dashboard](/images/dashboard-example.png "The dashboard or the original product we redesigned. Users struggled with the tasks they needed to complete..")

The product is essentially a CRM for trainee teachers, with user interaction largely focused on inputting data in forms. The original product had a number of issues:

* users were constantly being timed out
* a users progress wasn't being saved
* iconography, language and error messaging was confusing 
* forms were embedded within modals that presented significant accessibility challenges

![An example of the original forms.](/images/exit-information.png "There was no way to know how 'complete' a registration was nor what was left to complete.")

## Co-design for the win

This project had two senior designers. A bit of a treat to be honest, with ongoing opportunity for peer feedback and someone always there to bounce ideas off who knew the project intimately. Seeking and giving feedback are both challenging things to do well, yet get easier with practice and allow for better design. 

Designing collaboratively can be a rewarding experience but requires the people involved to be low on ego, strong in communication and also vulnerable and open to feedback.

## User centred design

I've not experienced user centered design done as well as it is within government design teams. UCD is respected by stakeholders and forms the core principles of how products are designed. There is no single person responsible for UX on the team and its refreshing! Instead we recognise that user experience is everybody's responsibility. 

The core UCD team is made up of user researchers, content and interaction designers with front end developers often helping to complete the group responsible for *UX,* and by sharing it we remove unintentional bias and bring our own individual experiences and knowledge to the product.

User needs define what we prioritise in design and what we ship first.

![A screenshot with post it notes from user research attached.](/images/ucd.png "UX is a team sport! After rounds of usability testing the UCD team analysed research data together, ensuring we all have a common understanding of the data and next steps.  ")

## Designing in flows

Some digital services are more transactional, with a relatively linear user journey. This service was far more complicated, where a trainee record may exist in the system for a number of years, meaning our users were required to return at multiple times to update data and complete tasks.

We mapped out complex parts of the user journey, allowing us to document the nuances around business rules.

![A user flow diagram](/images/flows.jpeg  "User flows were created to map complex processes and communicate business rules to the team before any visual design was done.")

## Designing in code

We designed this service exclusively in code, building a functional prototype using the [GOV.UK Prototype Kit](https://govuk-prototype-kit.herokuapp.com/docs), and using components from the [GOV.UK design system](https://design-system.service.gov.uk/). 

We produced a browser based prototype that looked, felt and most importantly worked like the real thing which allowed us to conduct detailed usability testing as well as provide a valuable resource for the development team to follow when moving our designs into production. 

![A screenshot of a code editor.](/images/code.png "The service was designed with HTML, CSS, Nunjucks and Express JS with not a Figma art-board in sight.")

## What we did

A simplified dashboard provided:

* a focus on the key data a user needed to know 
* links to critical guidance and task that needed attention

![A screenshot of a dashboard](/images/localhost_3000_home-10-.png "A caption goes here")

A significant issue with the existing tool was that users struggled to follow their progress when creating a record. The GOV.UK task list pattern helps "Task list pages help users understand: ...the order they should complete tasks in and when they have completed tasks".\
\
This pattern addressed the user's need for grouping related tasks and clearly signposting progress.

![A screenshot of a page listing the tasks needed to be done](/images/localhost_3000_new-record_overview-1-.png "We ensured it was clear to users which tasks they’ve completed and which still need their attention.")

User needed to track multiple trainees over a number of years. Trainee records can exist in multiple states and there was a need to provide a clear classification system and advanced filtering.

![A screen shot of trainee records screen](/images/filters.png "Advanced filtering allowed our users to maintain large numbers of trainees in various states.")

## Building empathy through user research

Working closely with user researchers on the team meant we could get into a rhythm of regular usability testing sessions, collaborative analysis, insight generation and iterative updates. When building empathy without users, there is no substitute for talking to actual users and observing them use the service. 

## Documenting design

We frequently documented our design using a [design history](https://bat-design-history.netlify.app/register-trainee-teachers/). The design history looks forwards and backwards, new posts show the team where the service is going and old posts tell us how we got to where we are now. It allows us to share what we learn with others and it ensures we’re being transparent and designing in the open.

![A screenshot of the design history](/images/bat-design-history.netlify.app_register-trainee-teachers_recording-training-outcomes-iteration-2_.png "The task reminds me that writing is hard and objectively documenting your own work is REALLY hard but it's worth it.")

## Celebrating team milestones

Some government digital service teams celebrate milestones with mission patches, a tradition that comes from the early space missions. I led our team in a team workshop to decide on our spirit animal and designed our mission patches. These were printed and then, as we are all remote, mailed across the country to the team. 

![A collection of mission patch designs](/images/mission-patches.png "A collection of mission patches I designed while working on the team. Each one represents a team achievement.. ")