# add-on
add-ons are nothing but web-extensions , that add additional features to browser

i've installed a cool add-on which would do the following

## What it does

Displays a simple button in the menu bar that toggles a bookmark for the currently active tab.

To display the button, the extension registers a [browserAction](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/browserAction) in the manifest.

A background script will listen for tab events and update the browserAction icon correspondingly. It also listens for `browserAction.onClicked` events to create or remove a bookmark when the user has clicked the icon.

## What it shows

* how to use the various `bookmarks` functions
  * create a bookmark
  * remove a bookmark
  * search bookmarks by url
* how to register a browserAction
* how to listen for tab changes

