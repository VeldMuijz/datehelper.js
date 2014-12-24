datehelper.js
=============

A simple set of prototypes to use for easy date formatting.

The usage is as follows:
To get a time value use the following:<br />
`var time = new Date().timeNow('hh:mm:ss');` will return `10:58:16`<br />
`var time = new Date().timeNow('hh:mm');` will return `10:58`<br />
`var timestamp = new Date().dateToday('dd-mm-yyyy')` will return `10-12-2014`<br />
`var timestamp = new Date().dateToday('dd-mm-yyyy') + " " + new Date().timeNow('hh:mm:ss');` will return `10-12-1990 10:58:16` <br />
<br />
There is also the posibility of formatting a date or time that is different than the current date or time:
`var timestamp = new Date('10-12-1990').dateToday('dd-mm-yyyy')` will return `10-12-1990`<br />
`var time = new Date('10:58:16').timeNow('hh:mm');` will return `10:58`<br />
<br />


See the JSFiddle for this: [datehelper.js](http://jsfiddle.net/VeldMuijz/7ctk6633/7/)
