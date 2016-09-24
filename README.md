# gmTwitter
Replacing the huge style sheets using Greasemonkey.

The social network Twitter (http://www.twitter.com) is one of these modern sites with excessive HTML nesting and over 6.000 CSS style rules. This is not only adding traffic, but also taxes the hardware.

Can't do much about the first problem, but by blocking the .css file and inserting custom styles via the Firefox extension Greasemonkey (https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) one can cut down on this unnecessary crap.

It should be noted that the script is not (yet) able to reproduce the full functionality of the site. Its main goal is to make browsing possible. Tweeting will probably always require to load the site with the adblocker and Greasemonkey disabled. Or by using the API (https://dev.twitter.com/overview/documentation); like I do.


How to use the scripts:

1. Block the CSS files by adding "||abs.twimg.com^" to an adblocker (or your router).
2. Maybe also block "||pbs.twimg.com/profile_images/*".
3. Add the Greasemonkey script gmTwitter.js.
