# JavaScript - Linting & JS Style Guide

-----

Est. to complete: {X}hr recommended: 1-6hrs per micro)

## Goal
- You have demonstrated the basic foundations in JavaScript Linting & the JS Style Guide.
- You should know about linting rules, leading commas, hoisted vars and the like.


-----

## Intro

>While static code analysis tools can spot many different kind of mistakes, it can't detect if your program is correct, fast or has memory leaks. You should always combine tools like JSHint with unit and functional tests as well as with code reviews. - JSHint.com/about

There are two main ways we enforce consistent code. Code Linting and Language Style Guides. FamilySearch suggests you use JSHint and adopt at least the default ruleset in our FS . jshintrc file. You may be more agressive as you see fit. We also have a JS style guide, which the web developers have created by agreeing on a short set of guidelines and conventions we would all like to see in our code.

-----


## Suggested Assignment(s)
Choose one (or more):

1) Implement JSHint in your editor
  - [ ] Grab the FS .jshintrc config file (need to make this first. stash in ref docs policy)
  - [ ] Put it in your project's root dir
  - [ ] Install jshint plugin for your editor
  - [ ] Demonstrate some code you've fixed after using JSHint

2) Implement JSHint in your devtime CI tests
  - [ ] Grab the FS .jshintrc config file (need to make, stash in ref docs policy)
  - [ ] Put it in your project's root dir
  - [ ] Make a build task and a watcher for it that run JSHint against your project files on changes
  - [ ] Demonstrate some code you've fixed after using JSHint

3) Implement JSHint in your deploytime tests (figure out how best to do this)
  - [ ] Grab the FS .jshintrc config file (need to make, stash in ref docs policy)
  - [ ] Put it in your project's root dir
  - [ ] Set a JSHint script to run during the build step of a deploy, and halt the build on a failure


-----


## Suggested Study

### Web
- [jshint/.jshintrc at master · jshint/jshint · GitHub](https://github.com/jshint/jshint/blob/master/examples/.jshintrc)
- [Download and install - JSHint](http://jshint.com/install/)
- [gulp-jshint - npm](https://www.npmjs.com/package/gulp-jshint)
-


-----

*Is this badge missing something? Submit a PR and review it with a master in this category*
