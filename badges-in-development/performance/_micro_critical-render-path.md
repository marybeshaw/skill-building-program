Performance - Critical Render Path [Micro Badge]
================================================


Goals:
------

- You have demonstrated the basic foundations in Performance - Critical Rendering Path.
- You should know about a few loading patterns, and how to prioritize the Critical Rendering Path is.


Intro
-----

Google defines the Critical Path as:  
> the code and resources required to render the initial view of a web page

Blank loading pages can't make conversions. We care about the user, and it hurts our relationship with them and our conversion numbers if they are served these kind of experiences. Get the critical pixels to the user ASAP.

**Loading Patterns:**  
  - Serial loading (blocking loading)
  - Async loading (non-blocking loading)
  - Progressive loading (load critical items, then load non-critical items)
  - Lazy-loading (load an item on-demand, such as "on click" or "on visible")


Suggested Assignment(s)
---------------------

Choose one:

1) Complete the free Website Performance Course at Udacity
  - [ ] watch all the videos and peruse the links [Website Performance Optimization Testing Course - Udacity](https://www.udacity.com/course/ud884)
  - [ ] Demonstrate your final project. It must pass the requirements Ilya gave you at the beginning of the course
  - [ ] Discuss your findings about critical render path strategies, and loading patterns

2) Read all suggested study items below, and demonstrate what you've learned with a simple coding project
  - [ ] Read all suggested study items below
  - [ ] Build a simple code demonstration that demonstrates each of the Loading Patterns from the intro above
  - [ ] Build a simple code demonstration on Express.js that delivers 5+ 300px+ images, and several large paragraphs of text from web sources with a pagespeed score of under 800. Use critical and non-critical items.
  - [ ] Demonstrate these things and discuss what you've learned


Suggested Study
---------------

### Web
- [Critical render path and pagespeed: An in-depth ... - Feedthebot.com](http://www.feedthebot.com/pagespeed/critical-render-path.html)
- [Optimizing the Critical Rendering Path - Velocity SC ... - Google Docs](https://docs.google.com/presentation/d/1IRHyU7_crIiCjl0Gvue0WY3eY_eYvFQvSfwQouW9368/present)
- [Performance Calendar » Deciphering the Critical Rendering Path](http://calendar.perfplanet.com/2012/deciphering-the-critical-rendering-path/)
- [Critical Rendering Path — Web Fundamentals - Google Developers](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/)
- [Analyzing Critical Rendering Path Performance — Web Fundamentals](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp)
- [Website Performance Optimization Materials - Udacity](https://www.udacity.com/wiki/ud884)
- [The performance best practices rules used by Sitespeed.io](http://www.sitespeed.io/rules/)
