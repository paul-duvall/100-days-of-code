# 100 Days of Code - Round 3

## Day 1
### Monday 4 February 2019 

#### Review / Learn:
* Watched a couple of videos on brand design by Philip VanDusen, [Trends in Graphic Design](https://www.youtube.com/watch?v=uM7XB0oUP7k) and [9 Brand Design Elements Your Brand Must Have](https://www.youtube.com/watch?v=jB57Pc1W6Ys).
* Listened to Syntax podcasts about [defunct web technologies](https://syntax.fm/show/103/hasty-treat-where-are-they-now-part-2), broading my awareness of legacy technologies I might come across.

#### Project:
* Researched portfolios, making a list of interesting examples in Evernote for future reference
* Continued to work on design for front page on new portfolio site using Adobe XD

#### Thoughts:
At the start of today, I wasn't 100% set on starting up 100 days of code again but now it seems I'm going to! Past two efforts have only been successful on my own terms (since I have missed something like 15 days each time). I'm going to try and cut that down this time.

I'm really pleased with the design work I've done on my portfolio today, building an introduction, skills, projects and contact section for the front page. Made some radical changes to the layout and made a real effort to ensure colour scheme is consistent across all page elements.

#### Link(s) to work

[Portfolio 2 github files](https://github.com/paul-duvall/portfolio-2)

## Day 2
### Tuesday 5 February 2019 

#### Review / Learn:
* Listened to Syntax podcast about [CSS Layout](https://syntax.fm/show/104/css-layout), reviewing the basics including position, viewport units, responsive design. **Investigate**: viewport units vmin and vmax.
* Re-listened to Shoptalk podcast - [Dan Mall on Building a Portfolio](https://shoptalkshow.com/episodes/329-dan-mall-building-portfolio/)
* Learnt how to use SkyFonts to install Google Fonts on to desktop; installed fonts for portfolio project
* Read about web font sizing guidelines [here](https://learnui.design/blog/mobile-desktop-website-font-size-guidelines.html) on the Learn UI Design Blog.
* Started the Advanced CSS and Sass course on Udemy, beginning the first project, a website called Natours. Worked on creating the header section, which involved creating a background with an image, a gradient overlay and a 'wedge' effect with an angled side. Centring the title achieved using absolute positioning, defining top and left properties using percentages and then using transform: translate(-50%, -50%).

#### Project:
* Finished some minor details of portfolio front page design, tweaking colours. 
* Created complete front page design of portfolio for smaller viewports.
* Updated all fonts to Roboto / Montserrat
* Started work on portfolio projects page design

#### Thoughts:
Made some good progress on portfolio design - I was pleased that I got the fonts sorted out and some more fine-tuning of colours. I really want to push on with this and get the design finished as soon as humanly possible. Next, I will finish the projects page (including creating small-viewport version) and hopefully push on to creating about, skills and contact pages shortly. These should be more straight-forward.

So far, the Advanced CSS and Sass course is promising; the tutor goes into a lot of detail and explains all decisions fully. I would really like to push on with this quickly so I can impliment Sass in my upcoming cafe website project. This is the reason why I have prioritised this course over the React course, which I was loving, but it would be really beneficial to have a new technology I can integrate into a live project.

#### Link(s) to work

[Portfolio 2 github files](https://github.com/paul-duvall/portfolio-2)
[Natours](https://github.com/paul-duvall/Natours)

## Day 3
### Wednesday 6 February 2019 

#### Review / Learn:
* Listened to Syntax podcast about [Tidying up code](https://syntax.fm/show/111/hasty-treat-tidying-up-code); suggestions included removing commented-out code, removing unused CSS (apparently there is a Chrome dev tool that helps with that), organising code, using code formatted such as Prettier or ESLint
* Listen to CodeNewbie podcast [How do I level up?(Ben Orenstein)](https://www.codenewbie.org/podcast/how-do-i-level-up)

#### Project:
* Completed design of projects page and created mobile version
* Created design of about page, including larger and smaller viewports
* Created design of skills page, including larger and smaller viewports 

#### Thoughts:
Pushed on through with the portfolio redesign; really pleased with the results. Only the contact page to go and then I'll be ready to start code. Will get through as much of the advanced CSS / Sass course tomorrow - on reflection and discussing with a friend, have decided I should be implementing Sass in my portfolio. Also need to do a review of CSS Grid so I can use that as much as possible for the layout.

#### Link(s) to work
[Portfolio 2 github files](https://github.com/paul-duvall/portfolio-2)


## Day 4
### Thursday 7 February 2019 

#### Review / Learn:
* Continued the Advanced CSS and Sass course on Udemy, working on the first project, a website called Natours. Added in 'move-in' animation on title and subtitle text using keyframes (animation set using percentages with transform and opacity). Involved using the following CSS properties on the class of the item being animated - animation-name, animation-duration, animation-timing-function (can all be set using the shorthand animation property).
* Added a button with subtle hover over and active animations (used pseudo-classes - link, visited, hover and active).
* Used the CSS after selector to add an interesting hover effect and animated the button using another keyframe.
* Watched short overview video highlighting what the tutor considers the '3 pillars of web development' - responsive design, writing maintainable and scalable code and web performance:

![Three pillars of web development](https://raw.githubusercontent.com/paul-duvall/website_images/master/sass-course-three-pillars.jpg)

* Watched short overview of what happens to CSS when a webpage is loaded:

![What happens to CSS when we load a webpage?](https://raw.githubusercontent.com/paul-duvall/website_images/master/sass-course-loading-webpage.jpg)

* Aaaaaaand.....watched a video about the cascade and issues of specificity. Main take-home points were to only use !important as a last resort, use IDs to be super-specific, whilst order of selectors is an important consideration, it is better to rely on specificity.

#### Thoughts:
Worked today so less coding done. Pushed on with the Advanced CSS and Sass course. Need to get through at least the first three sections, if not sections 4 / 5 as well. If I could do that (along with finishing final bit of design + researching cafe websites) over the next three days, I'd be very pleased.

#### Link(s) to work
[Natours](https://github.com/paul-duvall/Natours)


## Day 5
### Friday 8 February 2019 

#### Review / Learn:
* Continued the Advanced CSS and Sass course on Udemy, watching tutorials on how CSS values are processed when a page is rendered and inheritance of CSS properties.
* Learnt about the practicalities of converting px to rem and an effective workflow for managing this process. Essentially you want the font-size set to 10px on the html tag but this cannot be done as it overrides user settings meaning the webpage would become unreadable for people who have to set their font size larger. The solution is to set it as a percentage to 62.5% (10/16) - equivalent to 10px. Once this is done, 1rem is the same as 10px, so 2.3rem is 23px, etc.
* Reviewed box model, different box types (inline, block-level and inline-block) and positioning schemes (normal flow, floats and absolute positioning).
* Watch tutorial video introducing BEM and the 7-1 pattern for folder organisation

#### Thoughts:
Pushed on through some less-than-thrilling CSS theory tutorials, much of it review but still good to get a fuller picture. Implimented BEM in the course project. Sass tomorrow.

#### Link(s) to work
[Natours](https://github.com/paul-duvall/Natours)


## Day 6
### Saturday 9 February 2019 

#### Review / Learn:
* Completed introductory Sass tutorial videos, learning about variables, nesting, mixins and extends
* Used Yarn to add Sass to tutorial project, setting up a script in the package.json to compile
* Updated existing course project CSS code into SCSS, implimenting variables and nesting
* Watched tutorial video on basic responsive design principles:

![Basic responsive design principles](https://raw.githubusercontent.com/paul-duvall/website_images/master/sass-course-responsive-design-principles.jpg)

* Read an article, [The Great Divide](https://css-tricks.com/the-great-divide/) which outlines how 'front-end developer' is increasingly not a descriptive enough term as it seems to cover to broad camps which do not necessarily overlap - those who heavily use JavaScript for front-end work and those who are primarily interested in more UX-focused areas (including CSS, HTML, accessability, etc.).

#### Link(s) to work
[Natours](https://github.com/paul-duvall/Natours)


## Day 7
### Sunday 10 February 2019 

#### Review / Learn:
* Rewatched first part of Wes Bos' [CSS Grid](https://cssgrid.io/) tutorial series.

#### Project:
* Set up dev environment, initialising with package.json and installing Sass
* Set up folder structure and some initial Sass folders and partials.
* Set up index.html, linked in CSS and wrote markup for the front page header section
* Used BEM naming convention for classes
* Started to write SCSS for header elements
* Imported Google Fonts and set up variables for the main colours

#### Thoughts:
I'm very keen to impliment CSS Grid in Portfolio 2, since I've never used it in a major project before, despite having learnt it before. This is why I having put some time in today to review this. 

Very pleased to have begun coding work on Portfolio 2. Happy that the process of setting it up with Sass went smoothly and appears to be running correctly!

#### Link(s) to work
[Portfolio 2 github files](https://github.com/paul-duvall/portfolio-2)


## Day 
### Tuesday 5 February 2019 

#### Review / Learn:
* 

#### Project:
* 

#### Thoughts:
Thoughts here

#### Link(s) to work
Links here
