---
title: 'Fun with Open Course Hub (URL) Flags'
date: 01/17/2018
continue_link: true
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'Fun with Open Course Hub (URL) Flags'
    'twitter:description': 'A look at how the built-in URL flags of Open Course Hub helps better integrate content into existing LMSs'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2018-01-17-fun-with-open-course-hub-url-flags/onlysummary.png'
taxonomy:
    tags:
        - GravCMS
        - Canvas
        - Moodle
        - Integration
---

The Open Course Hub supports a number of optional URL flags, or parameter, to better embed content into other LMSs such as Canvas or Moodle:

|URL Flag|Purpose |
|---|---|
| `chromeless` |   Hide all global navigation elements |
| `summaryonly` |   Display the summary of a blog post |
| `hidepagetitle` |   Hide the title of a page |

===

Each URL flag can be added to a URL referencing a specific page of a Grav Open Course Hub site in the format `flagname:true`, for example:

`yourgravsite.com/chromeless:true`

and multiple flags can be used at once, for example:

`yourgravsite.com/chromeless:true/hidepagetitle:true`

So, time for some live demos!

View the standard Open Course Hub homepage:
[demo.hibbittsdesign.org/grav-course-hub/](http://demo.hibbittsdesign.org/grav-course-hub/)

And now let's view the same page using the `chromeless` URL flag:
[demo.hibbittsdesign.org/grav-course-hub/chromeless:true](http://demo.hibbittsdesign.org/grav-course-hub/chromeless:true)

Getting the idea? Let's continue!

View Week 1 for an Open Course Hub site:
[demo.hibbittsdesign.org/grav-course-hub/home/unit-01/](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-01/)

Now view the same page using the `chromeless` URL flag:
[demo.hibbittsdesign.org/grav-course-hub/home/unit-01/chromeless:true](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-01/chromeless:true)

You can also hide the page's title, like this:
[demo.hibbittsdesign.org/grav-course-hub/home/unit-01/chromeless:true/hidepagetitle:true](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-01/chromeless:true/hidepagetitle:true)

And even just display the summary (preview) of the page:
[demo.hibbittsdesign.org/grav-course-hub/home/unit-01/chromeless:true/hidepagetitle:true/summaryonly:true](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-01/chromeless:true/hidepagetitle:true/summaryonly:true)

Using the above three URL flags it's possible to embed various elements of your Grav Course Hub site into other LMSs like Canvas and Moodle - have fun!
