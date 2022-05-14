# Text Editor
## Description
For this project, I created browser-based text editor that meets PWA criteria. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

## Table of Contents
- [Usage](#usage)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Credits](#credits)
- [License](#license)

## Usage
Visit my [repo here](https://github.com/Quadrilateral0/Social-Network-API) and see below for a video demo.

The application requires [Node.js](https://nodejs.dev/learn/introduction-to-nodejs). Install the necessary dependencies in your terminal using the following command:
```bash
npm i
```

and invoke the program by using:

```bash
npm start
```

[![Video demo of completed project](images/API-demo.png)](https://youtu.be/d3MFNtsxTxM)


## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Credits
A thanks to my tools and resources:
- [idb](https://www.npmjs.com/package/idb)
- [Express.js](https://www.npmjs.com/package/express)
- [Node.js](https://nodejs.dev/learn/introduction-to-nodejs) 
- [Heroku](https://www.heroku.com/)
- [Screencastify](https://chrome.google.com/webstore/detail/screencastify-screen-vide/mmeijimgabbpbgpdklnllpncmdofkcpn?hl=en)
- [Visual Studio Code](https://code.visualstudio.com/download)

And thanks to these tutorials:
- [MDN Web Docs](https://developer.mozilla.org/)
- [W3 Schools](https://www.w3schools.com/)

## License
![MIT License](https://img.shields.io/badge/license-MIT-green)