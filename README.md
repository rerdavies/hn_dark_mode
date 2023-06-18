# hn_dark_mode
This project is a demo of a style sheet for Hacker News that repects Dark Mode settings. It is presented here in hopes that HN administrators will copy the stylesheet into HN production sources.

The one relevant file in the project is `docs/news.css`, which is a copy of the current HN style sheet augmented with additional rules for Dark Mode. 
Changes have been made only to color settings, all of which are conditioned on a `@media (prefers-color-scheme: dark)` selector. No changes are required
to HTML or Javascript files.

To view a mockup of the Dark Mode stylesheet, click [here](https://rerdavies.github.io/hn_dark_mode). It won't be dark, unless your browser is running in Dark Mode.

Note that Chrome on Windows does not have a Chrome-specific setting for Dark Mode. To view the page in dark mode on Windows, you must enable dark mode in Windows settings. Start the Windows Settings app, and search for "Dark Mode". You have two choices: "Turn on dark mode for apps", or "Turn on dark mode systemwide". Either will work. 
