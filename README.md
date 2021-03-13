# Homework
Made a working page more accessible and improved th semantics of the webpage, for better search engine optimization.
3.12.21 

## Installation
link to site

## Motivation
Changed the Title of the webpage to: Horiseon Social Solution Services, Inc.

Changed the div class = footer to just <footer> so that webpage scanners can rad the footer.

I noticed that change made the items in footer uncentered, I might go back and change that later for a better flow to the eye.

Changed <div class="header"> to just <header>.
Changed the <div> inside the header to <nav>.
I did both of those changes to make the webapge more SEO friendly, so that webpage scanners can find the header and navigation bar.


Since most of the font is ( font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;) on the page I put that at the top of the CSS under the * (which selects all elements) section so I could remove it from: .header, .benefits, .search-engine-optimization, .online-reputation-management, .social-media-marketing 

Added nav class to UL so it would recognize the CSS.

I moved the  "list-style-type: none;" to the .nav section, so that I could remove .nav ul.

Added <div id="search-engine-optimization">, so that the link would work, by knowing where to go on the page when the link is pushed.
  
 
## Screenshots
Include logo/demo screenshot etc.


## Features
Added a hover over the navigation links, so that when you hover over the links with your mouse, the links change color.

## Code Example
Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests
Describe and show how to run the tests with code examples.

## How to use?
If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.

## Contribute

Let people know how they can contribute into your project. A [contributing guideline](https://github.com/zulip/zulip-electron/blob/master/CONTRIBUTING.md) will be a big plus.

## Credits
https://ucsd.bootcampcontent.com/kittytaylor/ucsd-sd-fsf-pt-03-2021-u-c

