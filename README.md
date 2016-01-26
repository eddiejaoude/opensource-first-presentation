# Open Source First Presentation

We talk about Mobile or API first, why not Open Source First. What does this mean? It means you must think about the wider audience first and not just your private needs.

For example:
* The README must contain Installation instructions
* Each commit message must be descriptive
* Each committed files must be related to that commit
* Secure information must not be committed 
* De-coupled Architecture

Using [RevealJS for Slides](https://github.com/hakimel/reveal.js)

## Topics /  Areas

- [ ] Introduction(s)
    - [ ] Background(s)
    - [ ] Few facts
- [ ] Personal
    - [ ] Constantly learning
    - [ ] What we know today might be wrong tomorrow - signs of a good developer...look back at code and see many ways to improve it
- [ ] GitHub - code, issues, wiki, graphs & zenhub
    - [ ] Markdown quickstart - used for comments/wiki/pull requests
- [ ] When using an Open Source project
    - [ ] Before you use / add it as a dependency to composer/npm etc, have a good look
    - [ ] README - does it look like they know what they are doing? Installation etc
    - [ ] Stars / Forks
    - [ ] Regular & recent useful commits (don’t want a dead/dying) project
    - [ ] Issues - have there been comments, bugs fixes etc
    - [ ] Pull Requests - have there been PRs accepted and rejected - rejected is also important
    - [ ] Automated tests! I won’t use a project that has no automated tests & CI
    - [ ] If you are unsure, de-couple your code from their code!
        - [ ] No inheritance
        - [ ] Adapter design pattern
            - [ ] 
        - [ ] Tests will be much simpler
        - [ ] Fork to have a copy
        - [ ] If you need to make changes to the original, Fork and create a PR, use your Fork in your package manager (do not break your upstream so you can pull in their improvements - roject, must be easy for people to understand & navigate your project
    - [ ] Demo / Diagrams (flow / swim lanes / architecture)
    - [ ] Important documentation
        - [ ] README.md - installation instructions, faqs,
        - [ ] CONTRIUBTION.md
    - [ ] Repo
        - [ ] Issues created by public, reply with comments
        - [ ] Stars & Forks - the more you have the more likely you will get more (snow ball)
        - [ ] Branches
        - [ ] Releases
        - [ ] Badges
    - [ ] Vagrant
        - [ ] No need to install dependencies manually
        - [ ] Correct versions - Java, PHP etc
        - [ ] Lower the barrier to entry
    - [ ] Also good for future jobs / employers to see your work
- [ ] Git flow's branching model
    - [ ] Branching is amazing, but must be short lived!
- [ ] Automated tests
    - [ ] Unit (ideally Spec) & code coverage (just a guidance)
    - [ ] BDD
    - [ ] This also helps with Architecture and smaller classes with Single Responsibility (eg. Adding Adapters)
    - [ ] DI - good for mocking & for using in de-coupled way
- [ ] Releases (inc. Packages) & Changelog
- [ ] CI (and maybe CD)
    - [ ] Static code analysis
