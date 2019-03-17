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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

## Day 7
### Sunday 10 February 2019 

#### Review / Learn:
* Rewatched first part of Wes Bos' [CSS Grid](https://cssgrid.io/) tutorial series.
* Wrote and published blog artice about #100DaysOfCode round 2

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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

## Day 8
### Monday 11 February 2019 

#### Project:
* Started working on the layout of the header section and adding styling to name text
* Begun compiling links to insiprational pages on Dribble for Lemon Tree Cafe website

#### Thoughts:
Portfolio header starting to look as it should; annoyingly, it seems that it is not entirely straight-forward to add a box-shadow to a shape generated using clip-path. That may take a bit of research. Buttons need styling and I need to work out a way to put a blue mask over the image of me, but otherwise the full-screen version is basically there. I think I will try and do a bit of the CSS / Sass course tomorrow but I've high hopes that I will be able to get a workable version of the full-screen front-page done by the end of this week (minus navigation burger).

#### Link(s) to work
[Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

## Day 9 / 10
### Tuesday / Wednesday 12 / 13 February 2019 

#### Review / Learn:
* Did some reading about Git / Github.
* Started Udacity Git course
* leart some Git Bash commands, including cd .. (need to leave a space between the d and the dots!), diff to compare to files and code to run visual studio code! Also made a directory and moved a file across to new directory in Git Bash.

#### Thoughts:
I read an article - [Standing out from the crowd of Junior Developers part 1](https://www.byteconf.com/blog/standing-out-from-the-crowd-of-junior-developers-part-1) - which suggested using a more profession Git workflow on personal projects to effectively demonstrate this skill:

> You can achieve a huge amount with Git using around only 5-6 commands. In your projects, you should aim to make use of all of these and the features they provide. Adding a navigation bar to the top of your page? Raise an issue, check out a branch, make your changes and submit that pull request! Making your projects as close to real life as possible makes it much easier for an employer to see you fitting in with how they work. It also shows them you can reason about planning a project, breaking it down and executing it in a logical order,  rather than with no plan at all.

Yes, I've already spent some learning time on Git but I never integrated it into my workflow beyond commiting my projects directly to the master once I had finished working on then for a day. Whilst this is a good start, I definitely need to be more 'work-place' ready with my use of Git / Github. So the time spent on this course is definitely well spent and I will hopefully be able to put into practice what I learn straight away in my portfolio project. The course has been largely theory so far but I'm excited by the structure - it reminds me of the Harvard CS50 course, which I did part of(!), in that there are screens of instructions and they are clearly keen to make the course as interactive as possible. So far, I like it. Hopefully it will work through the majority of what I need to know in order to start to use Git more effectively on personal projects.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

## Day 11 / 12
### Thursday / Saturday 14 / 16 February 2019 

#### Review / Learn:
* Started Udacity course on Git and Github, learning some history of version control and how to use the following commands: 
    - git log - shows a history of all commits
    - git log -n 3 - specifies the number of commits to show
    - git diff commit1 commit2 - compares two different commits
    - git diff with no commits compares the working directory and the staging area
    - git diff --staged compares the staging area and the most recent commit
    - git checkout - switches to a different commit or branch
    - git clone - creates a copy of a respository
    - git init - initialises a new repository
    - git status - shows the state of the working directory
    - git add - adds chosen file to staging area
    - git commit - commits all files in staging area as new commit (opens code editor to write message)
    
 [Click here](http://udacity.github.io/git-styleguide/) to read the Udacity Git Commit style guide.
 [Handy Git cheatsheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf)
    
* Learnt how to complete these tasks from the command line. 
* learnt that ls -a lists directory contents along with any hidden files, including git directory

#### Thoughts:
Yes, I haven't done any work on projects / progressing in my Sass course, but I have really learnt a substantial amount about git, which seems vital if I'm going to be ready for the workplace. The important thing now is to impliment what I've learnt straight away in a project. One of the key takeaways here is the importance of having a commit for each self-contained change, which is rather different to what I've been doing (doing a big commit at the end of the day, lumping everything in together).

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 13
### Sunday 17 February 2019 

#### Review / Learn:
* Continued with git learning, getting some practice making changes to a file, then adding to staging and then making a commit.
* Learnt about branches, which allow changes to be made without affecting the main version ('master' branch), allowing you to try out experimental features or make new versions. Commands include:
        * git branch - lists the branches that exist within the current repository 
            (The branch that has a star next to it is the one currently checkout out.)
        * git branch new-branch - creates a new branch with the name specified in the argument
        * git branch -d branch-name - deletes a branch 
            (Note that doing this after merging branches will only delete the branch name, not the commits associated with that branch.)
        * git checkout new-branch - checks out the branch specified in the argument
        * git log --graph --oneline branch1 branch2 - generates a graph showing the relationship between the commits of two branches
        * git show commit-id - shows the changes in a commit compared to its parent
* Considered parent branches / commits, unreachable commits
* If you have checked out an older commit, you can make changes without affecting the current commit / branch. These changes would disappear if you returned to the master or moved to another commit. A new branch from this point can be created using this shorthand:
        * git checkout -b new-branch-name - creates the new branch and the commit at the same time
* How to merge files, including how automatic merging works and how to deal with conflicts
        * git merge branch1 branch2
* Using Git with Github - adding a remote to a local repository
        * git remote - displays remotes on a respository
        * git remote add origin url
            (Origin is the name of the remote - this is a conventional name for the primary remote.)
            (The URL is provided when a repository is set up on Github.)
        * git push target-rep local-rep - pushes changes from the local master to the target repository on Github
        * git pull target-rep local-rep - pulls changes from the target repository on Github to the local master
        * forking
* Listened to the [The Changelog]() podcast on ethics in the technology industry.
        

#### Thoughts:
Learnt a lot today. Lost it a bit towards the end - overloaded on info somewhat. Feel like I'm getting behind on portfolio project; just had to remind myself how vital these git-related skills are to working within the web dev industry.

#### Link(s) to work
[Udacity reflections](https://github.com/paul-duvall/udacity-reflections)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 14
### Monday 18 February 2019 

#### Project:
* Created new local repository, cloning from Github, added node_modules back in
* Made two small changes using new workflow (log issues, new branch, commits, push to origin on Github, create pull request, merge and mark issues as closed).
* Opened new branch to start work on sorting out layout. Decided to change to mobile first; ripped layout apart and started to rebuild

#### Thoughts:
Three days ago I absolutely could not have used git to the degree I can now and it feels pretty great to have a more professional workflow for working on my projects.

#### Link(s) to work
[Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
[Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 15
### Tuesday 19 February 2019 

#### Review / Learn:
* Started reading Steve Krug's Don't Make Me Think, a book about web usability. Have read the section on guiding principles, including how the web is used by people (scanning, settling for the first decent option - satisficing), designing for scanning, the importance of giving users 'mindless choices' and not getting them to think too much ('Don't make me think!').
* Read [article](https://blog.logrocket.com/the-only-reason-your-css-fails-8e4388d562af) on core principles of CSS - block formatting context, box model, stacking context, and the cascade (particularly specificity).

#### Project:
* Finished changes to make the header section of the front page mobile first

#### Thoughts:
I initially thought that I would start with the larger-viewport version but realised that the mobile version, where everything is essentially stacked on top of each other, is much simpler and, therefore, a more logical place to start from. I now feel more confident that I'll be able to reintroduce the CSS grid required for the more sophisticated layout needed for larger viewports using media queries.

#### Link(s) to work
[Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
[Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 16
### Wednesday 20 February 2019 

#### Review / Learn:
* Continued reading Don't Make Me Think - a chapter about minimising unnessessary text content and the importance of good navigation.
* Continued Advanced CSS / Sass course, making the 'Natours' project: 
    * Developed a custom grid using floats, how the attribute selector works (allows you to select an element or elements with a particular attribute, e.g. \[alt] would grab all elements with an alt attribute. \[class^="col-"] grabs all that start with "col-". Replacing ^ with * changes it to "contains". Replacing ^ with $ changes it to "ends with".
    * Also involved a lot of work with calc() and using the :not pseudo-class
    * Working on the next section, we briefly covered the idea of utility classes, which led me to [this](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/) article
    * Used a combination of background-clip:text, a background image with a linear gradient and color:transparent to create a header coloured with a gradient

#### Project:
* Finished integrating grid layout for larger viewports for header section of main page
* Add html and CSS for 'hello there' section of main page

#### Thoughts:
Whilst styling the header section, it became clear that I couldn't get bogged down in small issues I come across. As such, I created a decent working version, and logged a number of small layout / design issues in Github. Whilst coding the 'hello there' section, I quickly came across two significant design issues that seem like they will require a fair amount of tinkering; the irregular shape of the div and the gradient colouring of the owl icon. It may be that the form is more trouble than it is worth. Either way, both have been logged as issues so I can push forward towards getting a workable version of the page.

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)
* [Natours github repository](https://github.com/paul-duvall/Natours)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 17
### Thursday 21 February 2019 

#### Project:
* implemented html and css for home page skills section, fully responsive

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 18
### Friday 22 February 2019 

#### Review / Learn:
* listened to a [podcast](https://www.codenewbie.org/podcast/what-are-progressive-web-apps) on progressive web apps
* listened to a [podcast](https://syntax.fm/show/120/gatsby-vs-next) on Gatsby and Next

#### Project:
* implimented html and css for home page projects section, not yet responsive

#### Thoughts:
For my projects section, I decided to impliment a nice animation effect that I'd learnt in a tutorial - [codepen here](https://codepen.io/duvallpj/pen/roWvLw). I'm pleased I managed to integrate this and with the final effect. Makes this part of the page feel more dynamic / vibrant. Also added in a link button for each project, which wasn't in the design (but it was always my intent to have a project page for each project).

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 19
### Saturday 23 February 2019 

#### Review / Learn:
* Continued with Natours project in the Advanced CSS and Sass course, finishing the build of the about section. Created a new button style with a nice animation. Integrated a new variable for a standard font size, which is used in a number of places.
* For the same project, built an image composition section with three over-lapping images. When hovered, an image comes to the front and the other two images scale and become slightly smaller.
* For the same project, built a 'features' section built around a card component. Skewed background using transform (required the contents to be skewed in the opposite direction, achieved using the direct child selector). 

#### Project:
* Resolved an issue with the images in the skills cards not being centered correctly and merged with master on github

#### Thoughts:
Made some good progress on Natours, coming across a couple of ideas I'd like to integrate into portfolio project. Firstly, the image effect where the images not hovered over shrunk slightly. This might be good on the skills cards. Secondly, the skewed background effect described above. This might be a more effective way of skewing the background of the skills section (may make it more easy to make responsive).

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)
* [Natours github repository](https://github.com/paul-duvall/Natours)
* [Natours website](https://objective-panini-843ecc.netlify.com/)


![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 20-21
### Sunday / Monday 24 / 25 February 2019 

#### Review / Learn:
* Wrote and posted blog post about my portfolio redesign
* Started to learn basics of SQL covering:
    * Creating and deleting a database
    * Adding a table and insterting entries
    * Updating and deleting an entry
    * Altering an existing table
    * Selecting data in different ways

#### Thoughts:
So I have a remote technical test for a job I have applied for. This will test a range of full-stack developer skills and I was advised to take a quick look at SQL and C# in order to improve my chances!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 22-23
### Tuesday 5 February 2019 

#### Review / Learn:
* Watched a [video about SQL]()https://www.youtube.com/watch?v=nWeW3sCmD2k and coded along
* Watched part of a [video on C#](https://www.youtube.com/watch?v=GhQdlIFylQ8&t=8360s) and coded along

#### Thoughts:
Projects - and everything - on hold whilst I prepared for a technical test for a job. Test did not go brilliantly. Back at the regular stuff tomorrow!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 24
### Friday 1 March 2019 

#### Review / Learn:
* Posted portfolio blog post to dev.to
* Watched [this video](https://www.youtube.com/watch?v=aGfi7GXAOWw) and [this video](https://www.youtube.com/watch?v=Z9QbYZh1YXY) about Agile.
* Watched first half of Andy Harris's [How to begin thinking like a programmer](https://www.youtube.com/watch?v=azcrPFhaY9k&t=1544s)

#### Project:
* Portfolio - resolved layout issues of projects section. Adjusted background height of skills section and added in box-shadow on various elements using a Sass mixin
* Portfolio - added html for footer section, started to add css

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)
Blog post on dev.to - https://dev.to/paul_duvall/updating-my-portfolio-1349

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 25
### Sunday 3 March 2019 

#### Review / Learn:
* Continued with Sass / CSS course Natours project. Starting working on tours section, which involved creating cards that flip round. Achieved using CSS properties - perspective, backface-visibility, transform: rotateY and position: absolute

#### Project:
* Styled the contact form in the footer and made footer fully responsive
* Tweeked layout of projects section (still not quite there)

#### Thoughts:
The end is within sight of the portfolio frontpage now. The large-viewport header section is still a shambles; the plan is to go back to the drawing board on that tomorrow and start from stratch. Once that is done, all that will be left to do is the navigation and some minor adjustments and it can go live. Quick thought - I will need to add some modals for the two featured projects so that their 'find out more' buttons go somewhere. But hopefully that can all be done by midweek and then I'll be able to turn my project focus over to the lemon tree for a bit. I'm hoping to have some material from the client before the end of the week.

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 26
### Monday 4 March 2019 

#### Review / Learn:
* Sass course Natours project - finished off the tours section and put together the 'stories' section. Used html tags (video, source) and css (including object-fit) to create a background video. Used a combintion of clip-path and shape-outside to get text to wrap around a circular image. Add some nice animations.

#### Project:
* Overhauled layout of header section on larger viewports. Happy with that now!

#### Thoughts:
The layout of the header section was too complex; have simplified by using grid a bit less and having a simpler flexbox layout at the top level.

Pushing on with the Sass course. Wanted to complete all sections in order so am aiming to get to the collapsable navigation very soon so I can use this as a template to impliment navigation on my portfolio. Also, there is a section on modals that I will use for portfolio also.

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 27
### Tuesday 5 March 2019 

#### Review / Learn:
* Started navigation section of Sass course Natours project

#### Thoughts:
Short and sweet - busy day with work so not much coding time. Decided to jump ahead to the nav section skipping the last main section so that I can integrate into my own portfolio as soon as possible.

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 28 and 29
### Wednesday and Friday 6 and 8 March 2019 

#### Review / Learn:
* Completed the navigation of course project for Sass / Advanced CSS course
* Continued reading YNKJS - Types and Grammar, reading about truthy / falsy values
* Continued reading Don't make me think, reading about how many arguments on usability are pointless and how there is no average web user

#### Project:
* Added navigation button and navigation to site
* Created a basic 'about me', 'contact', 'projects' and 'skills' pages
* Fixed some issues, including the link colour on project cards

#### Thoughts:
So it turns out that the navigation, as I set it up, doesn't disappear when a link is clicked upon if that link it to an anchor point within the same page. No doubt there would be work arounds using JavaScript but I do not have time to dedicate to those right now. Instead, I am setting up a bare-bones version of each of the site subpages, and linking to those from my navigation.

This needs to be done ASAP as I have a recruiter keen to put me forward to a company I like the look of, and there is another job being advertised at another company I am interested in, and I would love to have my new portfolio up and running so they can look at it. This means getting something servicable by the end of this weekend.

#### Link(s) to work
* [Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
* [Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 30
### Saturday 9 March 2019 

#### Project:
* Finished animation on navigation button
* Made some layout and style tweeks
* Bought domain name and attempted to hook up to site on Netlify

#### Thoughts:
The domain name stuff is all a bit of a mystery. Not really working right now - will see if it sorts itself out over night!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 31
### Sunday 10 March 2019 

#### Review / Learn:
* Watched advanced CSS / Sass course videos about adding modal
* Read [interesting article about problem-solving](https://medium.com/@janelgbrandon/problem-solving-like-a-programmer-88c4866752fc):

"A much more challenging aspect of programming is learning to think like a programmer when you are solving a problem. You start with a problem (where problem is a generic term meaning something you want to write code to accomplish), clearly define the problem, then translate it into data structures (the strings, numbers, arrays, hashes, objects, etc. that you will use to represent the problem) and control structures and flow (the loops, conditionals, methods, and algorithms) that will make up a solution."

* Continued reading about coersion in YDKJS: Types & Grammar, covering string to number (and visa-versa) and date to number coersion.

#### Project:
* Added modals to portfolio for projects
* Hooked contact form up on Netlify
* Added new button style for projects section

#### Thoughts:
The portfolio is now in a state where I can launch it and use it as my primary portfolio. Plenty more to do but now definitely better than my current portfolio! I'll be taking a break from this now and splitting my time between finishing the current project on the Sass course and starting design work on cafe project. Once the current project on Sass course is complete, I'll switch back to the React course. Will be doing the first sections again, perhaps putting together a separate, similar project instead of coding along with the course project.

#### Link(s) to work
* [Portfolio website](https://www.pjdwebdesign.com)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 32
### Monday 11 March 2019 

#### Review / Learn:
* Completed speed typing game tutorial and added high score functionality
* Wrote a blog post on using git workflow and posted to blog
* Started to review React by beginning the React section on FCC

#### Project:
* Made some corrections to links and pages titles on portfolio in response to suggestions on Twitter

#### Thoughts:
Updated CV / portfolio sent to recruiter, who is putting me forward for another role today. Applied for another role direct to the company.

Felt a little aimless today; worked through a youtube tutorial and then added to the functionality by adding a high score feature that persisted the score, if it beat the previous high score, to the local storage and displayed in the DOM.

#### Link(s) to work
* [WordBeater](https://codepen.io/duvallpj/pen/YgxmqM)
* [Portfolio website](https://www.pjdwebdesign.com)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 33
### Tuesday 12 March 2019 

#### Review / Learn:
* Continued YDKJS: Types and grammar, reading about implicit coersion

#### Project:
* Started to work on edit task functionality on devLearn
    * Added "id" data attribute to each item in the UI
    * Added event listener to the edit button for each of the tasks
    * Added 'open edit mode' function that identifies which item was selected, sets a currentTask property in the data structure to reflect item selected, populates the form with the data from that item and opens the modal to display the updated form.
* Set up devLearn to function as a git repository on local using git clone; pushed updates to origin

#### Thoughts:
It feels good to get back into some JavaScript - I feel like I needed the reassurance that (1) I hadn't forgotten everything and (2) I am actually able to impliment some of this stuff independently. Really pleased with what I added to devLearn - it may not look like much, but there were a number of steps. I'm very aware that following logical steps to solve a problem is a key skill to work on and it felt like I was able to do that today.

#### Link(s) to work
* [devLearn code](https://github.com/paul-duvall/devlearn)
* [devLearn site](https://boring-bohr-ee6bf1.netlify.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 34
### Wednesday 13 March 2019 

#### Review / Learn:
* Started to review React, going over how to set up a React dev environment with live-server, adding React scripts and using Babel to compile. Wrote a blog post covering this topic.
* Continued with React, reviewing JSX including JSX expressions and conditional rendering in JSX using
    * if statements
    * the ternary operator
    * the logical and operator - &&
* Continued reading YDKJS: Types and Grammar, learning about implicit coersion with booleans and the && and || operators

#### Thoughts:
Good to get back into a bit of React - definitely need to go over again; this time I'm going to write a series of blog posts essentially to remind myself how to do stuff. Once I am into the course project, I'll start working on a parallel personal project, apply the skills. Need to think about what that will be. By that time, I will hopefully have made decent progress on devLearn and have made a good start on the cafe website, both of which I will work on this weekend. Working tomorrow so little coding. Friday continued with React. Weekend for personal projects.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 35
### Thursday 14 March 2019 

#### Review / Learn:
* Continued with React review
    * Learnt about how to work with forms and inputs
    * and about how to work with Arrays including using the map() method to iterate over array items
    * and about creating React Components and nesting React Components
* Wrote blog articles on JSX and Using Arrays Within JSX

#### Project:
* Started to think about cafe design, locating some images from client's facebook account, selecting an approximate font for headings, etc. (), extracting colours from client's logo and setting up Adobe XD file

#### Link(s) to work
[Cafe project repositoy](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 36
### Saturday 16 March 2019 

#### Review / Learn:
* Continued with React course, learning how to use the constructor function in order to bind methods and how to use this.state, setState() and prevState to manage state

#### Project:
* Made a proper start on designing frontpage of cafe site, selecting a font and additional colours.

#### Thoughts:
Made a great start on design the frontpage of the cafe site; I'm really pleased with how the design has turned out.

#### Link(s) to work
[Cafe project repositoy](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 37
### Sunday 17 March 2019 

#### Review / Learn:
* 

#### Project:
* Worked on resolving form styling issue on portfolio.
* Finished cafe homepage design, creating mobile layout design.

#### Thoughts:
Thoughts here

#### Link(s) to work
links here

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 
### Tuesday 5 March 2019 

#### Review / Learn:
* 

#### Project:
* 

#### Thoughts:
Thoughts here

#### Link(s) to work
links here

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)
