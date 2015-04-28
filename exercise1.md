# Exercise 1: Duplicate Google's layout.

![Google Home Page](./assets/exercise1/google-homepage.png "Google Home Page")

Google is known not only for their search wizardry. Their sparse design is a trademark of their products as well. This makes duplicating their homepage a great starting point for our series.

## What to do

1. Fork this repository and create a branch named exercise1. Create your index.html and css files and do your work in this branch. When you have something to show create a pull request from your fork's exercise1 branch back to the tmbritton/fems repository master branch and we'll review the code in the pull request diff.
2. Focus on clean code, semantic HTML, separation of content from presentation, and browser compatibility. 
3. The layout is provided as a .png in the assets folder. Open this in your image editor and use it to measure margins, pick colors, and everything else you need to do to build a website from a layout.

## Layout Techniques

- [Table-based layouts](http://www.ironspider.ca/webdesign102/tables4layout2.htm)- Seriously old-school. Don't do this.
- [Float-based layouts](http://alistapart.com/article/css-floats-101)- How things have been done for years. A solid choice for consistent browser support.
- [Flexbox layout](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)- The new hotness. Browser support looks pretty good these days: (http://caniuse.com/#search=flexbox). I'd say this is a solid choice to be very up-to-date with current trends. Bonus points if you use Flexbox and provide a float-based fallback if browser support isn't there.

## What you'll need

1. An image editor, like Photoshop, or something cheaper like [Pixelmator](http://www.pixelmator.com/ "Pixelmator"), or something free like [GIMP](http://gimp.org "GNU Image Manipulation Program").
2. A text editor like Github's [Atom](https://atom.io/), Adobe's [Brackets](http://brackets.io/), [Sublime Text](http://www.sublimetext.com/), or [Notepad++](http://notepad-plus-plus.org/).
3. Git, either using the command line (like a boss), or using [one of these GUIs](http://git-scm.com/downloads/guis).
4. A [GitHub](https://github.com/join) account.

## What you can use

1. HTML/CSS. Let's keep it up-to-date and use semantic HTML5.
2. A CSS pre-processor like [SASS](http://sass-lang.com/) or [LESS](http://lesscss.org/), if you wish.
3. Build tools like [Grunt](http://gruntjs.com/) or [Gulp](http://gulpjs.com/).
4. A CSS reset like [reset.css](http://meyerweb.com/eric/tools/css/reset/) or [normalize.css](http://necolas.github.io/normalize.css/)

Feel free to over-engineer your build tools as much as you want, but keep in mind that the browser speaks HTML, CSS, and Javascript. Pre-processors like SASS and LESS might fall out of favor and build tools like Grunt and Gulp are very flavor-of-the-week.

## What you can't use

1. A drag & drop editor like Dreamweaver or FrontPage.
2. A front-end framework like [Bootstrap](http://getbootstrap.com/) or [Zurb Foundation](http://foundation.zurb.com/). Let's walk before we run.
