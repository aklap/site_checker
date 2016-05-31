# site_checker
Creating a background process with Launchd to check HTTP status code of a website on Mac OS/X

A launch agent for Mac OS/X to check when a site is online with status 200 OK. Instead of refreshing constantly to see if a website is online, we have a background process for a sp. user run and if the site is running, pop open a tab in the browser automatically for us.