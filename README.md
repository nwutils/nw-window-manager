# nw-window-manager

WIP: NW.js Window Management library

## Ideas

* Easier stuff
  * Create new windows
  * Show relations of parent/child windows
  * Hide/Show/Close a window remotely
  * Hide/Show/Close all child windows
  * Hide/Show/Close all windows
  * Blur/Focus any window
* Harder stuff
  * Communicate with windows created as a new instance (via sockets/ports)
  * Keep track of window urls if possible
  * Communicate with framework routing libraries maybe? (Like Vue-Router)
  * Keep track of window stack order by listening to onFocus events and re-arranging an array
