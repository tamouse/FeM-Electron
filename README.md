# Frontend Masters Electron Live workshop with Steve Kinney (Workshop #90)

* November 15, 2016
* [Steve Kinney](http://stevekinney.net/) [@stevekinney on twitter](https://twitter.com/stevekinney)
* [Setup Instructions](https://gist.github.com/stevekinney/4cc5c61e827c00dbea55409f26d1da02)
* [Slides](https://speakerdeck.com/stevekinney/electron-frontend-masters)
* [Turing School](http://turing.io)
* [Electron in Action (book)](http://bit.ly/electronjs)

## Videos

* [Live Video](https://frontendmasters.com/live-event/electron-live/)

The video segments are available in the live player as soon as they're
cut and posted. Click on the little drawer icon in the top right of
the video player to see the available segments.

![](video-drawer.jpg)

## Copy of Setup Instructions

Participants should have a recent version of Node.js installed on their system (preferably the latest LTS version, which is 6.9.1 as of this writing—but anything from 0.10 on should work). Participants should clone the following repositories and run `npm install` in each of them prior to the start of the workshop.

- [Bookmarker](https://github.com/stevekinney/fem-bookmarker)
- [Fire Sale](https://github.com/stevekinney/fem-firesale)
- [Clipmaster 9000](https://github.com/stevekinney/clipmaster-9000-tutorial)

Optional: It might be helpful to install Electron globally so that you can use it from the command line in case there are any issues with any of the dependencies in the project above. You can install this through `npm install -g electron`.

Finally, debugging the main process is easiest using Visual Studio Code, which is available for all platforms (Windows, Linux, and macOS). This is not a hard requirement, but helpful if you'd like to follow along for that small segment of the workshop.

### Live Coding branch

Steve has saved the results of his live coding on each of these in a
branch:

- [Bookmarker live coding](https://github.com/stevekinney/fem-bookmarker/tree/fem-live-coding)
- [Fire Sale live coding](https://github.com/stevekinney/fem-firesale/tree/fem-live-coding)
- [Clipmaster 9000 live coding](https://github.com/stevekinney/clipmaster-9000-tutorial/tree/fem-live-coding)


## Other

* [Chat Emoji Cheat Sheet](http://www.webpagefx.com/tools/emoji-cheat-sheet/)
* [Suz Hinton - noopkat](http://noopkat.com/)
* [Electron Docs](http://electron.atom.io/docs/)


### reloading / livereload of main electron app
* [Quramyelectron-connect Livereload tool for Electron](https://github.com/Quramy/electron-connect)
* [electron-livereload](https://www.npmjs.com/package/electron-livereload)
* [app - Electron](http://electron.atom.io/docs/api/app/#apprelaunchoptions)


### getting screen info

* [screen - Electron](http://electron.atom.io/docs/api/screen/)


### easily rendering system font

```css
body, input {
  font: menu;
}
```


### Getting content of a file from readFileSync

From James G:

```javascript
var contents = fs.readFileSync(path, { encoding: 'utf8' });
```
