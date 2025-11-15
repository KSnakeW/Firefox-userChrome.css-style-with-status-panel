# Firefox userChrome.css style with status panel
UserChrome.css style for Firefox ver. > 96 with default theme. Restores status panel.

Allows restore classic status panel in Firefox. Additionally subtly changes tabs look in default Firefox themes.

For version up to 105 status panel is always hidden in fullscreen. Even if Firefox force to display any lable.

From version 106 everything is dynamic as in original FF behavior.


### Installation
Just copy **chrome\userChrome.css** into Your Firefox profile folder.

To open **Root Profile** folder just:
- run Firefox,
- open address: **about:profiles** ,
- if there is more than one profile then locate 'in use' one,
- click **"Open folder"** button next to **Root Profile** path,
- create ***chrome*** folder and open it,
- save here ***userChrome.css*** file,
- restart Firefox,
- VOILA!

## If doesn't work:
Open **about:config**, search or create ***toolkit.legacyUserProfileCustomizations.stylesheets*** *boolean* preference, set it *true* and restart browser.

### As far works on every system that's Firefox Quantum runs



### Many thanks to [ablazhov](https://github.com/ablazhov) for minor but very usefull modifications in Firefox 128 and newer versions.
