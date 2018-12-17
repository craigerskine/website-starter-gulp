# website-starter-gulp

A super basic web project setup using Gulp, Tailwind, and some CSS & JS compressors.

### Requirements

* [node.js](https://nodejs.org/)

### Usage

1. Download the project and extract to a folder on your system.
2. Open a terminal/command prompt in that folder.
3. Type the following commands:

`npm install` - you only need to do this the first time

`./node_modules/.bin/gulp`

When you edit the files in the `app` folder they will get compiled and moved to `dist`, and your browser will auto reload to show the results.

__NOTE:__ BrowserSync does not support a full cache reload, so you must set your devtools to flush cache while open and leave the devtools open while working. I'm looking for a way around this.
