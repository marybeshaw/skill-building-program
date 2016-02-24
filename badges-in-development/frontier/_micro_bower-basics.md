# Bower Basics - Micro Badge

-----

Est. to complete: 3hrs

## Goal
- You should be able to install and manage Bower packages from the Bower registry.
- You should be able to install private dependencies from Github.
- You should be able to use `bower link`.
- You should know how to reference your Bower packages.
- You should know how to manipulate the bowerrc file.
- You should know the parts of the bower.json file.


-----

## Intro

>Bower - A package manager for the web.

Bower is a way of installing and managing front-end packages in your apps. It works much like npm in how you install and reference packages. Bower has its own registry of packages accessible to all, but you can also use it to install a private github repo as a dependency. There's a bower.json file that works much like npm's package.json, and a bowerrc file for managing what it does with your packages and where to put them.

For more information on how Bower is used in Frontier, check out the [Bifröst Docs](https://github.com/fs-webdev/frontier-build-tools/blob/master/Bifrost.md#bower-and-3rd-party-libraries)

-----


## Suggested Assignment
In your Frontier Skills app, do the following:

1) Demonstrate that you can install and reference bower packages.
  - [ ] Install a package fromt the Bower registry.
  - [ ] Create a package and install it from a github repo.
  - [ ] Create another package and use `bower link` to install it in your app.
  - [ ] You must be able to explain how to use each of these three methods and when you should use them.

2) Demonstrate your ability to manipulate the bowerrc file.
  - [ ] You must be able to explain the order of importance into which the config is merged from various configuration sources.
  - [ ] Change the directory into which your bower components are installed.
  - [ ] Use a "preinstall" "postinstall" or "preuninstall" hook to perform an action in one of those situations.

3) Demonstrate knowledge of the bower.json file.
 - [ ] Explain what role the bower.json file plays.
 - [ ] Explain the different pieces of a bower.json file.
 - [ ] Explain how `bower update` affects the bower.json file.
 
4) Demonstrate proficiency at the bower API
 - [ ] Use three differenct API commands other than install, uninstall, init, or link.


-----


## Suggested Study

### Web
- [Bifröst Docs](https://github.com/fs-webdev/frontier-build-tools/blob/master/Bifrost.md#bower-and-3rd-party-libraries).
- This [article](https://oncletom.io/2013/live-development-bower-component/) about `bower link`.
- The [Bower](http://bower.io/) Website has all the docs and api things you need to know.
- This [Guide](http://blog.teamtreehouse.com/getting-started-bower) on getting started with bower.
- Another great [Intro](http://code.tutsplus.com/tutorials/meet-bower-a-package-manager-for-the-web--net-27774) on tutsplus.
- [Article](https://css-tricks.com/whats-great-bower/) on Css Tricks about why Bower is awesome.


-----

  *Is this badge missing something? Submit a PR and review it with a master in this category*
