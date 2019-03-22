# Contributing

Suggestions and pull requests are highly encouraged!

# Notions

- You should be familiar with how [Chrome extension development](https://developer.chrome.com/extensions/devguide) works.
- You should be familiar with [Tumblr](https://www.tumblr.com/)
- The extension can be loaded into Chrome manually ([see below](#manually-loading-into-the-browser))
- All the [latest DOM APIs](https://github.com/WebReflection/dom4#features) and JavaScript features are available because the extension only has to work in the latest Chrome :tada:

# Workflow

First clone this repository:

```
git clone https://github.com/newfurniturey/tumblr-light-mode
cd tumblr-light-mode
```

While working on the extension, load or reload it into the browser to see the changes (this will not happen automatically).

# Manually loading into the browser

When you have a local copy:

1. Open `chrome://extensions`
1. Make sure the **Developer mode** toggle is enabled
1. Click on the **Load unpacked extension** button
1. Select the folder `tumblr-light-mode/src`
