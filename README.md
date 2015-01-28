# VanillaForums-ChromeNotifier
Chrome notifier icon for Vanilla Forums installations.

Notes:
- you'll need to either a) replace YOURFORUMHERE.com with your URL in manifest.json, dostyle.js, browser_action.html, and background.js. Or (even better) set up a settings page where you can input the forum name. I'm not sure how much work that entails as I got it working on my site and gave up :)  The options_custom and options_simple directories are stock and untouched by me (I may have deleted some sample options or something).
- dostyle.js is poorly-named; it actually loads the notifcations page into the drop-down.
- in browser_action.html, I just load the site's main style.css, so there's no theme-based customization.  If you know of a good way to load the css for your site's theme here, please let me know :)
