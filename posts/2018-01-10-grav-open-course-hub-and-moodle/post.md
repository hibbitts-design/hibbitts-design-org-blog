---
title: 'Grav Open Course Hub and Moodle'
date: 01/10/2018
continue_link: true
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'Grav Open Course Hub and Moodle'
    'twitter:description': 'Several new features have been added to the Grav Open Course Hub to improve integration with Moodle'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2018-01-10-grav-open-course-hub-and-moodle/grav-with-moodle'
taxonomy:
    tags:
        - GravCMS
        - Moodle
---

Long on my **to-do list** was to further explore how Grav Open Course Hub content could be displayed within the popular open source [Moodle](https://moodle.org/) LMS. Curious about the initial results? You can explore a live demo at <a href="http://paulhibbitts.net/moodle/course/view.php?id=2">paulhibbitts.net/moodle/course/view.php?id=2</a> and view some draft docs at [learn.hibbittsdesign.org/coursehub/integrating-grav-with-moodle](http://learn.hibbittsdesign.org/coursehub/integrating-grav-with-moodle).

![Grav Course Hub content within Moodle](grav-with-moodle.png)  
_Figure 1. Grav Course Hub content within Moodle._

===

To better support display of Course Hub content within Moodle, two new URL flags have also been added:

`hidepagetitle:true` to hide the Course Hub page entitled  
`summaryonly:true` to only display a unit's (week) page summary  

So, for example to embed a Course Hub Unit page summary using an iFrame in Moodle without a page title the HTML would be:

        <p><iframe scrolling="no" style="border: 0px #ffffff none; " src="http://demo.hibbittsdesign.org/grav-course-hub-moodle/home/unit-01/chromeless:true/summaryonly:true/hidepagetitle:true" allowfullscreen="allowfullscreen" height="470px" width="100%"></iframe></p>
