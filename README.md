# Firefox reStock

### reStock theme for Mozilla Firefox
Provides a userChrome.css file for styling Firefox.


## Features
#### More Tabs
reStock allows for tabs to become significantly smaller than possible under normal circumstances.  
The new minimum tab width with reStock is 17 pixels, leaving only a one-pixel boundry between favicons.

#### Smooth Transitions
reStock adds smooth transitions to many elements of the browser interface, including tabs, the navigation bar and menus.


## Installation
1. Open Firefox.
2. Navigate to `about:support`.
3. Find the column `Profile Folder` and open it. *Hint: It most likely ends in ".default-release"*.
4. Create a new folder `chrome` if it doesn't exist already, and navigate into it.
5. Download the `userChrome.css` file from this repository or copy it's contents into a new file called `userChrome.css`.
6. Place that file into the `chrome` folder.
7. Go back to Firefox.
8. Navigate to `about:config`.
9. Search for the config option `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
10. Restart Firefox.

For more information about userChrome customisation and a more detailed guide you can visit [userchrome.org](https://www.userchrome.org/how-create-userchrome-css.html).
