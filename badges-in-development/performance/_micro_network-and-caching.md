Performance - Network & Caching [Micro Badge]
=============================================

Est. time to complete: 2hr

Goals:
------

- You have demonstrated the basic foundations in Performance - Network & Caching.
- You should know how to audit multiple aspects of browser networking and caching.


Intro
-----

> Good developers know how things work.  
> Great developers know **why** things work. - Steve Souders

Browser networking and caching can seem like black magic sometimes. Let's dive into things, pull them apart, and put them back together so we can have a better knowledge, and make better-informed decisions about how we build our code, and how things affect it.


Suggested Assignment(s)
--------------------

Choose one:

1) Prove your knowledge
  - [ ] Discuss some of the 6 Steve Souders HTTP/1.1 networking optimizations: [Chapter 11. HTTP 1.X - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch11.html)
  - [ ] Discuss the "Evergreen Performance Best Practices". Why are they considered "evergreen"? [Chapter 13. Optimizing Application Delivery - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch13.html)
  - [ ] How will HTTP/2 affect current HTTP/1.1 optimizations? Which 1.1 optimizations will go away? [HTTP/2 in 5 minutes](https://www.youtube.com/watch?v=fJ0C4zN5uOQ)(video)
  - [ ] Discuss different caching headers. Describe what network activity happens in each case. [Beginner's Guide to http Cache Headers](http://www.mobify.com/blog/beginners-guide-to-http-cache-headers/)
  - [ ] How could you guarantee that an unchanged file is not downloaded by a user's browser more than once per year?
  - [ ] Describe how a mobile phone's radio use on the web affects battery use. What network data flow behaviors are more desirable for mobile usage? Progressive and sporadic downloads, or all of the downloads up front in a big chunk (given same total of data)? [Chapter 8. Optimizing for Mobile Networks - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch08.html)
  - [ ] How long can the latency overhead of an HTTP request be on 3G and 4G mobile networks? [Chapter 8. Optimizing for Mobile Networks - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch08.html)
  - [ ] What methods can you use to attempt a sub-one-second page render on a mobile device? https://developers.google.com/speed/docs/insights/mobile
  - [ ] Demonstrate in browser dev tools some cached and uncached responses, show expires headers and what they mean to the page load. Demonstrate some gzipped and non-gzipped responses.
  - [ ] Simulate a slow mobile page load, and in dev tools demonstrate the exaggerated network behavior. [Device Mode & mobile Emulation - Chrome Dev Tools](https://developer.chrome.com/devtools/docs/device-mode) (video/article)
  - [ ] Between latency and bandwidth, which is the more restrictive bottleneck of a typical page load?
  - [ ] Describe some overall generalizations you have noticed among all of these study materials.



Suggested Study
---------------

### Web
- [Chapter 8. Optimizing for Mobile Networks - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch08.html)
- [Beginner's Guide to http Cache Headers](http://www.mobify.com/blog/beginners-guide-to-http-cache-headers/)
- [Chapter 11. HTTP 1.X - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch11.html)
- [HTTP/2 in 5 minutes](https://www.youtube.com/watch?v=fJ0C4zN5uOQ) (video)
- [Chapter 12. HTTP 2.0 - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch12.html)
- [HTTP/2 and a Faster Web](http://www.infoq.com/presentations/http2-linkedin)
- [Chapter 13. Optimizing Application Delivery - O&#39;Reilly Media](http://chimera.labs.oreilly.com/books/1230000000545/ch13.html)
- [Leverage Browser Caching - Google Developers](https://developers.google.com/speed/docs/insights/LeverageBrowserCaching)
- [Optimize caching - Make the Web Faster — Google Developers](https://developers.google.com/speed/docs/best-practices/caching)
- [Minimize round-trip times - Google Developers](https://developers.google.com/speed/docs/best-practices/rtt)


### Tools
- [Chrome Developer Tools - Google Chrome](https://developer.chrome.com/devtools/)
- [Firebug](http://getfirebug.com/)
- [WebPageTest.org](http://webpagetest.org)
- [Device Mode & mobile Emulation - Chrome Dev Tools](https://developer.chrome.com/devtools/docs/device-mode) (video/article)
- [Chrome Web Store - Postman - REST Client - Google](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm)
- [Chrome Web Store - Advanced REST client - Google](https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo)

-----

  *Is this badge missing something? Submit a PR and review it with a master in this category*
