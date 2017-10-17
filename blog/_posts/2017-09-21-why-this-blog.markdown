---
layout: post
title:  "Why this blog"
date:   2017-09-21 14:23:34
categories: intro 
---
This is really a specialty blog. My real homepage can be found at [beaukinstler.com.][bkcom] 
I've had in the back of my mind and hovering around my to-do list for some time, the desire to try out a Jekyll site.  When I learn new things, I do have the bad habit of trying to tack on or augment the standard intro tutorials, my own problem, or some additional concept that I think or have heard could be related. In that spirit, having focused on Ruby on Rails in the past, the other component to this was starting the development in the context of a Ruby on Rails app.

Now, what I've learned right out the gate, is this __could__ be overkill, certainly more than is needed.  Jekylly is a pretty cool tool for theming and formatting on its own.  As I write this, I'm writing in the markup format that Jekyll uses, and really not leveraging Rails at all.  Frankly, the only reason to use rails at the moment is on the test server, and also because it triggers the Jekyll build process, dumping it into the "public" folder of the app.  From there, I have a git repo in that public folder that will allow me to push up to the GitHub pages, which hosts it.

So, all in all, it's sort of just a fancier version of making edits to a static 
HTML site, and pushing it up via FTP. So it's clear, if I __really__ want to see something cool using this combo of technology, I'll want to use Ruby and rails to drive the building of these pages.



TODO: on that...

###Terms

- Jekyll
    - Its a framework for making static-paged websites. 
        - Pro: Static pages are much less at rist for attack and compromise. 
        - Con: Becuase it's static, dynamic content isn't really the main focuse of the app.  So, it's more suited to something like a blog, or static info site.

[bklink]:      https://twitter.com/beaukinstler
[bklink-gh]:   https://github.com/beaukinstler
[bklink-about]: https://beaukinstler.com/about
[bkcom]:        http://beaukinstler.com 
[bkemail]:    mailto:{{ site.email }}