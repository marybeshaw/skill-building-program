Performance - Image Optimization [Micro Badge]
=============================================


Goals:
------

- You have demonstrated the basic foundations in Performance - Image Optimization.
- You should know how to handle different image types "performantly", and use different loading methods to optimize their effect on the page's performance.


Intro
-----

> Images often account for most of the downloaded bytes and also often occupy a significant amount of the visual space on the page - Google Web Fundamentals

We notice when our javascript code gets bigger than 100kb, but we don't always notice multiple images of the same file-size. Images represent one of the largest performance improvement opportunities on a page, since they often have large file-sizes, take a lot of visual space above the fold, and can be found poorly optimized quite frequently. Let's get our images fit and trim and see what a difference it makes.


Suggested Assignment(s)
--------------------

Choose one:

1) Improve the Speed Index or Page Load Time of a page by optimizing its' images
  - [ ] Audit page's images. Record how many files, how much file-size they have when combined, and how long they take to download.
  - [ ] Are there any images that could be optimized further?
  - [ ] What percentage of the page's total file-size are image bytes?
  - [ ] What recommendations do your audit tools give you? (yslow, chrome dev tools, page speed insights)
  - [ ] Optimize image files as aggressively as you can without degrading the visual quality "too low" (subjective measurement)
  - [ ] Demonstrate what improvements these changes made to the page's performance metrics, esp. speed index and page load time

2) Improve the Speed Index or Page Load Time of a page by optimizing how it loads images
  - [ ] Audit page's images, and images' impact on page metrics, esp speed index and page load time
  - [ ] What percentage of the page's total file-size are image bytes?
  - [ ] What recommendations do your audit tools give you? (yslow, chrome dev tools, page speed insights)
  - [ ] Remove the largest images from the page temporarily, test again. How do the metrics change?
  - [ ] Optimize the number of images, and use "lazy-loading" for any images loading "below the fold" in your statistically typical viewer size.
  - [ ] Demonstrate what improvements these changes made to the page's performance metrics, esp. speed index and page load time


Suggested Study
---------------

### Web
- [Optimize images for performance — Web Fundamentals - Google](https://developers.google.com/web/fundamentals/media/images/optimize-images-for-performance)
- [Image optimization — Web Fundamentals - Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
- [Image performance - O&#39;Reilly Radar](http://radar.oreilly.com/2014/01/image-performance.html)

### Tools
- [Tools for image optimization - AddyOsmani.com](http://addyosmani.com/blog/image-optimization-tools/)
- [Grunt And Gulp Tasks For Performance Optimization | Yeoman](http://yeoman.io/blog/performance-optimization.html)
- [JPEGmini - Your Photos on a Diet!](http://www.jpegmini.com/)
- [Lazy Load Plugin for jQuery - Mika Tuupola](http://www.appelsiini.net/projects/lazyload)
- [Lazy Loading Images | CSS-Tricks](http://css-tricks.com/snippets/javascript/lazy-loading-images/)
- [jQuery Unveil - A very lightweight plugin to lazy load ... - Luis Almeida](http://luis-almeida.github.io/unveil/)

-----

  *Is this badge missing something? Submit a PR and review it with a master in this category*
