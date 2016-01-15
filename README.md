## W3C GitHub Issue Dashboard

A quick app to keep tabs on github issues used in W3C Repos. Improvements welcome!

## Templates
You can easily create new views of github issues by creating [HTML files with Mustache templates](templates/), and then adding a reference to said file in the `templateUrls` in [app/scripts/main.js](app/scripts/main.js).

Repos listed in the repository selector are the ones registered in ash-nazg. The app will also happily read from any repo in the @w3c organization account.

(MIT License) - Copyright (c) 2014 Ilya Grigorik
