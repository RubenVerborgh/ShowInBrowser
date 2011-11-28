# Show in browser
Google Chrome Extension that shows various types of textual files inside of the browser instead of downloading them.

## Concept
Have you ever wanted to view a textual file in Chrome (say, `text/turtle`) but did your browser just save it to your _Downloads_ folder?
<br>
This extension aims to change this using the experimental [downloads API](https://docs.google.com/document/d/12rNimeeGaA8jEV60PPKtT4pmJYmY9ae_edl3hJyoXYE/edit?hl=en_US).

## Limitations
- Currently, it only works with the latest [Canary](http://tools.google.com/dlpage/chromesxs).
- You need to enable Experimental Extension APIs in `chrome://flags`.
- The download is not canceled, as this appears not to be implemented in Chrome yet.

## Download
As this extension uses an experimental API, it cannot be downloaded from the Chrome Web Store.
<br>
[Download it here](http://dl.dropbox.com/u/51307162/ShowInBrowser.crx).
