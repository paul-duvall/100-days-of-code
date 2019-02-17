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
[Portfolio 2 github files](https://github.com/paul-duvall/portfolio-2)

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
        

#### Project:
* 

#### Thoughts:
Thoughts here

#### Link(s) to work
Links here

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)


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

![Fancy line](https://github.com/paul-duvall/website_images/blob/master/line1.png?raw=true)
