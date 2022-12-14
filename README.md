# This is a HEAVILY modified version of Pauan/AutoScroll, from their chrome extension. Intended only for my personal use, because the original version had a BUNCH of unnecessary stuff in it. 





AutoScroll
==========

For users on Linux or Mac, the lack of autoscroll can be a big pain. This extension can help!

Intentional differences with Firefox
====================================

* AutoScroll does not scroll on `contenteditable` elements; Firefox does

For developers
==============

Test these sites:

* <https://easyweb.td.com/waw/idp/login.htm?execution=e1s1>
* <http://9to5mac.com/>
* <https://www.willhaben.at/>
* <http://www.wind.it/it/privati/>
* <https://www.opengl.org/sdk/docs/man/html/glDrawElements.xhtml>
* <https://twitter.com/amcharts>
* <http://addepar.github.io/ember-table/>
* <https://plus.google.com/>
* <https://duckduckgo.com/?q=test&ia=meanings>
* <http://fivethirtyeight.com/>
* <https://www.washingtonpost.com/news/wonk/wp/2016/01/20/we-have-a-q-tips-problem/>
* <http://www.indiewire.com/>
* <http://www.teknoseyir.com/>
* <http://www.nu.nl/>

TODO

* Use the nice Radiance and Ambiance images provided by a user
* Add better scaling (slower when near the disc, faster when away from the disc, like in Firefox)
* Add configurable scaling
* Move speed should be 0 = slowest, 10 = fastest
* Use a slider for the move speed, rather than a number box
* Fix the severe bug with pinch-to-zoom on Mac
* Add better promotional images on the Chrome Web Store
* Add in an option for reversing the X and Y axis (up is down, down is up, etc.)
* Add in touchscreen/tablet support
* When scrolling horizontally, it should only scroll when the mouse is to the left/right of the disc, like in Firefox
* When scrolling vertically, it should only scroll when the mouse is to the top/bottom of the disc, like in Firefox
* Add in an option to stop autoscrolling when the user scrolls with the mouse wheel
* Option for keyboard-only control
* Option to change the key binding for activating AutoScroll
* Switch to the new options page system (in Chrome)
