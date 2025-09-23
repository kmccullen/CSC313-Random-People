Your challenge is to create something that looks like this:



This is a table of entries from randomuser.me.

A couple of notes:

The table and header are defined in the HTML, but the table rows are dynamically created from the data returned by randomuser.me. Most of your code will be involved in processing that data. You'll need to capture it from randomuser.me, parse it into fields, format the data, build a data structure holding the data, sort that data, and then build HTML rows using jquery.

The table is sorted by last name.

*The table has a more modern look that comes from use of CSS (embedded in the <style></style> tags in the HTML). That look was taken from: https://dev.to/dcodeyt/creating-beautiful-html-tables-with-css-428l

* As you mouse-over the rows, they change color, and the telephone number appears as a tip message (the little popup message). The mouse-over effect was implemented using CSS, taken from: https://medium.com/@brajagopal.tripathi/how-to-change-the-text-color-on-a-mouseover-in-html-697f4d4210fa

* There is a video demo of the table with mouse-over effects available: Demo Video in Yuja

I've provided templates for the HTML and Javascript. (Note that you'll need to rename the Javascript for it to work).

The Javascript includes a working method of using async functions with await. I'll go over that in class.

Submit three files:

* A brief writeup describing the challenges and successes of your project.
* PeopleDashboard.html
* PeopleDashboard.js
