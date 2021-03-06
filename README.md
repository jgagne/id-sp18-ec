`ART3402`

# Interactive Design

- Wednesday, 1:25–4:05 p.m., ADM 535
- Instructor: Justin Gagne
- Email: `gagnej@emmanuel.edu`
- Office Hours: TBA
- Class Workspace on [Slack](https://id-sp18-ec.slack.com) — Where Work Happens™
- Work: Design lead for [Gymnasium](https://thegymnasium.com) at [Aquent](https://aquent.com) in Boston, MA.

- - -

- [Course Description](#course-description)

- - -

- [Schedule](#schedule)
- [Tools](#tools)
- [Books](#books)
- [Resources](#resources)

- - -

- [Author](#author)
- [License](#license)


## Course Description

This advanced course introduces students to the concepts and techniques of interactive design through industry standard web development. Through focused projects, students will explore interactive paradigms of user experience, information architecture, and navigation design with an emphasis on organization and usability. Current and future directions of interactive design will be discussed with a focus on advanced HTML, CSS, responsive design, frameworks, and workflows.

## Schedule

- - -

### Week 1

`January 17`

 - *First Day of Class*

### Content Markup

> 90 percent of design is typography. And the other 90 percent is whitespace.
>
>—[Jeffrey Zeldman](https://www.zeldman.com), designer, writer, and publisher

> Good design and good markup provide structure to content. Good markup is a fundamental part of good design: beautiful on the inside, beautiful on the outside.
>
>—[Frank Chimero](https://frankchimero.com), designer, illustrator, and writer

#### Lectures

- [Resilience](https://vimeo.com/166140718) by [Jeremy Keith](https://adactio.com) ≈ 46 min `video`
- [Do We Need to Write Markup](https://vimeo.com/109912256) by [Nathan Ford](http://artequalswork.com) ≈ 46 min `video`

#### Hello World

- [The World Wide Web project](http://info.cern.ch/hypertext/WWW/TheProject.html)
- [This is a web page.](https://justinjackson.ca/words.html)
- [This is a motherfucking website.](http://motherfuckingwebsite.com)

#### Readings

- [Designers vs Coding](https://web.archive.org/web/20111201205345/http://blog.frankchimero.com/post/9594863189) by [Frank Chimero](https://frankchimero.com)
- [Resilient web design](https://resilientwebdesign.com) by [Jeremy Keith](https://adactio.com) *Introduction; (Chapter 1) Foundations*
- [The Benefits of Semantic HTML](https://talum.github.io/blog/2015/12/21/the-benefits-of-semantic-html/) by [Tracy Lum](http://talum.github.io)

#### Warm-Up

##### Editing Soft Copy

Text, format, and markup (text-level semantics).

- [View source](http://thinkingwithtype.com/extras/#editing-soft-copy)
- [Raw text](lessons/01-content-markup/warm-up/editing-soft-copy/editing-soft-copy.txt)
- [Visual guide](lessons/01-content-markup/warm-up/editing-soft-copy/lupton-editing-soft-copy.png)
- See [HTML Semantics](http://marksheet.io/html-semantics.html); see also [HTML Resources](#html)

- - -

### Week 2

`January 24`

- *No Class; Work from Home Day*

#### Readings

- [MarkSheet: An overview of how the Web works](http://marksheet.io/introduction.html) (1.1–1.3)
- [A Brief History of Markup](https://html5forwebdesigners.com/history/)
- [The Design of HTML5](https://html5forwebdesigners.com/design/)
- [HTML & CSS is Hard: Introduction](https://internetingishard.com/html-and-css/introduction/)
- [HTML & CSS is Hard: Basic Web Pages](https://internetingishard.com/html-and-css/basic-web-pages/)
- [Semantics](https://html5forwebdesigners.com/semantics/)
- [The i, b, em, & strong elements](http://html5doctor.com/i-b-em-strong-element/)

- - -

### Week 3

`January 31`

#### Warm-Up

##### Editing Soft Copy

Text, format, and markup (text-level semantics).

- [Work in progress files](lessons/01-content-markup/warm-up/editing-soft-copy/)
  - [HTML Preview](https://htmlpreview.github.io/?https://github.com/jgagne/id-sp18-ec/blob/master/lessons/01-content-markup/warm-up/editing-soft-copy/index.html)
- See comments in HTML and CSS files for resources and notes


#### Readings

- [MarkSheet: HTML Basic](https://marksheet.io/html-basics.html) (2.1–2.7)
- [MarkSheet: HTML Text](https://marksheet.io/html-text.html) (3.2)
- [MarkSheet: Inline semantics](https://marksheet.io/html-inline-semantics.html) (3.3)
- [HTML lists](https://webplatform.github.io/docs/guides/html_lists/)
- [Graphic Design as a Liberal Art](http://jarrettfuller.com/projects/liberalart)

#### Project

##### Recipe

Select a cooking/baking recipe to share *(and make)*.

- Markup the content first with [semantic HTML](http://w3c.github.io/html-reference/elements-by-function.html).
  - Consider what each content chunk and phrase is and about
- Use proper [typographical characters](http://htmlarrows.com) for numbers, punctuation, symbols, etc.
- Photograph the final product
- Develop the look and feel of your content
  - Create a [style tile](https://alistapart.com/article/style-tiles-and-how-they-work)
    - Develop a color palette based on the colors your recipe
    - Serif or sans-serif text, or [both](https://www.cssfontstack.com)? (≥90% Win/Mac)

###### Inspect

- Quick Start: [Starbucks Coffee Bean Peanut Brittle](https://news.starbucks.com/news/starbucks-coffee-bean-peanut-brittle-recipe)
- Furthermore: [A Coffee Ritual, Baked Not Brewed](https://1912pike.com/a-coffee-ritual-baked-not-brewed/)

- - -

### Week 4

`February 7`

#### Homework

##### Recipe

Create a [style tile](https://alistapart.com/article/style-tiles-and-how-they-work) (for the general look and feel) and, then layout two comps, one for small screens (mobile first) and the other for wider screens (tablet–desktop).

- Make comps by hand on paper (as a [paper prototype](https://alistapart.com/article/paperprototyping)) or use a digital design tools like Illustrator, InDesign, Sketch, etc. (*Please*, [skip Photoshop](https://signalvnoise.com/posts/1061-why-we-skip-photoshop).)
- Be ready to show style tile(s) and comps for the next class as a print-out or an on-screen PDF

###### Separation of Content and Style

- Markup content with [semantic HTML](http://w3c.github.io/html-reference/elements-by-function.html)
- Add an image and write a descriptive [alternative text](https://axesslab.com/alt-texts/)
  - For example: `<img alt="An orange cat is sleeping." src="img/orange-tabby.jpg">`
- Use an [external stylesheet](https://learn.shayhowe.com/html-css/building-your-first-web-page/#referencing-css)
  - For example: `<link rel="stylesheet" href="css/main.css">`

#### Comping

- [Why we skip Photoshop](https://signalvnoise.com/posts/1061-why-we-skip-photoshop)
- [Paper Prototyping](https://alistapart.com/article/paperprototyping)
- [Printable Grids for Design Wireframing](http://sneakpeekit.com) `templates`

#### Readings

- [Separation: The Web Designer’s Dilemma](https://alistapart.com/article/separationdilemma)
- [Responsive questions](https://adactio.com/journal/5351)
- [A brief history of CSS until 2016](https://www.w3.org/Style/CSS20/history.html)
- [CSS Selectors](https://internetingishard.com/html-and-css/css-selectors/)
- [CSS Box Model](https://internetingishard.com/html-and-css/css-box-model/)
- [Web Typography](https://internetingishard.com/html-and-css/web-typography/)

#### References

- [Obsolete and deprecated elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Obsolete_and_deprecated_elements)
- [Organizing Data with Tables](https://learn.shayhowe.com/html-css/organizing-data-with-tables/) (*Please*, use an `ol`, `ul`, or `dl` instead of a `table`.)
- [Alt text is part of your site’s content](http://centercentre.com/blog/2016-06-30-alt-text-is-part-of-your-sites-content)
- [Alt-texts: The Ultimate Guide](https://axesslab.com/alt-texts/)
- [Why you should say HTML classes, CSS class selectors, or CSS pseudo-classes, but not CSS classes](http://tantek.com/2012/353/b1/why-html-classes-css-class-selectors)
- [CSS Reference](https://cssreference.io)
- [CSS Cheat Sheet](https://adam-marsden.co.uk/css-cheat-sheet)

- - -

### Week 5

`February 14`

- *Valentine’s Day*

> Content precedes design. Design in the absence of content is not design, it’s decoration.
>
> —[Jeffrey Zeldman](https://studio.zeldman.com), designer, writer, and publisher

> The Web is 90% text, so let’s style it first.
>
> —[Jeremy Thomas](http://marksheet.io/css-text.html), CSS guru and author of [MarkSheet](http://marksheet.io)

> Choosing a typeface is not typography.
>
> [iA](https://ia.net/topics/the-web-is-all-about-typography-period/), digital design and product agency

#### Homework

##### Recipe

Focus on content first and mobile first layout using `padding`, `border`, and `margin`, accessible text and background colors, use of web safe fonts, and basic typographical adjustments. *Don’t worry about layout for wider width screens — mobile first and friendly.*

#### Lecture

Type, Color, and Layout

- [The Art of Web Design](https://www.youtube.com/watch?v=3iVVM_DgWY4) Off Book series by PBS `video`
- [Typography](https://www.youtube.com/watch?v=eKKDL6lekmA) Off Book series by PBS `video`
- [Jan Tschichold](https://www.youtube.com/watch?v=mm-K8MGDpqU) by Josh Eiten `video`

#### Readings

- [Everything Easy is Hard Again](https://frankchimero.com/writing/everything-easy-is-hard-again/)
- [Responsive Web Design](https://alistapart.com/article/responsive-web-design)
- [How Floating Works](https://bitsofco.de/how-floating-works/)
- [What’s the Deal with Collapsible Margins?](https://bitsofco.de/collapsible-margins/)

#### References

- [CSS Font Stack](https://www.cssfontstack.com) Web safe font families
- [Font Family Reunion](http://fontfamily.io) Compatibility tables for default local fonts
- [Webfont Test](http://webfont-test.com) Test and analyze your favorite web fonts
- [Unitless line-heights](http://meyerweb.com/eric/thoughts/2006/02/08/unitless-line-heights/)
- [Butterick’s Practical Typography](https://practicaltypography.com)
- [Web Safe Colors](http://websafecolors.info)
- [Accessible Colors](http://accessible-colors.com) Test accessible web color combinations
- [IBM Type](https://ibm.github.io/type/)
- [IBM Typography Guidelines](http://www.carbondesignsystem.com/style/typography/overview)

- - -

### Week 6

`February 21`

#### Readings

- [The (Mostly) Complete History of Layout on the Web Part 1: Liquid Cool](https://thehistoryoftheweb.com/mostly-complete-history-layout-web-part-1-liquid-cool/)
- [The (Mostly) Complete History of Layout on the Web Part 1: Responsive Design](https://thehistoryoftheweb.com/mostly-complete-history-flexible-web-layout-part-2-responsive-design/)

- - -

### Week 7

`February 28`

#### Demo

- [Web Fonts Demo](https://github.com/jgagne/web-fonts-preload/) Using `@font-face` and `preload` for loading performant web fonts

#### Project

##### Reading Redesign

Select and redesign a previously assigned reading from the [course syllabus](#schedule) as a single-page website focusing on readable typography, accessible colors, and flexible images with a responsive layout for various screen sizes — small (mobile first) to wide(r) (tablet, laptop, and desktop).

- - -

### Week 8

`March 7`

- **No Class**

- - -

### Week 9

`March 14`

- - -

### Week 10

`March 21`

#### Lecture

HTML and CSS frameworks — web design and development made faster and easier.

- [Bootstrap 4](http://blog.getbootstrap.com/2018/01/18/bootstrap-4/)
- [Get Started with Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/) Build responsive, mobile-first projects on the web with the world’s most popular front-end component library
- [Grid Layout in Bootstrap 3](https://thegymnasium.com/courses/GYM/003/0/about) Outdated, but the basics to get started are not `video`
- [Learn Bootstrap 4 in 30 minutes by building a landing page website](https://medium.freecodecamp.org/learn-bootstrap-4-in-30-minute-by-building-a-landing-page-website-guide-for-beginners-f64e03833f33)

#### Homework

##### Reading Redesign

Select and redesign a previously assigned reading from the [course syllabus](#schedule) as a single-page website focusing on readable typography, accessible colors, and flexible images with a responsive layout for various screen sizes — small (mobile first) to wide(r) (tablet, laptop, and desktop).

- Begin with sketches of the article redesign — mobile first, then for a wider screen
- Use Bootstrap’s stylesheet, `bootstrap.css`, as the foundation for layout
- Use a separate stylesheet, `main.css`, for custom typography and colors

#### Readings

- [Building Twitter Bootstrap](https://alistapart.com/article/building-twitter-bootstrap)
- [Web Typography & Layout: Past, Present, and Future](https://alistapart.com/event/web-typography-layout-past-present-future)
- [A DIY Web Accessibility Blueprint](https://alistapart.com/article/diy-web-accessibility-blueprint)

#### References

- [Normalize.css](https://necolas.github.io/normalize.css/) A modern, HTML5-ready alternative to CSS resets
- [HTML5 Boilerplate](https://html5boilerplate.com) The web’s most popular front-end template

- - -

### Week 11

`March 28`

#### Demo

- [Responsive Images Demo](https://github.com/jgagne/img-srcset-sizes) Using `src`, `srcset` with `w` descriptors, and `sizes`

#### Tutorial

- [Learn Bootstrap 4 for free](scrimba.com/g/gbootstrap4)

- - -

### Week 12

`April 4`

#### Demo

- Bootstrap Comp Demo (Comping basic layout using Bootstrap as a foundational framework)
  - [View Source](https://github.com/jgagne/id-sp18-ec/tree/master/lessons/02-framework/warm-up/bootstrap-comp)
  - [Download ZIP](https://github.com/jgagne/id-sp18-ec/tree/master/lessons/02-framework/warm-up/bootstrap-comp.zip)

- - -

### Week 13

`April 11`

> Simplicity is about subtracting the obvious and adding the meaningful.
>
> —[John Maeda](https://www.wired.com/2017/03/john-maeda-want-survive-design-better-learn-code/), designer and technologist

#### Project

##### Single Serving

Design a modern responsive single serving website — a single-page with a single-theme based on self generated content; focusing on type, color, image, and layout built using Bootstrap as a foundation.

#### References

- [Single Serving Sites](http://kottke.org/08/02/single-serving-sites)
- [Purple, Obama, and Single Serving Websites](http://thehistoryoftheweb.com/purple-obama-single-serving-websites/)
- [How to Order Eggs](http://hansonwu.com/howtoordereggs)
- [Books on Graphic Design (and Typography)](https://booksongraphicdesign.com)

#### Homework

#### Recipe To-Dos

- [Recipe To-Dos](https://gist.github.com/jgagne/5bbeeee70f707a0def34a9e8be26b27a) `#tasklist`
 - Copy and paste tasklist (click the "Raw" button, then copy and paste) in your recipe repo as a new "To-Dos" issue and start checking each to-do off

- - -

### Week 14

`April 18`

#### To-Dos

Copy and paste each tasklist (click the "Raw" button, then copy and paste) in *your* repo as a new "To-Dos" issue and start checking each to-do off.

- [Recipe To-Dos](https://gist.github.com/jgagne/5bbeeee70f707a0def34a9e8be26b27a) `#tasklist`
  - **Updated** Code, Design, and Extra Extra to-dos
- [Redesign To-Dos](https://gist.github.com/jgagne/5268a361baabfd701f457e29c532a6af) `#tasklist`

- - -

### Week 15

`April 25`

- *Last Day of Class*

#### Break Bread

Bake, cook, or prepare your recipe and bring to the last class to share for potlock lunch. `#optional`

#### Critique

- Recipe
- Redesign
- Single-Serving

#### To-Dos

Copy and paste each tasklist (click the "Raw" button, then copy and paste) in *your* repo as a new "To-Dos" issue and start checking each to-do off.

- [Recipe To-Dos](https://gist.github.com/jgagne/5bbeeee70f707a0def34a9e8be26b27a) `#tasklist`
  - **Updated** Code, Design, and Extra Extra to-dos
- [Redesign To-Dos](https://gist.github.com/jgagne/5268a361baabfd701f457e29c532a6af) `#tasklist`
- [Single-Serving To-Dos](https://gist.github.com/jgagne/957090af3ee95cd26dcb75a361dae833) `#tasklist`

#### Grading

- Any updates to project repos must be done, and please notify me via Slack, by the end of day on Monday, May 7 for final grading. *(Final grades are due Wednesday, May 9.)*

#### Course Eval

[Interactive Design (01)-ART*3402*01](https://eclearn.emmanuel.edu/courses/2211299/files/116610574?module_item_id=33140663) `#comments`

## Tools

### Text Editors

Pick a *free* flavor…

- [Atom](https://atom.io) (GitHub)
- [BBEdit](http://www.barebones.com/products/bbedit/) (Mac only [Made in Massachusetts])
- [Brackets](http://brackets.io) (Adobe)
- [Visual Code Studio](https://code.visualstudio.com) (Microsoft)
- [JS Bin](http://jsbin.com) (web-based)
- [HTML Builder Prototype](http://dev.artequalswork.com/builder/) (web-based)

### Developer Tools

HTML and CSS validators, and more…

- [W3C Developer Tools](https://www.w3.org/developers/tools/)

### Digital Design

- [Illustrator](https://www.adobe.com/products/illustrator.html)
- [Sketch](https://sketchapp.com/store/edu/) (Mac only; 50% off for students)
- [Inkscape](https://inkscape.org)

### Image Optimization

- [ImageOptim](https://imageoptim.com/mac) (Mac only)
- [SVGOMG!](https://jakearchibald.github.io/svgomg/)

## Books

Nice-to-have, but *not* required.

- [HTML5 for Web Designers](https://abookapart.com/products/html5-for-web-designers) by Jeremy Keith (Second Edition)
- [Responsive Web Design](https://abookapart.com/products/responsive-web-design) by Ethan Marcotte (Second Edition)
- [Designing with Web Standards](https://www.amazon.com/Designing-Web-Standards-Jeffrey-Zeldman/dp/0321616952) by Jeffrey Zeldman (Third Edition)
- [The Art and Science of Web Design](https://www.amazon.com/Art-Science-Web-Design/dp/0789723700) by Jeffrey Veen *(Oldie, but goodie.)*

## Resources

### HTML

- [MarkSheet](http://marksheet.io) A free HTML & CSS tutorial
- [HTML5 Element Index](http://html5doctor.com/#glossary) Helping you implement HTML5 today
- [HTML Elements Organized by Function](http://w3c.github.io/html-reference/elements-by-function.html)
- [HTML Reference](http://htmlreference.io) A free guide to HTML
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web) Web technology for developers
- [HTML5 For Web Designers](https://html5forwebdesigners.com) by Jeremy Keith

### Misc

- [HTML Arrows](http://htmlarrows.com) A delightful reference for HTML Symbols, Entities and ASCII Character Codes
- [TitleCap](http://titlecapitalization.com) Automatically Capitalize Your Title

- - -

## Author

A course developed by Justin Gagne.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png"></a>

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
