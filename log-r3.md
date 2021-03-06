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
* Installed Inkscape and started to familiarise myself with this tool, watching a couple of basic tutorial videos

#### Project:
* Worked on resolving form styling issue on portfolio.
* Finished cafe homepage design, creating mobile layout design.

#### Link(s) to work
[Cafe project repositoy](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 38
### Monday 18 March 2019 

#### Review / Learn:
* Continued with React course
    * Refactored the 'Visibility Toggle' application, setting up to function as a React component
    * Reversing the data flow by passing methods down to children as props
    * learnt about Stateless function components and implimented in Indecision App
    * Setting up default prop values by creating a defaultProps objects
    * Lifecycle methods - componentDidMount, componentDidUpdate, componentWillUnmount

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 39
### Tuesday 19 March 2019 

#### Project:
* Worked on devlearn:
    * Added in cursor for hover-over of edit icons
    * Added in edit / delete buttons and added selectors for buttons
    * Create a set add state function that ensures the edit and delete buttons are hidden
    when user is adding new item
    * Create an edit state function that ensures edit and delete buttons are showing and add
    button is hidden when user is editing an existing item
* Worked on cafe design, beginning to design the menu page

#### Thoughts:
As always, it is good to get back in to making changes to an actual project - I really need to remember this and try to make some time, regardless of the mood I'm in, to make some kind of small progression on either the portfolio, Claude's or devLearn. 

I haven't written thoughts for a couple of days - again, need to remind myself that this is an important part of the process and I should do it every day. I recently fixed styling issue of the form on my portfolio; spent quite some time working on this, enlisted the help of another dev. Eventually, it turned out that is was an issue related to CSS specificity, which was resolved by adding an id and targeting that.

#### Link(s) to work
* [devLearn code](https://github.com/paul-duvall/devlearn)
* [devLearn site](https://boring-bohr-ee6bf1.netlify.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 40
### Thursday 21 March 2019 

#### Review / Learn:
* Worked on webpack section of React course

#### Project:
* Worked on devLearn, specifically functionality to edit existing items 

#### Thoughts:
Struggled with both things I worked on and ended up feeling like nothing was achieved. I need to make sure I really dedicate myself next week as I cannot code over the weekend due to family commitments.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 41
### Monday 25 March 2019 

#### Review / Learn:
* Listened to [JS Party](https://changelog.com/jsparty/67) podcast with Chris Coyer as a guest discussing further the 'great divide' in front-end development

#### Project:
* Worked on devLearn, adding functionality to enable editing of existing items:
    * added updateTask function to update the currently selected task in the data structure
    * added editItemInLS function to update the currently selected task in the local storage
    * close modal and reinitialise app to update display
    * tweaked populateTasks function to ensure that existing display is cleared prior to updating with new data
* Worked on Cafe website design, mostly finishing menu page for larger-viewports and starting menu page for smaller-viewports.

#### Thoughts:
Only had time for a few hours today but was pleased with progress made, particularly on the devLearn editing functionality. Spent quite some time on what felt like a complex solution to the issue, which was essentially finding a way to identify which item to update in the data structure and update it. Realised that there was a simpler solution and worked through this to completion, ensuring the item is also updated in the local storage and the UI. This issue had gotten the better of me last week so it felt good to resolve it and take the project to a point where I am more comfortable with prospective employers taking a look at it!

#### Link(s) to work
* [devLearn code](https://github.com/paul-duvall/devlearn)
* [devLearn site](https://boring-bohr-ee6bf1.netlify.com/)
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 42
### Tuesday 26 March 2019 

#### Review / Learn:
* Continued reviewing React using React Udemy course, going through the webpack section:
    * Installing and configuring webpack
    * Using ES6 import / export to set up named exports to break code out into separate files
    * Using default exports   
    * Importing third party modules
    * Setting up Webpack to work with Babel

#### Thoughts:
So it turns out that the stumbling block that was preventing me from continuing with the Webpack section of the course was...I had put the app.js file in the wrong folder! Once that was corrected, I was able to continue. As with last time I ran through this section, I am struck by just how complex Webpack is; or at least - how complex it feels to a beginner. the webpackconfig.js file all makes sense, but there is a lot to take in. Several additional dependencies need to be added to the package.json to enable Babel to work with Webpack and a new file .babelrc is needed to ensure Babel has access to presets that were previously listed in package.json. 

That feels like a lot, and I've no idea how I would do this without a precise guide such as this course to guide me through it. 

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 43
### Wednesday 27 March 2019 

#### Review / Learn:
* Listened to podcast about NPM from [JS Party](https://changelog.com/jsparty/55)
* Read chapter on mobile design in Don't Make Me Think

#### Project:
* Cafe website - finished design for menu page

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 44
### Saturday 30 March 2019 

#### Review / Learn:
* Read up a bit more on [BEM best practice](https://www.smashingmagazine.com/2016/06/battling-bem-extended-edition-common-problems-and-how-to-avoid-them/) in preparation for implimeneting on cafe website

#### Project:
* Started coding cafe website
    * Set up webpack and installed live-server
    * Started writing html for homepage

#### Thoughts:
Not a lot of time spent recently - have been unable to code for the last couple of days. Got a bit done today however and, given the short amount of time available, it felt right to make a little start on setting up the cafe project site structure. Felt good to make a start on that. Took it slow, thinking about class naming conventions to ensure I approach this area with a little more thought this time around, having used BEM in my previous project. 

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 45
### Sunday 31 March 2019 

#### Review / Learn:
* Continued with React course:
    * Components split out into separate files using export / import
    * Added a source map to the webpack.config.js file so that errors give an accurate location in the console
    * Setting up Webpack dev server

#### Thoughts:
Busy day. Had some time in the afternoon but felt very drained and decided to cut myself some slack and watched a film. Got in some time working on React in the evening.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 46
### Monday 1 April 2019 

#### Review / Learn:
* Continue with React course using the transform class properties plugin so that the constructor function is no longer needed (state can be defined directly on the object and methods no longer need binding as they can be defined as arrow functions.
* Also started to impliment a third party component, the React modal

#### Project:
* Set up the CSS and Sass file structure for cafe project
* Begun to style the navigation

#### Thoughts:
The navigation is going to take a while to set up on the cafe project; my hope is to get this fully implimented (including burger menu for smaller viewports and a dropdown section for the menu parts) before I do anything else. The React course continues to be challenging - there is so much to take in that, even on a second run through, I find myself a little overwhelmed. It all makes sense as we are working through it, but sometimes I look at the code we have written, and I don't recall what some of the specific parts are for or how the syntax for particular elements is put together (e.g. the different ways set state is used).

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 47
### Tuesday 2 April 2019 

#### Review / Learn:
* Continued with React course: 
    * Finished setting up the React modal third party component
    * Refactored stateless functional components to use arrow function shorthand syntax
    * Set up project to use CSS and Sass via webpack
    * Started writing Scss for the project
    * Added normalize.css

#### Project:
* Worked on navigation component for cafe website:
    * Styled component including links and logo element in centre of nav
    * Used [a tutorial](https://www.youtube.com/watch?v=gXkqy0b4M5g&t=57s) to help build the burger menu

#### Thoughts:
Made really good progress on the navigation component of the cafe website; I really like this particular method for a responsive nav bar, which uses a combination of CSS and JavaScript. After a couple of frustrating moments with webpack, I finally made some good progress with the React course; will have 'caught up with myself' by tomorrow and will be starting on fresh material.

I also want to start thinking about adding some bits and pieces to my portfolio site, just some small fixes and adjustments and maybe start thinking about building out the projects subpage.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 48-49
### Wednesday / Thursday 3 / 4 April 2019 

#### Review / Learn:
* Pushed on with React course, finishing the styling React section for first project, using that project to create a 'boiler plate' project to use going forward, setting up new project and starting to get into React Router

#### Thoughts:
Feels really good to push on into new territory with the React course, even though I strongly feel that the second run-through of the first half of the course was time well-spent. There are so many new concepts and tools to get to grips with, and I really felt that this review time helped solidify my understanding of some of those concepts.

React Router - even though I have only just started - is undoubtedly giving me one of those glorious 'ah-ha!' moments. Now I know what client side rendering is!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 50
### Saturday 6 April 2019 

#### Review / Learn:
* React course! Covered some more of React Router, including:
    * Setting up a 404 page
    * Linking between routes using Link and NavLink
    * Organising routes into separate components using import / export

#### Thoughts:
Not a lot of time spent today but got my hour in! I continue to enjoy learning about React Router!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 51 / 52
### Sunday / Monday 7/8 April 2019 

#### Review / Learn:
* Continued with React course:
    * Practiced router by creating a basic multi-page portfolio
    * Got an introduction to redux, covering how to set redux up and creating actions

#### Project:
* Worked on cafe project:
    * Added hover effect for nav links
    * Started to style the header section of the homepage

#### Thoughts:
Redux is a whole new way to manage state and it feels a little foreign at present, though I completely understand the need for it. I'm looking forward to setting up the next course project and putting Route and Redux into practice.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 53 / 54
### Tuesday / Wednesday - 9 / 10 March 2019 

#### Review / Learn:
* Watched a video about [position: sticky](https://www.youtube.com/watch?v=8TyoihVGErI)

#### Project:
* Worked on cafe project, adding html and css for opening hours and recommendations section of homepage for mobile view. Opening hours section finished, recommendations section started.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 55
### Thursday 11 April 2019 

#### Review / Learn:
* Read article about the [challenges of finding your first dev position](https://medium.com/@tuni_tech/your-first-developer-job-hunt-it-sucks-and-youre-not-alone-part-1-13c5a28942f8)
* And another about the [new loading attribute](https://addyosmani.com/blog/lazy-loading/) which will allow lazy loading of images with no JavaScript
* And another about [readability on the web](https://webdesign.tutsplus.com/articles/readability-on-the-web--cms-31165)
* And another about the [CSS text align property](https://ishadeed.com/article/the-hidden-power-text-align/)

#### Project:
* Continued with cafe project, finishing off design of mobile version of homepage, adding some JavaScript to auto update the date in the copyright info and fixing an issue with the burger menu div being visible off the side of the screen when it should be hidden
* Set up and complete the first front-end library project on freeCodeCamp - the Random Quote Machine!

#### Thoughts:
Made some great progress with the cafe project today - mobile version of homepage fully set up now. Will now create mid-size and full-size versions as quickly as possible so I can move on to the menu page.

I feel great that I managed to set up the first front-end library project using React so quickly and managed to get it to pass all the tests straight away. This is the first app I have built independently using React and it is a relief to have finally built something so I can prove I have been learning this technology! It still needs to be styled but once that is done, I'll get it on to my portfolio (which desperately needs a projects page - that is near the top of the job list too!).

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)
[Stoic Quote Machine](https://codepen.io/duvallpj/pen/VNpqLQ)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 56
### Wednesday 17 April 2019 

#### Review / Learn:
* Listened to a podcast about [how one person became a junior dev](https://learntocodewith.me/podcast/how-to-get-hired-as-a-junior-developer/)
* Listened to a podcast about [creating a portfolio](https://syntax.fm/show/133/hasty-treat-tips-for-a-good-portfolio)

#### Project:
* Created a contact form, including styling and validation JavaScript, for a coding test for a job application

#### Thoughts:
I enjoyed working on the web form. Went with a simple design that was inline with the companies brand and was pleased with what I produced. Hopefully what I produced - something simple that does the job - was what they wanted!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 57
### Tuesday 16 March 2019 

#### Project:
* Worked on cafe project, making homepage responsive for larger screens and adjusting positioning of nav links
* Styled Quote machine React project

#### Link(s) to work
https://codepen.io/duvallpj/pen/VNpqLQ

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 58
### Sunday 21 March 2019 

#### Review / Learn:
* Posted an article to blog outlining how to set up a React.js environment
* Started writing an article reviewing my portfolio

#### Project:
* Worked on cafe project:
    * Applied CSS Grid to make recommendations section of homepage response
    * Fixed issue with first recommendations section image sizing
    * Fixed issue with opening hours background image

#### Thoughts:
It took a long time to impliment CSS grid in the recommendations section - longer than I was anticipating. This was in part due to the length of time since I have last used grid in a project and partially because it was quite fiddly - switching positions of divs at different screen-sizes, adding / removing borders for different divs depending on the screen size, etc.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)
[React environment article](http://let-there-be-code.com/2019/04/21/react-environment-setup/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 59
### Tuesday 5 March 2019 

#### Review / Learn:
* Complete three challenges on Hackerrank
* Read an article about the [weird rules one jobseeker set for himself(https://dev.to/healeycodes/the-weird-rules-i-set-myself-that-got-me-a-job-2g9m?utm_source=digest_mailer&utm_medium=email&utm_campaign=digest_email)

#### Project:
* Added html for menu page of cafe project

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 60
### Tuesday 23 March 2019 

#### Review / Learn:
* Read an article to review [array methods](https://areknawo.com/exploring-the-hidden-potential-of-javascript-arrays/) - which included a number of methods I hadn't heard of - including .entries(), .keys() and .values()
* Solved a hackerrank challenge - Diagonal difference - that given a square matrix, calculate the absolute difference between the sums of its diagonals.
* Continued with React course, reviewing an introduction to Redux, installing Redux, using createStore, using actions to communicate with the store (an action is an object that must have at least one property - type), using store.dispatch to communicate with the store and setting up a switch statement to handle different types of action calls.
* Continued with React learning:
    * how to add additional properties to an action object in order to pass dynamic information via the store.dispatch to the Redux           store
    * using object destructuring (including default values and using a different name for the variable) for objects and arrays
    * creating action generator functions (using destructuring for the arguments passed in) so that the objects required for the dispatch() calls to the store only need to be written once (this minimises the opportunities for typos)

#### Project:
* Worked on cafe project menu page, styling navigation buttons and section header

#### Thoughts:
A pretty productive day after a couple of weeks of being a little less consistent than I would have liked. Still, only four hours despite being at home all day - need to begin building this back up again. A full day at home should result in six hours of productive coding and coding-related activities.

Still, it was good to get back into React. I enjoyed the Hackerrank challenge - I know I'm only on the easy ones, but it is reassuring that I am able to tackle these, since it has been a while since I've taken on any algorithm-like challenges such as these. And I made a satisfactory level of progress in the cafe project. Hopefully I can get the menu pages done within the next week and then I can take it to the client and see if I can get content for the catering page.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 61
### Wednesday 24 April 2019 

#### Review / Learn:
* Solved two challenges on Hackerrank, Plus Minus and Staircase
* Listened to a podcast interview about a developer who started [as a writer](https://freecodecamp.libsyn.com/ep-57-adam-hollett-from-writer-to-developer)
* Listened to a podcast interview with a developer who started [as a lawyer](https://secondcareerdevs.com/episodes/sonia-gupta)
* Watched a talk by Jen Simmons called [Thinking with grid](https://vimeo.com/331578108)

#### Project:
* Finished styling menu items on cafe project

#### Thoughts:

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 62
### Thursday 25 April 2019 

#### Review / Learn:
* Read an article reviewing [12 JavaScript concepts](https://hackernoon.com/12-javascript-concepts-that-will-level-up-your-development-skills-b37d16ad7104), including destructuring, closure (which I've added to my review list), generators
* Completed two challenges on Hackerrank, Birthday Cake Candles and miniMaxSum
* Continued with React course, learning more about Redux:
    * what reducer functions are and how they can be passed into createStore (they need to be pure functions and mustn't change the           state or actions
    * how to use combineReducers to use multiple reducers instead of one big one
    * using the array and object spread operator with redux

#### Project:
* Worked on cafe project menu page. Decided that, rather than hard-coding the menu items, they should be stored in JavaScript and be dynamically generated. Spent some time setting up that and getting it working.

#### Thoughts:
Again, positive experience with Hackerrank - this is turning into a really good way to start the day. React course continues to be good; the Redux structure is quite daunting but I have a basic understanding of what is happening.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 63
### Friday 26 March 2019 

#### Review / Learn:
* Solved problem on Hackerrank
* Continued reading YDKNJS: Types and Grammar, covering use of brackets to avoid disambiguation and ASI (Automatic Semicolon Insertion)

#### Project:
* Worked on cafe project menu page, breaking JS out into separate file (resolving an issue with the JS looking for page elements that weren't there on other pages). Added in the JS functionality to change to different menu sections.

#### Link(s) to work
[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 64
### Sunday 28 April 2019 

#### Review / Learn:
* Worked on a Hackerrank problem
* Continued learning about Redux in React course, setting up a function to filter and sort the data and then integrating the Redux code written into the main course project and organising the code into separate files and folders (separate folders for the store, the actions and the reducers).

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 65 / 66
### Tuesday / Wednesday 30 April - 1 May 2019 

#### Review / Learn:
* Read some Eloquent JavaScript, reviewing arrow functions, the call stack and optional arguments

* Listened to a podcast about covering [What's new in web development](https://syntax.fm/show/138/what-s-new-in-web-development) which included discussion about CSS Houdini (which allows you to create your own CSS properties), subgrid (a CSS feature that will be launched soon that allows child elements to be part of the same grid as parents) and CSS scroll snap (that allows pages to 'snap' to a particular element / div).

* Also listened podcast about [web accessability issues](https://learntocodewith.me/podcast/assistive-technology/)

* Continued React course, learning about Higher Order Components (HOCs). An HOC is a React component that renders another component. They allow you to reuse code and...some other stuff. I don't quite understand yet! Also went over using React-Redux in order to give a React app access to the Redux store.

#### Thoughts:
I've been a little inconsistent over the last few days but I hope to get back on track now. The focus for the time being is split between pushing forward with React / Redux knowledge and finishing the cafe project. The React / Redux stuff today was very tricky and will need review.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 67 / 68
### Thursday 2 + Friday 3 May 2019 

#### Review / Learn:
* Listened to [JS Party podcast](https://changelog.com/jsparty/73), which covered keeping up with changes in the dev world and book recommendations
* Listened to [Syntax fm podcast](https://syntax.fm/show/140/potluck-media-queries-npm-vulnerabilities-fullstack-js-vs-jamstack-web-vr-ar-switching-jobs-more)

#### Project
* Continued to work on menu page, getting all of the menu items in place and tidying up styling

#### Thoughts:
Really worked hard on the cafe menu page today and brought it really close to completion. There are just a couple of bits that need finishing off but it is 95% done. Then I need to think about the other two pages, which should be significantly easier and - really - at the same time, work out how I'm going to present it to the client.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 69
### Saturday 4 May 2019 

#### Project
* Continued to work on menu page, adding images for each section and data / JS for the extras sections

#### Thoughts:
It took quite some time to get the images to behave in the title block for each menu section. Went round and round in CSS circles and eventually adjusted the design so that the images didn't stretch across the whole menu div for larger screens (this was resulting in the images looking less than great). Instead, the image switches to the right hand part of the div, revealing a yellow background behind the text on the left.

I then added the data for the extras section and managed to get this to generate on the breakfast and mains sections. This took a bit of adjusting. I didn't realise it was going to be necessary to make some adjustments given that I needed the html to generate in two separate locations. I had to use querySelectorAll to grab both locations from the DOM and then an extra forEach loop to loop through both locations, generating the code in each.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

[Cafe project repository](https://github.com/paul-duvall/lemon-tree)

## Day 70
### Friday 3 May 2019 

#### Review / Learn:
* Continued with React course, implimenting functionality into Expensify app, connecting it with the Redux store, first to render individual expenses to the screen and then to add a text input that updates the text filter in the filters object in the store and then updates the expenses visible according to that filter. Also added in a dropdown to change the value of the sortBy field in the filters object so that the expenses shown are orders either by date or amount.

#### Project
* Finished off a few finishing touches on the menu page of cafe project
* Put together design of contact page

#### Thoughts:
Good progress on cafe website. Just need to create the contact page (which shouldn't take long) and I'll then be in a position to show something to the client.

Using React with Redux continues to be quite mind-bending, but I'm understanding the logic of how it works to some degree. Hopefully with continued practice and repetition, it will start to make sense. Essentially, I think the challenge he is to understand state and how state is managed. Since it is neccesary to set up a store and then create actions and reducers, it means there are several stages and, when the application is finally hooked up, everything suddenly working appears like magic. Need to keep at it and hopefully it will all click!

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

(NB. For days in between here, I did listen to multiple podcasts and read some of Eloquent JavaScript.)

## Day 71
### Saturday 11 May 2019 

#### Project
* Added design for cafe contact page mobile version
* Added html and CSS for mobile view for contact page

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 72
### Monday 13 May 2019 

#### Review / Learn:
* Continued with React course:
    * Added the 'add expense' form to the expensify app, creating a new component using a React class that generates a form. The input fields of the form each update a field in the class's state object (the amount field uses a regular expression to check that the form is correct).
    * Added a date picker to the form using [moment.js](http://momentjs.com/) (a time utility library that allows you to easily work with time and dates) and [react-dates](https://github.com/airbnb/react-dates), the actual calendar picker tool.
    * Set the form to update the Redux store on submit by calling a prop passed in from the parent (the add expense page). This is important - we wanted the submission to be handled by the page rather than the form because we will be reusing the form on the edit expense page, which will need to handle the data differently (they will need to dispatch different actions). Also used the history.push() method to switch pages back to the dashboard.

#### Project
* Started working on Markdown Viewer project on freecodecamp using React

#### Link(s) to work
[Markdown viewer](https://codepen.io/duvallpj/pen/zQKpBY)


![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 72
### Tuesday 14 May 2019 

#### Review / Learn:
* Read an article on [becoming a Junior Developer in 2019](https://medium.com/epfl-extension-school/becoming-a-junior-developer-in-2019-1942e4f6427f), which made some interesting points:
    * A key skill is testing / troubleshooting - need to be good at reading / understanding code that is already written and be familiar with common troubleshooting methods (things like - and I have no idea what these terms mean yet! - step-by-step execution, verifying assumptions). Should learn a testing framework.
    * Domain knowledge - look for jobs in an area where you already have experience. For me, this would be education. I don't know how many developer jobs there are linked to education that are local to me (none that I have seen!) but this is worth bearing in mind.
* Continued working on React course, not getting too far. Was setting up edit expense page on expensify app, but hit a road block when it didn't update correctly. Will need to rewatch this part.

#### Project
* Continued working on Markdown Viewer project, using the React prop dangerouslySetInnerHTML to resolve the issue I was having yesterday with the keystroke delay on the previewer working. Also added the initial markdown text that appears when the app is loaded, including a header (H1 size), a sub header (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text. 
* Started updating the projects page of my portfolio so that it is in-line with the original design. Added two more cards, setup the skewed background gradient and made some adjustments to the layout so everything is centered on smaller viewports.

#### Thoughts:
Made good progress on the Markdown viewer, which is now fully-operational and passing all tests. Next, it will need styling but that will be a job for another day.

Working on the React course continues to be challenging; the application we are making is now extremely complex (from my perspective) using Redux and React-Router - currently the code is spread over 18 different files. Hence making the move back to completing freeCodeCamp projects. These projects not only some much needed practice in actually implementing React, but also some finished items that can be integrated into my portfolio.

It was also good to look back to my portfolio and to start building out the projects page properly. This was not without challenges - centering the content proved suprisingly tricky since I was trying to position the project cards over a skewed background; I ended up utilising the fact that I was already using position relative and absolute by implimenting a trick using transform: translate I learnt from the advanced CSS course.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)

#### Link(s) to work
[Markdown viewer](https://codepen.io/duvallpj/pen/zQKpBY)
[Portfolio 2 github repository](https://github.com/paul-duvall/portfolio-2)
[Portfolio website](https://wizardly-snyder-0678f7.netlify.com/#)


## Day 73
### Wednesday 15 May 2019 

#### Project
* Made some tweaks to the cafe project site; layout adjustments on contact page, a minor copy change on the homepage and adjusting the images appearing in the header sections on each page

#### Thoughts:
Short and sweet today. Client came round to look at site and was pleased. They will be providing some copy and images to go on the two final pages. Hoping to turn it around in the next month, but this is dependent on them providing that text.

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 74
### Friday 17 May 2019 

#### Review / Learn:
* Read a good article called [Moving passed tutorials: pseudocode](https://dev.to/aspittel/moving-past-tutorials-pseudocode-13a6) covering the importance of being able to write good pseudo-code in the early stages of working out how to tackle a project.

#### Project
* Styled the markdown view and submitted to freeCodeCamp

#### Thoughts:
Styling the markdown viewer took longer than anticipated but I'm pleased with how it has turned out. Particularly pleased with how the 'top-bars' of the editor and viewer components feel that they are properly connects to the main components (especially the use of border-radius at the top of the top bar and the bottom of the main component to give them a consistent feel) and the styling of the scroll bar on the editor. I didn't spend too long on this so no doubt it could be improved, but I'm happy that I managed to add some styling to it.

I enjoyed the pseudocode article and wrote some pseudocode for my bedtime routine, which was fun. Then I wrote some pseudocode for a freeCodeCamp JavaScript algorithm challenge and then used that to write a solution.

#### Link(s) to work
[Markdown viewer](https://codepen.io/duvallpj/pen/zQKpBY)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 75
### Sunday 19 May 2019 

#### Project
* Worked on the project page of my portfolio, making the project cards responsive + changing the layout on larger viewports using CSS grid. Also fixed issue with background images of project cards not taking up the full card and added newer projects. 

#### Thoughts:
Not a huge amount of coding today, but made some great progress on portfolio and made changes live. There are a couple of issues that will need to be fixed (form at bottom of projects page broken, project cards not staying central on larger viewports).

#### Link(s) to work
[Portfolio projects page](https://pjdwebdesign.com/projects.html)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 76
### Monday 20 May 2019 

#### Review / Learn:
* Read [Receiving a problem to solve](https://dev.to/aspittel/moving-past-tutorials-receiving-a-problem-to-solve-2hf8) article by Ali Spittel. Learnt what MVP means (not Most Valuable Primate...actually Minimum Viable Product!) - the most basic site / application that can be deployed and made available to users. 
* Worked through the Metronome project in Dave Ceddia's [6 Fun React Projects You Can Build article](https://daveceddia.com/react-practice-projects/)

#### Project
* Started to think about Hiit project; as per the article above, 
* Learnt how to use create-react-app in order to quickly create a simple React.js application. Deployed as a practice to Netlify.

#### Thoughts:
The idea for a project related to Hiit training was suggested to me by a friend. He proposed an application that would randomly generate a sequence of exercises for a Hiit workout session.

#### Link(s) to work
[Practice deploy to netlify](https://sad-benz-30063a.netlify.com/)
[Metronome](https://suspicious-mirzakhani-bf1c66.netlify.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 77
### Wednesday 22 May 2019 

#### Review / Learn:
* Listened to a [second career devs podcast](https://secondcareerdevs.com/episodes/kurt-kemple) about an ex-felon who became a web developer. Very interesting, particularly hearing what he had to say about mindset during the times that might be consider low points in life: need to approach every day with a positive attitude. He said to be wary of viewing getting a development job as success and expecting everything to be ok after that. Some of the days right now could well be the best days if viewed with a positive attitude.

#### Project
* Worked on adding some animations to portfolio site.

#### Thoughts:
Made quick work of setting up some simple animations on my portfolio homepage, something I have been meaning to do for a while now. I used keyframes and the animation property. Commited and uploaded to Gitub. For some reason, these animations are not having an effect on my live site. A problem for another day!

#### Link(s) to work
[Portfolio](https://pjdwebdesign.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 78
### Thursday 23 May 2019 

#### Review / Learn:
* Watched a video, read docs for AOS, an animate on scroll library.
* Created a demo site to practice using the library.

#### Thoughts:
I intend to use this animation library on my portfolio. Should be able to implement this tomorrow.

#### Link(s) to work
[AOS Demo site](https://unruffled-brattain-507825.netlify.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 79
### Saturday 25 May 2019 

#### Review / Learn:
* Listened to podcast about [CSS - The Cool Parts](https://syntax.fm/show/146/css-the-cool-parts)

#### Project
* Added AOS library to portfolio and used to animate elements on homepage and projects page

#### Thoughts:
It really was quite straight-forward to use the AOS library and quick to add animations to my portfolio. These simple animations on scroll, I hope, are subtle enough so as not to detract from content. They have made the pages feel a little more dynamic.

#### Link(s) to work
[Portfolio](https://pjdwebdesign.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 80-81
### Monday / Tuesday 27 / 28 May 2019 

#### Review / Learn:
* Worked through a React tutorial making a recipe app. 
* Worked on a hackerrank problem - couldn't do it! Got close but it failed some test cases and I couldn't work out why

#### Project
* Made some tweaks to portfolio
    * Adjusted timings on button animation on homepage
    * Fixed height on background on projects page so it spans all the main projects
* Took a look at drum machine project on freecodecamp - it looks hard!
* Started to design a product page for boardgame shop site

#### Thoughts:

#### Link(s) to work
[Portfolio](https://pjdwebdesign.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 82
### Wednseday 29 May 2019 

#### Review / Learn:
* Posted an article about [JSX](http://let-there-be-code.com/2019/05/29/jsx/) on my blog.
* Completed a couple of freecodecamp lessons in the React section

#### Project
* Continued looking at the freecodecamp drum machine, making some progress. Built array of objects to house the sounds and related properties. Rendered a button to the screen for each object in the array. Adjusted the handleSound function so that it plays a different sound depending upon which button is clicked.

#### Thoughts:
Progress made with drum machine app - I feel like this is progressing in a positive direction now. There are, however, a couple of bugs now: firstly, there is an error the first couple of times a button is clicked - uncaught (in promise) DOMException - and secondly, it seems that the first time a button is pressed, it plays the sound assigned to the previous button.

#### Link(s) to work
[drum machine](https://codepen.io/duvallpj/pen/MdGBXm)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 83 / 84
### Friday / Saturday 30 May - 1 June 2019

#### Review / Learn:
* Read a good article about [how to write clean, scalable JavaScript](https://blog.logrocket.com/12-tips-for-writing-clean-and-scalable-javascript-3ffe30abfe20/). Not much new but a good reminder of general principles.

#### Project
* Started adding a section at the bottom of the projects page on my portfolio for smaller mini-projects
* Worked on drum machine, fixing the issue with each button playing the sound of the previous button before switching over to correct sound. This was achieved by cutting out an unnessessary stage I had put in (I had added a property to the state to hold the location of the sound file but actually this could be automatically assigned from its location in the sound's object, cutting out the need to use the state) and using async / await so that the sound doesn't play until the state has been set.
* Also on drum machine, started to add functionality to enable sound to play on key press. Used componentDidMount() to add an event listener that runs a function that grabs the keycode from the event object.

#### Thoughts:
Haven't done as much as I would like over the last couple of days, but when I have sat down and coded, it has felt productive. Have been in contact with client for cafe website; it sounds like she will be able to provide the remaining content soon and then that will be up and running. Really looking forward to getting that, and my drum machine, added to my portfolio. 

I read an article about how jQuery was still relevant. Made me think that I should be building something using jQuery to demonstrate that I am able to use that tech (and to remind myself of the syntax / methods, etc. because I have basically forgotten all of it) - possibly the boardgame product page I am working on...

#### Link(s) to work
[drum machine](https://codepen.io/duvallpj/pen/MdGBXm)
[Portfolio](https://pjdwebdesign.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 85
### Monday 3 June 2019 

#### Review / Learn:
* Review jQuery a bit by watching a couple of tutorial videos:
    * [jQuery Race Game](https://www.youtube.com/watch?v=QVSwX98kKFs)
    * [jQuery effects and animation](https://www.youtube.com/watch?v=QVSwX98kKFs)
* Started writing blog post on multitasking in coding

#### Project
* Worked on drum machine, adding functionality that enables sounds to play on key press
* Finished adding secondary projects to projects page on portfolio
* Started working on a jQuery-focused project - a movie quote quiz. Created basic setup - a 'start screen', a container than houses a random multiple-choice question and an info section that currently contains a score tracker

#### Link(s) to work
[drum machine](https://codepen.io/duvallpj/pen/MdGBXm)
[Portfolio](https://pjdwebdesign.com/)
[Movie Quote Quiz](https://codepen.io/duvallpj/pen/wbNYwQ)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 86
### Tuesday 4 June 2019 

#### Review / Learn:
* Finished writing blog post on multitasking in coding (will need to edit)

#### Project
* Resolved issue with score tracker in Movie Quote Quiz and added some basic styling. Also added functionality so that quotes don't appear more than once and added an 'end of game' function that displays message and final score.
* Started putting in place html for skills page on portfolio
* Responded to email from cafe site client, adding to and editing some provided copy and sending it back for their approval

#### Thoughts:

#### Link(s) to work
[Portfolio](https://pjdwebdesign.com/)
[Movie Quote Quiz](https://codepen.io/duvallpj/pen/wbNYwQ)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 87
### Wednesday 5 June 2019 

#### Project
* Worked on movie quote quiz, adding some styling and functionality for 'lives' - you get three lives and, if they run out, the game ends.

#### Thoughts:
Short and sweet today. Also tried to add reset to movie quiz, which is proving more complex than I anticipated. I reset the lives to to three but, for some reason, when it restarts, it doesn't register the newly updated lives and so ends the game immediately. One for another day.

#### Link(s) to work
[Movie Quote Quiz](https://codepen.io/duvallpj/pen/wbNYwQ)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 88
### Friday 7 June 2019 

#### Review / Learn:
* Took up the Advanced CSS course again, finishing the section on styling a modal, adding a nice subtle zoon animation on open

#### Project
* Worked on drum machine, starting to style the app, adding a display that shows what sound is currently playing and an on/off button

#### Link(s) to work
[drum machine](https://codepen.io/duvallpj/pen/MdGBXm)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 89
### Tuesday 4 June 2019 

#### Project
* Drum machine - added animation to buttons on click and changed the on/off button to a slider

#### Link(s) to work
[drum machine](https://codepen.io/duvallpj/pen/MdGBXm)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 90
### Sunday 9 June 2019 

#### Project
* Changed 'featured project' on portfolio homepage to the Stoic Quote Machine
* Contacted cafe project client to explain that provided images were quite low quality and suggesting a way to send images of a higher quality (which I know they have)
* Created design for the cafe project 'about us' page using XD
* Started to code the cafe project 'about us' page, adding html and css for smaller viewports. Started to code responsive version for larger viewports

#### Thoughts:
Emailed a couple of recruiters about jobs today. One job, in particular - a junior web developer role - looks promising. Conscious that this means someone new will be looking at my portfolio, I changed the 'featured project' on my portfolio homepage away from devLearn to the Stoic Quote Machine. This project may be quite simple, but it is complete, demonstrates my ability to used Reactjs and is quite well-designed.

Made a personal commitment to push forward with the cafe project - need to get this done ASAP as I would like it done and am quite keen to feature it in my portfolio. Worked on the about us page today then hit a bump with responsive css. Will take another look tomorrow.

#### Link(s) to work
[Portfolio](https://pjdwebdesign.com/)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)



## Day 91
### Tuesday 11 June 2019 

#### Review / Learn:
* Posted blog on multitasking and coding

#### Project
* Worked on cafe project, completing work on loayout and image styling for about page and creating and populating an image gallery page using lightbox. Navigation updated, removing catering link and adding in link to new gallery page.
* Add some styling to my movie quote quiz, some extra questions and some functionality at the end to provide a different end-game message depending on the user's score.

#### Thoughts:
Lemon Tree very, very close to being complete. There are a few layout bugs to sort on the homepage and then client's images will need to be integrated replacing old images, then it'll be done. Hopefully will be able to get the rest of the work done by the end of the week and will then host on Netlify and send client a link.

#### Link(s) to work
[cafe respository](https://github.com/paul-duvall/lemon-tree)
[Movie quote quiz](https://codepen.io/duvallpj/pen/OYqEeY)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 92 / 93
### Thursday / Saturday 13 / 15 June 2019 

#### Review / Learn:
* Continued with Advanced CSS course, reviewing media queries, including the pros and cons of mobile first:

![Responsive design - mobile first](https://raw.githubusercontent.com/paul-duvall/website_images/master/responsive-design-mobile-first.jpg)

The lesson also covered selecting breakpoints. It suggested that using standard breakpoints based on currently-popular devices is a bad strategy. Better is to use an average of commonly-used devices. Even better is to ignore devices and base decisions upon the design.

Then moved on to actually implimenting some media queries, which was achieved using Sass mixins and the 'content directiive', which allows you to pass properties into a mixin:

@mixin respond-phone {
  @media (max-width: 600px) { @content };
}

#### Project
* Made some adjustments to CSS for the movie quiz in the hope of removing the display issues some users were experiencing. Also moved project off codepen, setting up a git hub repository and deploying to Netlify.
* Also added gradient effect to the main title

#### Thoughts:
Reviewing media queries was interesting - it occured to me that I have never actually worked through any proper courses on this subject, having just picked up what I know here and there as I needed it. Using Sass mixins is a bit of a revelation - it will clearly lead to more readable code since having all the code related a particular class / id / tag in the same area will make it a lot easier to write and edit.

Also, now that we are implimenting media queries, it is really clear just how useful it is to base everything on rems and to manual control what 1rem equals. So by adjusting this for different viewport sizes, not only do the font sizes change across the site, things like padding and margin begin to automatically adjust, reducing the size of buttons, padding around components, etc. really quickly and with hardly any effort.

#### Link(s) to work
[Movie Quote Quiz](https://quizzical-edison-7689de.netlify.com/)  
[Advanced CSS Course Natours Project](https://github.com/paul-duvall/Natours)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 94
### Sunday 16 June 2019 

#### Project
* Worked on Lemon Tree, adjusting the burger menu so it doesn't widen the screen over to the right (it still does this, annoyingly, but now only after it has appeared)
* Adjusted movie quiz so it looks better on smaller viewports
* Added movie quiz to portfolio

#### Link(s) to work
[cafe respository](https://github.com/paul-duvall/lemon-tree)
[Movie Quote Quiz](https://quizzical-edison-7689de.netlify.com/)  

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 95
### Monday 17 June 2019 

#### Project
* Fixed issues with cafe project side-scrolling and navigation

#### Thoughts:
Didn't have time for a whole lot today but it's good to resolve the issues I was having, particularly because I'd spent so much time looking at this previously! The navigation issue was fixed with the help of someone on Twitter. For the side-scrolling, I asked for help and got lots of suggestions but, ultimately, I managed to get to the bottom of it myself. I learnt the benefit of gradulally removing components until you remove one and the issue is resolved, thus narrowing it down to that component. This was suggested by Scott on an episode of syntax.fm and really helped to narrow down the problem.

#### Link(s) to work
[cafe respository](https://github.com/paul-duvall/lemon-tree)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 96-97
### Tuesday / Wednesday 18 / 19 June 2019 

#### Review / Learn:
* Continued with the section of Advanced CSS course, learning how to impliment media queries with Sass
* Listened to a [Changelog](https://changelog.com/podcast/349) podcast about the State of CSS in 2019 survey

#### Project
* Replaced images on cafe website with images taken by client

#### Link(s) to work
[cafe respository](https://github.com/paul-duvall/lemon-tree)
[Advanced CSS Course Natours Project](https://github.com/paul-duvall/Natours)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 98
### Tuesday / Wednesday 18 / 19 June 2019 

#### Review / Learn:
* Continued with Advanced CSS course, finishing section on media queries in Sass

#### Project
* Drum machine
    * Added styling for an 'off mode'
    * Added 'drum machine' text
    * Made responsive for smaller viewports

#### Link(s) to work
[drum machine](https://codepen.io/duvallpj/pen/MdGBXm)
[Advanced CSS Course Natours Project](https://github.com/paul-duvall/Natours)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 99
### Friday 21 June 2019 

#### Review / Learn:
* Continued with Advanced CSS course, learning about responsive images:
    * Using the srcset and sizes properties on html img elements
    * Using the min-resolution media query in CSS
* Course also covered using feature queries (using @supports) to check a CSS property is supported before it is applied

#### Project
* Designed and started to code a component for an organic box delivery company. This will be used to practice using Media Queries in conjunction with Sass and, possibly, responsive images

#### Link(s) to work
[Organic boxes - Sass and Media Queries](https://codepen.io/duvallpj/pen/xoqLBr)
[Advanced CSS Course Natours Project](https://github.com/paul-duvall/Natours)

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


## Day 100
### Saturday 22 June 2019 

#### Review / Learn:
* Went over using media queries in Sass using mixins and @content and @if; wrote a blog article about this.

#### Project
* Finished organic food box mini-project, practicing media queries in Sass
* Continued design of board game e-commerce product page

#### Thoughts:
I'm pleased with the mini-project and glad I created an opportunity to have a bit of a practice with using media queries in Sass. Wrote the blog post to cement the knowledge - it is actually quite straight forward, so I'll definitely be using this on my next mid-scale project, which will most likely be the e-commerce product page.

#### Link(s) to work

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)
