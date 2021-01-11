---
layout: page
title: Week 2T - Responsive Web
categories: dsgn270
---

## Lesson Prep
1. Read: [The web and web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards) by the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn) (link to their Learning Area)
2. Watch: [A brief history of layout](https://youtu.be/E005mjqpZ9Y) by [Layout Land](https://www.youtube.com/c/LayoutLand/)
3. Watch: The first 7 minutes of [Beyond Media Queries](https://vimeo.com/235428198) by Michael Riethmuller (you can stop at Fluid Typography)
4. Read: [Designing Card-Based User Interfaces](https://www.smashingmagazine.com/2016/10/designing-card-based-user-interfaces/)
5. Read: [The Thumb Zone: Designing For Mobile Users](https://www.smashingmagazine.com/2016/09/the-thumb-zone-designing-for-mobile-users/)
6. Skim: [Mobile vs. Desktop Usage in 2019](https://www.perficient.com/insights/research-hub/mobile-vs-desktop-usage-study)
7. Watch/Skim: [Mobile in Context: Design Principles of Flow and Navigation](https://youtu.be/OZRczPw1BBw)

## 1. The Evolution of Web Layout
### Learning Objectives
- Describe responsive design and what problem it tries to solve.
- List the physical and software characteristics that are unique to mobile devices.
- Discuss the relative market share of mobile web traffic vs desktop web traffic.
- Discuss the relative screen time spent on mobile apps vs mobile web sites.

### Terminology
<dl>
  <dt>Desktop vs Mobile Web</dt>
  <dd>A comparison of web traffic between desktop and mobile platforms.</dd>
  <dt>Native App vs Web App Screen Time</dt>
  <dd>A comparison of average time spent "on-screen" between web and native phone applications.</dd>
</dl>

### Activity: How is mobile unique?
You will work in groups of 3 or 4 for this activity. 

Beyond the obvious difference in screen size, discuss how mobile is different than desktop:
- What hardware features do mobile phones have compared to traditional desktop systems?
- Do users have the same goals when browsing on a phone vs browsing on a laptop or desktop? If not, what's different?
- What problems are mobile users often trying to solve?

Please add a comment your phone make and model in [this Issue](https://github.com/sait-wbdv/sait-wbdv.github.io/issues/7) 

#### Spoilers
- what are the device differences?
  - landscape vs portrait
  - screen size -> hamburger menu
  - no cursor -> no hover
  - gestures (with focus on the thumb)
  - performance
  - phone calls
  - location -> maps
  - camera
  - accelerometer

## 2. Common Mobile Design Patterns
### Learning Objectives
- Identify common design patterns for responsive web development.
- Explore how the standards of HTML, CSS and Javascript have evolved to better take advantage of mobile web.
- Create a block of minimally responsive body text using basic box model properties.
- Locate the box model diagram in FireFox Developer Tools

### Terminology
<dl>
  <dt>Web Responsiveness</dt>
  <dd>A Web development concept focusing on making sites look and behave optimally on all personal computing devices, from desktop to mobile.</dd>
  <dt>Viewport</dt>
  <dd>The viewable area of a website within the browser window.</dd>
  <dt>Media Queries</dt>
  <dd>A feature of CSS that enable webpage content to adapt to different screen sizes, orientations, aspect ratios and mediums (e.g. print vs screen).</dd>
  <dt>Breakpoint</dt>
  <dd>Points in responsive design where website presentation responds to changing viewport characteristics (width, orientation, etc).</dd>
  <dt>Hamburger Menu</dt>
  <dd>A button in websites and apps that typically opens up into a side menu or navigation drawer.</dd>
  <dt>Card Pattern</dt>
  <dd>A convenient means of displaying content composed of different types of objects. They are also well-suited for presenting similar objects whose size or supported actions can vary considerably, like photos with captions of variable length</dd>
</dl>

See: 
- [The building blocks of responsive design](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Responsive/responsive_design_building_blocks)
- [Responsive Text Cheatsheet]({{site.baseurl}}/cheatsheets/design/responsiveness)
- Codepen: [Responsive Text: Max line length with scroll track](https://codepen.io/browsertherapy/pen/RwaJmbx)
- Codepen: [Starter - Responsive Text: Max line length with scroll track](https://codepen.io/browsertherapy/pen/dyMKEzd)
- Codepen: [Puppy Card](https://codepen.io/browsertherapy/pen/mdPWXZb)
- Codepen: [Basic 1x3 Card Pattern](https://codepen.io/browsertherapy/pen/vYGxRNB)

### Activity: Dev Tools vs Mobile Devices
You will work in groups of 3 or 4 for this activity.

Compare and contrast the visual appearance of your favourite mobile websites between
1. The virtual mobile simulator in FireFox Dev Tools, and
2. A real mobile device.

How accurate is the phone simulator in FireFox (or Chrome)? Submit screencaps to [this Issue](https://github.com/sait-wbdv/sait-wbdv.github.io/issues/8).

Select a representative from each group to present a summary of your findings to the rest of the class.

## 3. Performance Audits
Pushed to tomorrow.

## Clean up time!
- [Tomorrow]({% link _posts/2020-09-16-performance-copyright.md %})