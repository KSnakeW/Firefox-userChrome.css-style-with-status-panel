# Firefox userChrome.css style with status bar
UserChrome.css style for Firefox ver. > 96 with default theme. Restores status bar (status panel).

Allows restore classic status panel in Firefox. Additionally subtly changes tabs look in default Firefox themes.

**From version 157**
- Nova theme is now widely provided. This is somehow messing with colors schemes. If you used *about:config* to disable and re-enable Nova then you have to use newest version which contains dynamicaly assigned status bar color. Good news is that, that new version works perfectly with thirdparty themes and Mozilla's "Firefox Color" addon as well.
- I added some accents to bookmarks which allows to distinguish buttons from background.
- Now there are shadows under tabs.

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
