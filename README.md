ember-mobile-html5-boilerplate
==============================

The purpose of this project is to provide a starting point for emberjs apps on mobile.

### Method

Simply, we'll be combining the ember starter kit from [http://emberjs.com/] and the html5 mobile boilerplate from [http://html5boilerplate.com/mobile]

## Useful info from mobile boilerplate

A JavaScript helper is included in the boilerplate with namespace MBP, it's located at js/mylibs/helper.js.
There are a couple of kick-ass functions that help you to improve mobile user experience. 

### iPhone Scale Bug Fix
**Description:** <br />
MBP.scaleFix is used to fix the iPhone reflow scale bug, read more about it here: [a fix for iphone viewport scale bug](http://www.blog.highub.com/mobile-2/a-fix-for-iphone-viewport-scale-bug/)<br />
**Usage:** <br />
`MBP.scaleFix();`

###Hide URL Bar
**Description:** <br />
MBP.hideUrlBar is used to hide the URL bar at the top of mobile Safari on your iOS. Mobile space is limited and this helps to leverage every pixel on the screen to maximize display area.<br />
**Usage:** <br />
`MBP.hideUrlBar();`

###Fast Buttons **(only use this if you only target webkit browsers, we are still testing out cross-browser support)**
**Description:** <br />
MBP.fastButton is used to make instant responsive buttons, 300ms faster to be exact. (It uses touchstart to detect click event.) <br />
**Usage:**<br />
`new MBP.fastButton(document.getElementById('myBtn'), function() {alert("clicked")});`

###Autogrow textarea
**Description:** <br />
MBP.autogrow is used to make textarea to grow its height while you are entering more lines of text.<br />
**Usage:** <br />
`new MBP.autogrow(document.getElementById('myTextarea'), 14); // 14 -- line height`

 





