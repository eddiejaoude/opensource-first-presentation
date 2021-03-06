# Open Source First Presentation

We talk about Mobile or API first, why not Open Source First. What does this mean? It means you must think about the wider audience first and not just your private needs.

For example:
* The README must contain Installation instructions
* Each commit message must be descriptive
* Each committed files must be related to that commit
* Secure information must not be committed 
* De-coupled Architecture

## Usage

### Overview / Layout grid

* Press `escape`
* Navigate to slide
* Press `enter` to select

### Speaker notes

* Visit deployed version of slides and press `s` to view speaker's view (inc. notes).

---

## What you will learn

* Personal targets
* How to use GitHub
* What to look for when using an **Open Source** Project
* Best Practices to include & cover in your **Open Source** Project


Using [RevealJS for Slides](https://github.com/hakimel/reveal.js)

And for *revealjs* remote control via [phone](http://remot.io)

---

## Notes: Topics / Areas to cover

GIFs to explain each section

* [ ] What does Open Source mean to you?
    * [ ] To me it means - a transparent community around the same code base and open for anyone to contribute / join etc.
    * [ ] That continues to evolve and more forward as a community & individuals
    * [ ] Benefits of Open Source
        * [ ] Community
            * [ ] Contribution - support, help, feedback, ideas, testing...
        * [ ] Quality is much higher
    * [ ] With so many large & active communities it is easier to build your Applications & focus on your business logic
    * [ ] Output is higher quality & to standards as they know their peers will be observing
    * [ ] Open Source Licensing
* [ ] Personal traits of members
    * [ ] Constantly learning
    * [ ] What we know today might be wrong tomorrow - signs of a good developer...look back at code and see many ways to improve it
    * [ ] You come to events like this! So many dont and are missing out
* [ ] Agile
    * [ ] What you think your users want or will use is probably wrong
    * [ ] Put something in front of them as soon as possible & get feedback (MVP)
    * [ ] Small iterations
        * [ ] Retrospective / Planning (past & future)
        * [ ] Deploy & get feedback
    * [ ] Setup hello world pipeline (eg. GitHub, TravisCI, Deployment)
    * [ ] Quality is always high & production ready (unless prototype)
        * [ ] Fixed date or fixed features, but not both!
    * [ ] Complete the feature before moving on to the next - feature means something providing value
* [ ] Git
* [ ] GitHub - code, issues, wiki, graphs & zenhub
    * [ ] Trending
    * [ ] Not just code, government documents
    * [ ] Beginner tags???
    * [ ] Put GitHub logo up for this section
    * [ ] Markdown quickstart - used for comments/wiki/pull Requests
    * [ ] Templates - Issue / Pull Requests
* [ ] When using an Open Source project
    * [ ] Before you use / add it as a dependency to composer/npm etc, have a good look
    * [ ] README - does it look like they know what they are doing? Installation etc
    * [ ] Single (or few) massive commits
    * [ ] Stars / Forks
    * [ ] Branches are important - dont want experiments in the mainline
    * [ ] Should be using Releases not feature branches or master
    * [ ] Regular & recent useful commits (don’t want a dead/dying) project
    * [ ] Issues - have there been comments, bugs fixes etc
    * [ ] Pull Requests - have there been PRs accepted and rejected - rejected is also important
    * [ ] Automated tests! I won’t use a project that has no automated tests & CI
    * [ ] If you are unsure, de-couple your code from their code!
        * [ ] No inheritance
        * [ ] Adapter design pattern & Interfaces
            * [ ] 
        * [ ] Tests will be much simpler
        * [ ] Fork to have a copy
        * [ ] If you need to make changes to the original, Fork and create a PR, use your Fork in your package manager (do not break your upstream so you can pull in their improvements - project, must be easy for people to understand & navigate your project
    * [ ] Demo / Diagrams (flow / swim lanes / architecture)
    * [ ] Important documentation
        * [ ] README.md - installation instructions, faqs
            * [ ] Prioritise the order, similar to a trailer, need to capture user
        * [ ] CONTRIBUTION.md
    * [ ] Repo
        * [ ] Branches
        * [ ] Releases
    * [ ] Vagrant
        * [ ] No need to install dependencies manually
        * [ ] Correct versions - Java, PHP etc
        * [ ] Lower the barrier to entry
    * [ ] Never make changes to 3rd party source code in your project
* [ ] All participants Register on GitHub repo for the event
    * [ ] One at a time, Fork repo & Create PR
    * [ ] Multiple PRs that have been branched off each other, they will need to be updated to show correct diff
    * [ ] Two at the same time to create conflict
* [ ] Also good for future jobs / employers to see your work
* [ ] Git flow's branching model
    * [ ] Branching is amazing, but must be short lived!
    * [ ] Also to contain everything for that feature - code, test, docs etc
* [ ] Commits
    * [ ] Include ticket number, create a ticket if doesnt exist
    * [ ] Concise / Descriptive message
    * [ ] Do not rewrite history even if not pushed, revert then you still have changes for the future
    * [ ] Include 1 specific change / feature / fix per commit
* [ ] Automated tests
    * [ ] Unit (ideally Spec) & code coverage (just a guidance)
    * [ ] BDD
    * [ ] This also helps with Architecture and smaller classes with Single Responsibility (eg. Adding Adapters)
    * [ ] DI - good for mocking & for using in de-coupled way
    * [ ] When creating a Pull Request, CI will report back to GitHub, do NOT merge until this has gone green - more difficult to pull code out than to put them in
        * [ ] If branched from another Pull Request dont forget to update after the previous one is merged so that it can be more concise
    * [ ] Load testing / Soak testing
    * [ ] Penetration testing
    * [ ] Test data
        * [ ] Development - Sample data
        * [ ] Test - Generated data, eg. Faker / Alice - generates data (name, address etc)
        * [ ]
* [ ] Releases (inc. Packages) & Changelog
* [ ] Hosting
    * [ ] GitHub pages (static)
    * [ ] Heroku for dynamic
    * [ ] Dokku for private heroku
* [ ] CI (Continuous Integration)
    * [ ] Triggered by any commit to any branch
    * [ ] Run automated tests
    * [ ] Static code analysis
    * [ ] Report back & notify
    * [ ] Successful build create tag/release with artifacts
* [ ] CD (Continuous Delivery)
    * [ ] Successful build deploy out to relevant environment
* [ ] Searching for Answers - blog posts / stackoverflow
    * [ ] Check the dates
    * [ ] Not always the answer at the top is still valid, check for newer ones below
    * [ ] Dont copy and paste - understand what it does, you might realise a better way
* [ ] Code will never be finished or perfect, but it can be still be great!
    * [ ] Slow is smooth and smooth is fast!
* [ ] What I look for when interviewing
    * [ ] Active GitHub CVs go to the top of the list
    * [ ] Teamwork & Collaboration
    * [ ] Easy to read CV - spoon feeds me the information I need to see
* [ ] Licensing
    * [ ] http://choosealicense.com
* [ ] Conclusion
    *  [ ] Open Source First
