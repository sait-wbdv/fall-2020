---
layout: post
title: Today - The Browser Triad, Long-form Text and Validation
categories: cpnt260
---

## HouseKeeping

## Lesson Prep
- Choose a print document (book, magazine, brochure, etc) in your immediate area that shows diverse examples of visual hierarchy.
- Choose an open-source web document (e.g. a Wikipedia page) explaining a favourite topic of your choice.
- Watch: [Why is CSS So Weird?](https://www.youtube.com/watch?v=aHUtMbJw8iA)
- Watch: [Introduction to Pair Programming](https://www.youtube.com/watch?v=vgkahOzFH2Q)
- Read: [HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
  - Read: [HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- Read: [CSS basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

## 1. The Browser Triad
### Learning Objectives
- Explain the difference between HTML, CSS, and JavaScript.
- Briefly summarize the history and development of HTML and CSS to their current incarnation.
- Define a tag, element and attribute.
- View the source of a web page.

### Terminology
<dl>
  <dt>Content Layer</dt>
  <dd>The HTML that defines the meaning and structure of web content.</dd>
  <dt>Presentation Layer</dt>
  <dd>The CSS (and supporting assets) that control the visual appearance of a web page. Examples: typography, layout, colour, etc.</dd>
  <dt>Behaviour Layer</dt>
  <dd>The Javascript that controls the interactive behaviour of a web page. In practice, the behaviour layer is responsible for everything the content and presentation layers <em>can't</em> do.</dd>
</dl>

### Activity: From Print to Web
You will be working in groups of 3 or 4 for this activity.

Identify common examples of visual hierarchy in the print document you selected as homework. 
- Does the pattern or technique have a name? 
- How do they apply to Web documents?
- Would this pattern or technique be implemented using HTML or CSS?

## 2. Long Form Text
### Learning Objectives
- Identify depreciated and obsolete elements from previous versions of HTML.
- Add appropriately marked-up text to a web page, including paragraphs and headings.
- Distinguish between block and inline elements.

See:
- [HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [inline vs block elements](https://stackoverflow.com/questions/9189810/css-display-inline-vs-inline-block)

### Activity: Your first HTML blog post
You will be working in pairs for this activity. 

Take either/both articles you have chosen and code them in HTML (using Codepen). Start with the following HTML tags:
- `h1`-`h3`: headings
- `p`: paragraphs
- `a`: anchor
- `strong`, `em`: bold and italicize
- `ul` and/or `ol`: unordered and ordered lists
- `img`: image as content

### Stretch Activities
Once you have the basics figure out, try some of these more advanced concepts:
- [Customize your list styling](https://css-tricks.com/almanac/properties/l/list-style/)
- [Style a blockquote with pseudo-elements](https://css-tricks.com/snippets/css/simple-and-nice-blockquote-styling/)
- [More cool things you can do with pseudo-elements](https://css-tricks.com/pseudo-element-roundup/)

## 3. Lab Time: Optimize and Validate
### Learning Objectives
- Define the rules for naming web pages.
- Add a file extension and save a web page.
- Validate a web page.

### Activity: Optimize and Validate
1. Clean up your code!
    - Are there any dead ends or failed experiments that should be removed?
    - Are there better solutions to the problems you solved today?
    - Which of your solutions could be re-used for future projects?
2. Migrate your final Codepen code into an HTML file (with external style sheet) in VS Code. See: [Applying CSS and JavaScript to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML#Applying_CSS_and_JavaScript_to_HTML)
    - Copy your Codepen CSS to an external stylesheet using a `link` element in the `head` of your HTML document.
    - Copy your Codepen HTML inside the `body` element of your HTML document. 
3. Validate your HTML file using the [W3C Markup Validation Service](https://validator.w3.org/)
4. Validate your external CSS file using the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

## Clean up time!
- [Homework for Monday]({{site.baseurl}}/tomorrow)