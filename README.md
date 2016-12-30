# Bookmark 🔖
_Bookmark your place and zoom in Sketch.app_

When working on a long document in Sketch.app, I often thought that it would be nice to quickly navigate between my reference and the current working place. So, I wrote a little script to do just that. You can save 5 bookmarks per page and navigate quickly between them.

<img src="/../artwork/teaser.png?raw=true" alt="Bookmark 🔖 fn + 1" width="200">

## Installation
Installation should be quite easy, here are two ways to do it.

### Install using Sketch Toolbox (recommended)
1. Install the app from http://sketchtoolbox.com/
2. Install the plugin using the app.
3. Start using it.

### Install from repo
1. Download and open [Bookmark-master.zip](https://github.com/Arkkimaagi/Bookmark/archive/master.zip)
2. Navigate the Sketch menu bar to `Plugins ▸ Manage Plugins... ▸ ⚙ (Settings gear symbol) ▸ Show Plugins Folder`
3. Place `Bookmark.sketchplugin` into the revealed plugins directory

## How to Use
Select `Plugins ▸ Bookmark 🔖 ▸ Save bookmark 1` in the Sketch menu bar or use the keyboard shortcut <kbd>fn</kbd> + <kbd>⇧ shift</kbd> + <kbd>1</kbd> to save a bookmark of the current position and zoom for the current page.

To load a bookmark, select `Plugins ▸ Bookmark 🔖 ▸ Load bookmark 1` in the Sketch menu bar or use the keyboard shortcut <kbd>fn</kbd> + <kbd>1</kbd> to load the currently saved bookmark. If you save a new bookmark on the same number, the old one is overwritten.

Currently **Bookmark 🔖** supports 5 bookmarks per page. If you feel that you'd want more, please let me know.

If for some reason you wish to clean all the bookmarks for current page, plugin menu has an option for that. (Helps me with debugging this script)

**Keyboard Shortcuts**

| *Shortcut*                                        | *Action*                          |
|---------------------------------------------------|-----------------------------------|
| <kbd>fn</kbd> + <kbd>⇧ shift</kbd> + <kbd>1</kbd> | Save bookmark 1 for current page. |
| <kbd>fn</kbd> + <kbd>⇧ shift</kbd> + <kbd>2</kbd> | Save bookmark 2 for current page. |
| <kbd>fn</kbd> + <kbd>⇧ shift</kbd> + <kbd>3</kbd> | Save bookmark 3 for current page. |
| <kbd>fn</kbd> + <kbd>⇧ shift</kbd> + <kbd>4</kbd> | Save bookmark 4 for current page. |
| <kbd>fn</kbd> + <kbd>⇧ shift</kbd> + <kbd>5</kbd> | Save bookmark 5 for current page. |
| <kbd>fn</kbd> + <kbd>1</kbd>                      | Load bookmark 1 for current page. |
| <kbd>fn</kbd> + <kbd>2</kbd>                      | Load bookmark 2 for current page. |
| <kbd>fn</kbd> + <kbd>3</kbd>                      | Load bookmark 3 for current page. |
| <kbd>fn</kbd> + <kbd>4</kbd>                      | Load bookmark 4 for current page. |
| <kbd>fn</kbd> + <kbd>5</kbd>                      | Load bookmark 5 for current page. |

## Feedback
If you discover any problems, please create a new issue here explaining the problem.

<img src="/../artwork/bookmark.png?raw=true" alt="Bookmark 🔖" width="100">
