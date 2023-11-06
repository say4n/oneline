# oneline

a minimal firefox userChrome CSS with TST integration

## setup

minimal setup instructions for when I inevitably forget how I set things up with my firefox install in the future

- install [TST](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/) from firefox store
  - set appearence to "No Decoration" for TST
  - paste the contents of `tst.css` in the "Advanced > User Style Sheets" section of TST prefs 
- locate the profiles folder for the firefox installation using [`about:support`](about:support)
  - paste the chrome folder inside the folder
  - navigate to [`about:config`](about:config) and change `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`

## screenshots

![](https://github.com/say4n/oneline/blob/main/assets/SCR-20231028-necr.png?raw=true)
![](https://github.com/say4n/oneline/blob/main/assets/SCR-20231028-nemf.png?raw=true)

