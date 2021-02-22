# A Twitter web scraper example robot

A Twitter web scraper robot. Stores tweets (screenshot and text).

When run, the robot will:

- open a real web browser
- accept the cookie notice if it appears
- hide distracting UI elements
- scroll down to load dynamic content
- collect the latest tweets by a given Twitter user
- create a file system directory by the name of the Twitter user
- store the text content of each tweet in separate files in the directory
- store a screenshot of each tweet in the directory

> Because Twitter blocks requests coming from the cloud, this robot can only be executed on a local machine (or triggered from the cloud with Robocorp App).

See [Web scraper robot](https://robocorp.com/docs/development-guide/browser/web-scraper-robot) for detailed information about the robot!
