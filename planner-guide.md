# Want to Get Stuff Done? Behold!! The Ultimate System to Git-Things-Done!
_This article was originally posted in [barbarianmeetscoding.com](https://www.barbarianmeetscoding.com/blog/2015/06/04/want-to-get-stuff-done-behold-the-ultimate-system/). 😊_

Do you ever feel like you can't get enough stuff done? That days and weeks pass and you never get around doing that thing that you really want to focus on? Then this article may help you!

Today a great colleague from [Active Solution](http://www.activesolution.se/), [Evgeny Lukashevich](https://www.linkedin.com/in/evgenylukashevich), encouraged me to share my productivity system with you. After pondering about it a little bit on the commute home I thought: _Why not? Perhaps it will help someone to get more stuff done and live a more fulfilling and happy life. Who knows?_ I have never ever written about this before... it is definitely going to be interesting...

## [](#a-long-time-ago-in-a-galaxy-far-far-away)A Long Time Ago, in a Galaxy Far, Far Away

A while back, when I abandoned the sheltered, free, uncompromising and carefree life of a university student and started working as a software developer I quickly realized that, all of the sudden, I did not have time to do anything (anything else than work that is). I would spend the days at work, to come home tired, make and eat dinner, watch something, go to bed and repeat the next day.

After several weeks of this dynamic, with such as stark contrast to my previous life as a student where I pretty much did whatever I wanted, whenever I wanted, I thought to myself: _"This cannot be all there is to life"_. From then on, I would endeavour to find a way to get more stuff done, to get more out of life. And this is how _"the system"_ that I use today came to be. After reading [a ton of books](http://www.barbarianmeetscoding.com/reading/) and slowly improving it throughout the years I would build **a productivity system to design a life worth living**.

[![The System Git Things Done](https://res.cloudinary.com/practicaldev/image/fetch/s--lkJHfYbH--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.barbarianmeetscoding.com/images/the-system.jpg "The System Git Things Done")](https://res.cloudinary.com/practicaldev/image/fetch/s--lkJHfYbH--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.barbarianmeetscoding.com/images/the-system.jpg)

## [](#the-system-gitthingsdone)The System, Git-Things-Done

### [](#the-basics)The Basics

The system rests on 3 pillars:

*   Yearly, Monthly, Weekly and Daily goals that support each other
*   A core set of values, principles and a life purpose
*   Constant reflection and continuous improvement

**The yearly, monthly, weekly and daily goals give me direction and ensure that I spent my time in the most valuable way possible** (according to me).

I start the year by setting 3 goals on different areas such as _myself_, _life_, _career_, _financial_, etc. I then divide the year in quarters and set themes for each one of these quarters, a high level view of the things that I want to achieve in each one of them. These have to support and be aligned with the yearly goals in some way. Every month I set 3 goals for the month, something that I want to improve, and something that I should stop doing. Again these goals should support the quarterly and yearly goals. Every week I set 3 goals for the week, and so on. When I get to the day level I may use supporting techniques like the Pomodoro depending on the case.

**The core set of values, principles and life purpose help me take decisions**. When you have reflected about how you want to be and behave, it is much easier to make decisions. **The life purpose also serves as a long-term guidance**.

Finally I reflect often (every day, week, month, year) and incorporate improvements into upcoming goals. This is basically my **mechanism for continuous improvement**.

**In practice**, I handle everything within _this system_ through text files written in [markdown](http://daringfireball.net/projects/markdown/) and stored within a git repository (that's why I call it **GitThingsDone** sometimes [Get Things Done](http://gettingthingsdone.com/) + Git = Git-Things-Done :D). I edit them using vim:

[![The System Git Things Done and vim](https://res.cloudinary.com/practicaldev/image/fetch/s--RHWnjiN2--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.barbarianmeetscoding.com/images/gitthingsdone-in-vim-small.png "The System Git Things Done and vim")](https://res.cloudinary.com/practicaldev/image/fetch/s--RHWnjiN2--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.barbarianmeetscoding.com/images/gitthingsdone-in-vim-small.png)

Throughout the years I have tried lots of different applications: note-taking apps like evernote, scrum/kanban apps like pivotal tracker, to-do-list apps, trello, but I have irremediably ended up working against the tool and getting frustrated. And thus, in the end, nothing has afforded me the flexibility nor ease of use of a good olde text file.

This is a summary of the different steps involved in GitThingsDone:

*   **Reflect about your values, principles and purpose in life**
    *   Review frequently
*   **Yearly**:
    *   Start of the year: Set 3 goals for each area and for the year. Set quarterly goals
    *   End of the year: Review Year, Celebrate, Reflect
*   **Monthly**:
    *   Start of the month: Review yearly goals. Set 3 goals for the month that support the yearly goals. Focus on improving one thing and stop doing something unnecessary.
    *   End of the month: Review month, Celebrate, Reflect
*   **Weekly**:
    *   Start of the week: Review monthly goals. Set 3 goals for the week that support the monthly goals. Focus on improving one thing and stop doing something unnecessary.
    *   End of the week: Review week, Celebrate, Reflect
*   **Weekly (HOME)**:
    *   Start of the week: in addition to the above plan the whole week ahead.
*   **Daily (HOME)**:
    *   Start of the day: Blog, train
    *   Rest of the day: Follow goals as planned. Adapt. Be Flexible
*   **Daily (WORK)**:
    *   Start of the day: Review weekly goals. Read mails. Review backlog and remaining actions from yesterday. Set 3 goals for the day that provide the highest value.
    *   End of the day: Review day, celebrate, reflect and time report :).

And that's the basic of the system _grosso modo_. In the upcoming sections I will give you some concrete examples and more details about each of the elements of _Git Things Done_.

### [](#yearly-overview)Yearly Overview

When a new year comes I sit down and think about what I would like to achieve during the year. I reflect about the different areas in my life and I write down a at least 3 goals per area for the year. These goals will be my guiding light for the year to come and I will frequently review them during the year.

These are my goals for 2015 for instance:

<div class="highlight">

    // I usually pick a theme for the year, month, week
    // this year I didn't, I think I had some uncertainty as to what
    // to choose since I had just moved to Stockholm and was starting a new job
    # 2015 - The Year in which...

    ## Goals (set SMARTer goals)

    ### Myself

    - I want to finish things, get through with things more often
    - I want to be more mindful of every moment, enjoy the moment,
      live in the moment
    - I want to be more daring, outgoing this year, I want to get out there,
      be uncomfortable, do more things and talk to ppl

    ### Life

    - I want to spend more quality time with Malin. More travel,
      more and better time spent together
    - I want to get the perfect body this year
    - I want to get my driving license this year

    ### Career

    - I want to do an awesome job at Active Solution
    - I want to release at least one new(updated) product with
      my company
    - I want to write my first book
    - I want to become an expert in front-end web development
    - I want to become good at drawing, digital drawing and design
      with Photoshop

    ### Finance

    - I want to save 100K this year in addition to what I
      have saved thus far
        - save around 8K every month, which means 5K personal saving
          + 3K saving with Malin
    - I want to have made 30K revenue from my side-projects
      (company, blog, etc) by the end of the year
    - I want to have a better control/knowledge of where my money goes
        - remove all unnecessary monthly costs and spendings.
        - be more mindful and careful of how I spend my money
        - be smarter when paying things, take advantage of company offers,
          discounts, etc

</div>

When a year finishes, I sit down, review the year and reflect about what I have achieved. I celebrate the stuff that I have done, learn from my mistakes and feel hopeful for the future. These are my reviews/reflections from 2014:

<div class="highlight">

    # 2014 - The Year in Which I Started My Own Company

    In summary:
        - Great job with life goals, better work life balance,
          great time with Malin and good job with health
        - Great job with career although not so awesome job in
          my personal career endeavors
            - funny I don't have any goal in relation to working at
              Medius :) is that telling?
            - I did a great job with the blog, writing articles,
              getting a ton of readers, doing a great job
            - I did a great job with presentations and presenting
              in the local community
            - I started a company although I didn't do anything with
              it in terms of development
            - didn't write a book as I have planned :/
            - didn't spend any time with design skills
        - Ok job in finance
            - I did continue saving money and my net worth has
              increased this year. I still feel however like I
              never have money, which sucks, I need to improve
              my grasp on my own finances and where the money is going

    ## Goals
    ### Life

    * I want to have a better work-life balance. Do not work
      more that 40 hours a week no matter what. Fuck overworking.
      Be more effective at work, do more in less time.
    * I want to spend more quality time with Malin. More travel,
      more and better time spent together.
    / I want to get the perfect body this year :)
            - working on it :)

    ### Career

    * I want to start my own company
        - Started it but did not do much work with it unfortunately
    - I want to write my first book
        - #FAIL
    / I want to become an expert in front-end web development
        - I did improve a lot on this are but I don't think
          I can consider myself an expert yet
    - I want to become good at drawing, digital drawing and design
      with Photoshop
        - #FAIL

    ### Finance

    - I want to have saved 150K by the end of the year
        - I have saved so far -> 41K personally +
          60K with Malin => 101K saved much lower than
          my goal unfortunately
            - possible causes, paying the macbook, expensive
              trip to japan and spain, paying loan
            - I need to have a closer look at my economy and look
              where the money is going
            - soon I will have a better salary!!
    - I want to have made 30K revenue from my side-projects
      by the end of the year
        - #FAIL
    / I want to remove all unnecessary monthly costs and spendings.
        - I have improved with this in the sense that I don't
          have as many monthly subscriptions as I did before.
            - it doesn't feel like this was the main issue
              because I still struggle a little bit with money
            - I need to continue reviewing my monthly costs and spendings
            - Make better use of the stuff that the
              company offers me -> phone, training, etc

</div>

#### [](#quarterly-goals)Quarterly Goals

After having set the yearly goals and painted how the year is going to look like, I drill down and become more specific/practical with quarterly goals:

<div class="highlight">

    ## Quarter By Quarter
    * Q1: Angular.JS and buffing up my knowledge for Active Solution (Jan, Feb, Mars)
        * AngularJS
        * Web API
        * MVC
        * Certificates!
            * MSCD in web dev
                * front-end
    * Q2
        * I: Knowledge
            * Certificates! MSCD
                * backend!
                - cloud
                - C#
            - Design and Art!!! Illustrator or Photoshop?
        * II: Focus a 100% on my company and develop a product (April, Maj, June)
    * Q3: Write a book javascriptmancy -> portal (July, Aug, Sep)
    * Q4: Learn Haskell and/or F# (Oct, Nov, Dec)

</div>

I then divide the different monthly, weekly and daily goals into two subcategories, one is _home and life_ (the stuff that I do when I am not at work) and the other is _work_.

### [](#home-and-life)Home and Life

#### [](#monthly-overview)Monthly Overview

When I start a new month I review the past month, reflect and set 3 new goals for the month to come. I also select an item that I would like to improve and something that I should stop doing.

These are my _Home and Life_ monthly goals for this month of June for instance:

<div class="highlight">

    # June 2015 *The month I took the 487 Certificate biatches!*

    ## Goals
    - Must: Focus more on Malin
    - Should: Take the Azure and web services certification
    - Could: Write 4 blog posts this month

    - Improve: Your exercise, concentration and level of energy at the gym
    - NotToDoList: Don't get frustrated or annoyed for stupid things, chill

</div>

And this is my last month's review:

<div class="highlight">

    # May 2015  * The month I took yet another certification under my belt *

    ## Goals

    * Must: Take the backend certification
    * Should: Write 4 blog posts this month
        * I wrote 8 blog posts this month WAAAAAT
    * Could: Train every single fucking day and medidate in the mornings
        * I have trained at least 5 days every week and meditated (at night)

    ### 3 things that went well
    - Awesome job with the certification
    - AAAWESOME job with the blog, writing 1h every morning has brought awesome results
    - AAAWESOME job training first thing in the morning
    - AAAWESOME job waking up at 5.30 almost every day of the week  
    - This month was freaking awesome in terms of results and getting shit done

    ### 3 things that did not go so well and should be improve
    - Plan more things to do with Malin, focus more on Malin and less on my career/hobby of developing
    - I feel like I have lost a little bit of contact with my family
      and friends. I need to call my family more often and
      restablish the contact with my friends
    - Played videogames too long some days this month. It was a
      ton of fuuuuuun. But I think it is hearlthier if I can
      timebox it. Otherwise the time flies by and whole days are gone.
    - Be more social at work. Go to AW!

    ### What am I going to do to improve?
    - Have a monthly goal related to beautiful Malin
    - Book one day to call home. Make it a routine
    - Timebox playing videogames you biatch

</div>

Apparently I call myself and other people _biatches_ often in this review sections :D.

#### [](#weekly-and-daily-overview)Weekly and Daily Overview

One level down and again I set 3 goals for the week, one thing to improve and one things to stop doing. The goals should support the monthly and yearly goals. Since I don't have so much time outside of work, I have found that I am more productive if I plan the whole week in advance (it took me years to come to this realization). This removes the need to think and re-evaluate each day and I can just get started kicking ass right away.

This week goals look like this for example:

<div class="highlight">

    # June 2015 *The month I took the 487 Certificate biatches!*

    ## Goals
    - Must: Focus more on Malin
    - Should: Take the Azure and web services certification
    - Could: Write 4 blog posts this month

    - Improve: Your exercise, concentration and level of energy at the gym
    - NotToDoList: Don't get frustrated or annoyed for stupid things, chill

    ## Week 23
    ### Weekly Goals
    - Must: Focus more on Malin
    - Should: Complete at least half of the certification book
    - Could: Write at least 1 blog post this week

    - Improve: exercise, concentration and level of energy at the gym
    - NoToDoList: catch yourself when you are getting angry and let it go

    ### Monday 1st
    * Train, meditate, blog redesign
    * Call family
    * Certification book

    ### Tuesday 2nd
    * Train, meditate, blog
    * Certification book

    ### Wednesday 3rd
    * Train, meditate, blog
    * Certification book

    ### Thursday 4th
    - Train, meditate, blog
    - Certification book

    - add books read
        - speed reading
    - update notes web components
    - LinkedIN recommendations

    ### Friday 5th
    - Train, meditate, blog
    - Certification book

    ### Saturday 6th
    - Train, meditate, blog redesign
    - Have fun with Malin

    ### Sunday 7th
    - Train, meditate, blog redesign
    - Weekly review
    - Certification book

</div>

It goes like this. I wake up at 5.30 (have tried waking up before but it doesn't work for me, it is not sustainable), I have breakfast (vitamins, coffee and oatmeal) while I watch a pluralsight course or dev talk, I invariably lose 15 minutes in the loop of death (twitter, facebook, linkedin, gmail, twitter, facebook, linkedin, gmail, tw.....), Malin wakes up and we have an **awesome** good morning hug and kisses, I start a new article or continue writing an article for my blog between 6:00 and 7:00, go to the gym and then get to work around 9:00 am. I get home after work around 18:00 and there's no fixed script, I adapt to the daily situation and try to find time to get stuff done. Between 10:30 and 11:30 I go to bed. Sometimes I medidate before falling asleep.

And this is an example of a weekly review from last week:

<div class="highlight">

    ## Week 22
    ### Weekly Goals
    * Must: Write 2 blog posts this week
        * javacriptmancy series
        * redesign the blog series
            * working on it :)
    * Should: Redesign blog
        * started redesigning and it is going well xD
    * Could: Train and meditate every day of the week
        * trained 5 days this week and meditated also 5 days

    * Improve: Effectivity when I wake up, get started fast!
    * NotToDoList: don't get lost in your thought when you are spending time with beautiful Malin

    ### 3 things that went well
    - good job with the blog
        - wrote one blog post and started another one
        - also worked on the redesign and it went pretty well
    - great job with waking up early, training and meditating!

    ### 3 things that did not go so well
    - the weekend was superrelaxing but I feeel like I spent
      too much time playing XD I need to learn how to stop xD I
      should train myself to play timeboxed and obey that time
      boxing. Playing is fun, but you time flies while you are
      playing. It is dangerous! You're life can pass you by playing xD
    - I need to schedule a day to talk with my family. Mondays?

    ### What am I going to do to improve?
    - schedule a day to talk with family and stick to it
    - timebox playing and stick to it!

</div>

I try to think of every day, every week, every month as a clean slate. It doesn't matter if I have screwed up, if I haven't lived up to my expectations or goals. **Every day I have the chance to start over and kick ass.**

### [](#work)Work

#### [](#yearly-goals)Yearly Goals

Since _work_ is a more specific area than _Home and life_ it has much more specific goals. Again I set 3 specific work related goals (in agreement with my employer if possible and after discussing what are their expectations of me).

[![The System Git Things Done and vim at work](https://res.cloudinary.com/practicaldev/image/fetch/s--1TF5mOWN--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.barbarianmeetscoding.com/images/gitthingsdone-vim-work.png "The System Git Things Done and vim at work")](https://res.cloudinary.com/practicaldev/image/fetch/s--1TF5mOWN--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://www.barbarianmeetscoding.com/images/gitthingsdone-vim-work.png)

These are my yearly world for 2015 at work:

<div class="highlight">

    ## Goals
    1. 90% bel√§ggning // 90% allocation to projects as a consultant
    2. MCSD before May
    3. Write 32 blog posts this year (on JS :))
        - Stretch goal: Write a book on JavaScript for .NET developers before October
    4. Become a ninja in front-end development -> Kompetensutveckling fokuserad i front-enden
        - Break down into topics
            - OOCSS
            - CSS frameworks
                - Bootstrap
                - Semantic UI
                - Material Design
                - Foundation
            - JavaScript
                - Angular
                - Aurelia
                - React
            - Front-end DevOps
                - Browserify/Jetpack
                - Yo, Grunt, Gulp, Bower
            - UX
            - Design
            - etc

</div>

They align with some of my personal goals which is definitely a good thing to do (ever tried rowing in two different directions at the same time?).

#### [](#monthly-overview-and-weekly-overview)Monthly Overview and Weekly Overview

The monthly and weekly overviews work exactly like at home. I pick 3 goals, one thing to improve and one thing to stop doing:

<div class="highlight">

    # Juni 2015 - *When we completed KMD project in an AAAWESOME way*
    ## Goals
    - Must: Complete Azure/web services certificate
    - Should: Do an awesome job with the last month in the KMD project
    - Could: Do a great job with the handover to the Polish team

    ## Week 23
    ### Goals
    - Must: Create a great component library
    - Should: Help martin and jonas as best as I can
    - Could: Study like a boss for the certification

    - Improve: fix vim plugins

</div>

In contrast with how I plan at home, I do not plan a week in advance at work. There are too many shifting priorities and things out of my control to have a good enough view of what I will be working on each specific day.

#### [](#daily-overview)Daily Overview

Each day when I get to the office I spend at least the first 15 minutes planning out the day. I review my mail (don't get too much of it so it is not a sink of time), go through my backlog of actions, things that I didn't complete the day before, and I pick up 3 things to do that would add the most value to the project at this point in time.

<div class="highlight">

    ### Thursday 4th
    // As a consultant some of our customers value to have a very clear
    // picture of how I spend my time
    // so I have added this header since I started at Active
    09:00 -> 9:30 (30m) startup
    09:30 -> 10:00 (30m) smoke test
    10:00 -> 10:30 (30m) meeting standup
    10:30 -> 11:00 (30m) meeting maria
    11:00 -> 11:45 (45m) component library
    12:10 -> 13:20 (1h30m) component library
    14:30 -> 16:30 (2h) component library

    * Startup
        * Mail
        * Actions
        * Goals

    * Must: Component library
        - Introduction
            * objectives
            * OOCSS
            * inuit
            * add support for syntax highlighting
            * add auto TOC
            - add examples of OOCSS
            - About adding other libraries (bootstrap, foundation, etc)
        - CSS
            - grids
                - normal grid
                - flexbox grid?
            - forms
                - styles
                - custom html helpers
            - flexbox
            - tables
            - navigation (main, second level, third level)
            - typography
            - utils (mixins)
            - Responsive design
            - Bugs/Workarounds (flexbox ie10)
        - JavaScript
            - organization
            - jquery
                - good practices when using css
            - tables
            - datatables
            - change tracking
            - dialogs
        - About the docs
            - how to maintain them
        - Separate into its own area!!?
    * Should: Make questions to Maria again about facilities
    * Could: Smoke test

    - Read
    https://www.linkedin.com/pulse/s%C3%A5-bygger-du-starka-team-och-fantastiska-produkter-anna-stam

    - Important improvements
        - update template so it has the same indentation that in the main branch (easier diffs)
        - think about baselining all grids items (inline grid)

    - refactor tableList
        - javascripts, extract url generation (separate baseUrl from params...)
        - layout improvements
            - member stat defition -> show string when it is not available (this kund doesn't have member statistics)

    - LEARN
        - Read more about ems and rems!!!

    - Wrapup
        - Time report
        - Reflect
            - What went well today?
            - What didn't go so well?
            - What am I going to do to improve?
            - Did I help anyone?

</div>

During the day I may change priorities based on things that are happening around me and I may take notes of possible improvements, things that I'd like to do in the future, things that I should improve and learn more about.

At the end of the day I try to make time for doing a little reflection. For instance:

<div class="highlight">

    - Wrapup
        - Time report
        - Reflect
            - What went well today?
                - good job in estimation meetings, bringing up ideas, approaches, questions, etc
                - good job setting the foundation for the component library
            - What didn't go so well?
                - little bit slow with the component library
            - What am I going to do to improve?
                - continue contributing and speaking up
                - focus on the most important things first, don't get stuck fixing small things of marginal importance
            - Did I help anyone?

</div>

These goal-setting and recording have a nice side-effect at work as well, I can, at any point in time, show what I have been working on every day, of every week, of every month, of every year at a given company.

### [](#help-to-make-decisions-life-purpose-values-and-principles)Help To Make Decisions, Life Purpose, Values and Principles

Spending some time to reflect on how you are, how you want to be, which is your life purpose, which are your values and principles helps you have more active and conscious part in your development and also make decisions when you are about the business of living life.

These are mine. As you may notice, some are still under development:

#### [](#purpose)Purpose

<div class="highlight">

    # Purpose/Meaning system

    - I want to make the world a better place (not so S.M.A.R.T.)
        - Start with the people near to me
            - Live in the present
            - Be mindful and reflective
            - Enjoy every minute activity/thing
        - and increase/amplify IMPACT through my career and being an entrepeneur
        - WHY?
            - Because it's a worthy way to find purpose in life
        - HOW?
            - Building useful things as a software developer/entrepeneur
            - Building beautiful/inspiring things as a software developer/entrepeneur
            - Teaching/inspiring others to create awesome things
            - By being kind to the people around me
            - By championing worthy causes in my everyday life: sustainability, feminism, healthy lifestyle, etc

    ## Purpose/meaning in different areas
    ### Professional:
    - I want to be the most-awesome/best developer in the universe
        - WHY?
            - So that I can build awesome things and teach/inspire other ppl
            - Because I love developing and I am good at it
        - HOW?
            - Improve myself in software development
    - I want to inspire other ppl to be awesome developers
        - WHY?
            - To empower others to
            - Enabling others adds another dimension to my work and has a great impact
        - HOW?

    ### Entrepeneur:
    - I want to build useful/beautiful/inspiring things that make people happy and people lifes easier
        - Useful applications
        - Meaningful applications
        - Art and Games

    ### People around me:
    - I want to be kind, helpful and inspiring to the people around me

    ### Family:
    - I want to be loving, kind, helpful, supportive, present and inspiring to my close family

    ### Be a Champion of worthy causes:
    - I want to be a champion to the worthy causes of this world

</div>

#### [](#values-and-principles)Values and Principles

Values are not very actionable things, so I like to focus on principles. I have three core principles that I like to follow. These are:

<div class="highlight">

    - Principles:
        - Core
            - Be awesome
            - Be kind
            - Be a leader (help other people be awesome)

</div>

They are aspirational and mean:

*   **Be awesome**: whenever you do something put your heart and soul into it. Try to do the best job you can. Have pride in your work and in anything you do. Aim to awe, aim to put that little extra that makes a world of difference,
*   **Be Kind**: be nice to people, be empathic, care about other people,
*   **Be a Leader**: enable other people, help other people become awesome.

And then I have a ton of sub-principles that I try to live by. I re-read them often and work to internalize them:

<div class="highlight">

    - Principles - All:
        - When I get sad, I stop being sad, and be awesome instead
        - Life is short. Live your dream and share your passion
        - Be kind to people, smile, be positive, spread joy around you.
          At the same time, realize that you don't have to please everyone
        - Anything is possible, you make your own reality, you are
          in control of your life. Don't ever feel like you don't have a choice
        - Sell yourself well, don't be too humble
        - Don't put energy into things you don't want more of
        - Make small projects of every endeavour. Define goals and deadlines.
          Remember Parkinson's laws, every task extends itself to complete
          the time you have allocated for it.
        - Enjoy life! It's a short trip! Don't take things
          too seriously! Loosen up!
        - Don't forget the 20/80% rule, 20% of the effort provides
          80% percent of the results
        - Be curious. Always find the why of things! Question everything
        - Always strive to improve things and yourself,
          don't shut up, express your opinions
        - Get outside of your comfort zone. Make it a habit!
        - Sharpen the saw. Practice smart. Practice Perfect.
          How you perform daily is a reflection of how you practice
        - Be diligent, have discipline, a little bit of work
          every day makes a huge difference in the long term
        - Believe in people. People are not out to get you,
          people are just like you with their own needs, wants and insecurities
        - See obstacles and change as opportunities. Before
          obstacles other people may just give up. You won't.
          You will not give up.
        - Life is short, build stuff that matters
        - Do something that scares you everyday. Challenge
          yourself. You learn/develop the most when you do this
        - Don't waste time feeling sorry for yourself. Take responsibility
          for your life
        - Don't give away your power. You are in control of your own emotions,
          you have a choice. No one can make you feel bad unless you let them
        - Don't waste energy on things you cannot control. Focus on
          what you do control
        - Don't shy away from change. Change means new opportunities
          and things to learn
        - Don't dwell on the past and wish things were different.
          Live for the present and plan for the future
        - Don't make the same mistakes over and over. Reflect and learn
          from your mistakes
        - Don't resent other people's success. Recognize real success
          comes with hard work
        - Don't give up after the first failure. Be persistent
          and determined. Have true grit
        - Don't feel the world owes you anything. You are not
          entitled to anything, it is up to you to go out and take it
        - Be a leader. Help and inspire other people to be better
        - Have your own opinions
        - Don't expect other people to agree with you. You are
          a salesman of your ideas
        - Don't be arrogant. Think about other people and other
          people's proposals beyond your prejudices and preconceptions
        - Think about the big picture! Don't get always captured in the detail
        - Acknowledge people.

    - new principles
        - It's easier to bleed than to sweat.
        - Build habits. Make harder/painful to have negative habits.
          Make easier/pleasureable good habits. Work on creating the
          path of least resistance to the things that you want to work
          on for real.
        - Die empty. Ask yourself, what do I want to do before I die,
          and do it. Ask yourself, if this was the last day I got to live,
          what would I do? Would I do anything differently?
        - Do the Work, no matter what, Do the work
        - Every obstacle is an opportunity. Every time that something
          bad happens to you, don't get angry, don't get scared,
          stop yourself, think, reflect and find the opportunity
          within the obstacle, find a way to grab that obstacle and
          turn it to your advantage
        - Train your willpower every day. When you feel a urge of
          something that is not really good for you, wait 10 minutes
          and see if it is really that important that you satisfy it.
        - People doesn't know what you know. Don't get offended if
          someone thinks you don't know something. People usually
          mind about themselves, not about you. You need to have a
          very strong branding or be freaking famous before ppl give
          a damn, and even then... xD So chill dude... and sell yourself
          cause no-one else is going to do it for you.

</div>

### [](#reflecting-and-continuous-improvement)Reflecting and Continuous Improvement

Every good system needs a mechanism for improvement. Mine is to reflect often (daily, weekly, monthly, yearly), ask periodically for feedback, be humble, find things that can be improved and improve them.

When I reflect daily I try to answer these questions:

*   What went well today?
*   What didn't go so well today and could be improve?
*   What am I going to do to improve?
*   Did I help anyone today? Did I do any good deed?

When I reflect weekly, monthly and yearly I go through my goals. Write comments and notes in each one of them and I try to answer these questions:

*   3 things that went well and should continue doing?
*   3 things that did not go so well and should be improved?
*   What am I going to do to improve?

### [](#other-supporting-sources-and-techniques)Other Supporting Sources and Techniques

Some other stuff that I do to complement the previously mentioned techniques:

*   I use additional notes for bigger projects and individual topics that I'd like to focus on separately. For instance I have separate notes for my blog, shortcuts that I am trying to learn in my favorite IDES/editors, retrospectives within a project at work, etc.
*   Use the pomodoro technique when I have a hard time focusing.
*   Always have a moleskine notepad with me to take notes whenever I need/want to
*   Handle my mail and incoming flow of things in a very similar way to the one proposed in GTD (Do it, Defer it, Delegate it)
*   Listen to audiobooks on the commute, when I am making the laundry or washing the dishes
*   Meditate

#### [](#a-project-example-blogging-at-barbarian-meets-coding)A project example: Blogging at Barbarian Meets Coding

When I tackle bigger projects I create a separate markdown file and I write a series of things:

*   Why am I pursuing this project?
*   What do I expect to get from it?
*   Does it have a time limit? a specific goal? if so, what will it look like to have completed it?
*   Goals, ToDos, Steps, Ideas, Scripts

I usually start by defining why I am pursuing a project and what do I expect to get from it. In the case of blogging:

<div class="highlight">

    # Why do I Blog?

    *I blog first and foremost to share my passion and
    enthusiasm for software development*.

    I blog:
    *  for myself in the first place, for FUN
    *  because it helps me materialize my thoughts and
       reflect in a very deep way
    *  to share my passion and enthusiasm for software development,
       contagiate others!
    *  to spread the word about the awesomeness of developing software,
    *  to share information about great libraries,
       frameworks, best-practices and great ideas,
    *  to make the software developer community better,
    *  to share my projects and ideas with others

    ## What do I want to get across when I write a blog post

    * Fun
    * Value proposition, how will it improve your life

</div>

I also write down goals, To-Dos, ideas:

<div class="highlight">

    # Ideas
    ## Up and Coming

    - Work on blog redesign
        - Improvements
            - startpage
                - header/sidebar
                    - conan background with opacity gradient
                    - increase size on hover of all anchor tags
                    - use floats instead of inline blocks in main menu
                - navigation
                    - main style
                    - add RSS
                    - add search
                - main area
                - social
                - current
                    - books reading
                    - twitter, etc...
                    - working on
            - Do something about the size of images. Optimize all of them. Find a nodejs tool or something to fix it permanently
            - blog/article views
            - archive
            - Mobile site
            - Tablet site
            - smaller improvements
                - good description in every page (like beginning of article)
                - hierarchy of navigation
                - optimize mobile experience

    - Next
        - new blog post series -> redesigning barbarian meets coding - step by step
        - javascript function patterns -> function overloading
        - barbaric tip of the week: emmet on web essentials
        - Dev talk monday on Chris Klug
        - Brief blog post on Peter Orneholm on Application Insights
        - Wiki. Concepts explained. What do I think words mean? For instance UX, or other stuff?  Have a clear concept in your mind

    - SHORT blog posts
        - Tip of the week
            - Web essentials features
            - ReSharper plugin
            - ReSharper feature
            - Vim feature
            - Vs plugins
        - Death by a thousand cuts
        - Kill all your notifications
        - Frontend monthly: CSSPen of the month
            - Look at a pen every month and talk about APIs used
        - Dev talk monday on Chris Hellman everything is awesome

    - LONG blog posts
        - OOCSS
        - Yo part 1, yeoman as a user
            - update: note about npm on windows (look github docs)
        - Blog about REST
            - review of the book
                - interactive video with fast-paced drawing
                    - that would be cool as hell xD
                    - http://www.videoscribe.co/buy
            - interactive documentation knockout.js
        - Knockout components blog post with examples!!!!
        - Blog -> SEMANTIC UI
        - Blog review about REST book
        - Yo part 2, writing a yeoman generator
        - Yo part 3, looking at the source code
        - Update thoughts on javascript allonge
            - separating iterating over a data structure and doing something on the data structure
        - Disclaimer to wiki sites
        - Review principles and Blog on Principles but now like a nice animated book?
        - What I learnt from every self-improvement books from 2014
        - Programming books from 2014
        - Barbaric Basics
            - HTML5, CSS, JavaScript basic apis
        - Add to reading now a link to all that I have read during the year

    # BACKLOG Of Ideas - To Categorize

    ...

</div>

And I write scripts as I find ways to improve what I am doing within the project:

<div class="highlight">

    # Blog post Checklist
    Hi Jaime, read this before you write a new blog post! ;) You'll do fine

    1. TL'DR' in the beginning (good idea)
    2. Think about one and only one person when you write an article, the person that represents your target market
    3. Tell a story whenever you can, stories are interesting and captivating
    4. Have a good structure
        - Catchy title
        - Introduction/Setup
            - What am I going to write about?
            - Write it in a way that is both informative, appealing and seductive
        - Content/Confrontation
            - Add some interesting, unexpected facts or demos
        - Conclusion/Reminder/Resolution
            - Summarize the whole post in one single paragraph
    5. Checklist
        - Add an image
        - Review it at least twice before you push it to the world
        - Do you tell a story?
        - Be yourself. Can you recognize yourself when you read it?

    6. Every month -> check stats -> which posts get more views?

</div>

I also write [lots of information for later reference within my wiki](http://www.barbarianmeetscoding.com/wiki/).

#### [](#using-the-pomodoro-technique)Using The Pomodoro Technique

I have found [the pomodoro technique invaluable](http://pomodorotechnique.com/) but I use it in periods depending the type of project that I am working on and how is the existing team dynamic.

I use a [small knockout.js pomodoro client](http://www.barbarianmeetscoding.com/iPomodoro/)(alpha version) that I built a loooong time ago. After I have set my daily goals, I copy them to the pomodoro client, estimate them, and start working through them pomodoro by pomodoro.

### [](#no-longterm-goals)No Long-term Goals?

You may be wondering why I don't have any long-term goals answering the classic _where do you see yourself in 5 years?_ question. Well, to be honest, I haven't thought of that, but thus far, the life purpose ideas seem to be a good pointer regarding where I want to be in the future.

### [](#cool-references)Cool References

A lot of the ideas that I have incorporated in my personal productivity system come from well established books and authors. Some of these are:

*   [Getting things done](http://amzn.to/1eRTozv) - David Allen
*   [Getting results the agile way](http://amzn.to/1KHwHIi) - J.D. Meier
*   [The 7 Habits of Highly Effective People](http://amzn.to/1Ju8aru) - Stephen R. Covey
*   [The Pomodoro Technique](http://pomodorotechnique.com/) - Francisco Cirillo
*   [Linchpin: Are you Indispensable?](http://amzn.to/1KHwLHW) - Seth Godin
*   [Tribes: We Need You to Lead Us](http://amzn.to/1Gnp1Ns) - Seth Godin
*   [Practice Perfect: 42 Rules for Getting Better at Getting Better](http://amzn.to/RAufLY) - Doug Lemov
*   [The Power of Habit: Why we do what we do in life and business](http://amzn.to/1KHwQvg) - Charles Duhigg
*   [The First 20 Hours](http://amzn.to/1Ju8iY0) - Josh Kaufman
*   [Start With the Why: How Great Leaders Inspire Everyone to Great Action](http://amzn.to/1KHwWTI) - Simon Sinek
*   [Die empty](http://amzn.to/11aV0x9) - Todd Henry
*   [Mindset: The New Psychology of Success](http://amzn.to/112qmWt) ‚Äì Carol Dweck
*   [Flow: The Psychology of the Optimal Experience](http://amzn.to/1vHXwVd) ‚Äì Mihaly Csikszentmihalyi
*   [Drive, The Surprising Truth About What Motivates Us](http://amzn.to/1z6HRSM) ‚Äì Daniel H. Pink
*   [The New Psycho-Cybernetics](http://amzn.to/1pxL4rg) - Maxwell Maltz
*   [The Dip](http://amzn.to/1mxd4Xl) - Seth Godin
*   [How to Fail at Almost Everything and Still Win Big: Kind of the Story of My Life](http://amzn.to/1km9EcR) - Scott Adams
*   [The Obstacle is the Way](http://amzn.to/1vvq5UX) - Ryan Holiday
*   [The War Of Art: Break Through the Blocks and Win Your Inner Creative Battles](http://amzn.to/1Gw40Pr) -
*   [The 4 Hour Work-Week](http://amzn.to/TNRQFE) - Timothy Ferris
*   [Zen to done: The Ultimate Simple Productivity System](http://amzn.to/1KHx31G) - Leo Babauta
*   [Without Their Permission: How the 21st Century Will be Made Not Managed](http://amzn.to/1GnpfUO) - Alexis Ohanian
*   [ReWork](http://amzn.to/1Ju8x5r) - Jason Fried

Particularly, I feel like I have borrowed many of my techniques from [Getting Results the Agile Way](http://amzn.to/1KHwHIi) and J.D. Meier.

## [](#concluding)Concluding

And that was _"the system"_, **GitThingsDone**, in a nutshell. It is an important part of my life that has helped me get more stuff done, become a better person and get more out of my life in the past years.

If you'd like to start doing something similar but you don't know where to start, just pick your 3 big wins for the day, the 3 things that would add the most value to your life/work and would make you happy about your day after having completed them. After that add some periodic time for reflection and build your own system from there.

Do you have your own productivity system? Any technique or idea that you'd like to share? Feedback is more than welcome!
