# tahrirumich.github.io


## Contributing

### Maintenance tasks
Add statements to statements page when released
1. create a file `/_posts/YYYY-MM-DD-slug.md`, where `slug` is a short name to be in the url
2. add the following header:
```
---
layout:     post
title:      "[long title]"
date:       [YYYY-MM-DD]
categories: statements
---
```
3. write the text of the post, using [markdown syntax](https://www.markdownguide.org/basic-syntax/); 
    images should be placed in `/assets/img` and linked as such;
    keep in mind that the first paragraph will be displayed as an excerpt
    on the statements page, so split the first paragraph if necessary.


Keep masthead images up to date
1. add the image in `/assets/img`
2. on the page, edit the url in the `style` attribute of the `header` element


Keep home page button up to date with an appropriate ask
1. on `index.html`, edit the `href` attribute of the
    `header > div > div > div > div > a` element and
    change the text; be sure to add `https://` to link
    to an external page
2. if necessary, copy-paste/delete additional `a` elements
    to add additional buttons; buttons will automatically
    be aligned in a row


### Technical info
The website is generated using [Jekyll](https://jekyllrb.com/). 
Shubh will add info about
- sitemap
- the default layout 
- the post layout
- testing locally
- pushing and deploying

Shubh will link to additional resources about
- jekyll
- html/css
- markdown
- github pages
- git


## TODOs

### Immediate content changes
- home page: change masthead image to encampment
- home page: some other thing to put as the big text on the image?
- about page: change masthead image (numbers super outdated)
- why divest? page: more political framing before the endowment guide;
    take from the more political aspects of the endowment guide
- statements: add additional missing statements


### Content changes requiring coalition discussion
- about page: change paragraphs to reflect current reality of TAHRIR
- contact: include way for people to plug in to our work


### Possible additions
- drop the charges campaign page
- press page, possibly with auto-generation; reference to press on home page
- gallery of images
- replace mastheads with image carousel
- change header style
