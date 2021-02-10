# Linux Ricing Setup
> Building a custom rice

## Firefox
### Setup: Chroming
Sets up the UI and new tab of firefox
- Go to **about:config** and set **toolkit.legacyUserProfileCustomizations.stylesheets** to *true*
- THen go to **about:support** and open the Profile directory
- In the directory create a folder called chrome
- Put the contents of the chrome folder in the repository into the newly created chrome folder
- Restart firefox

### Setup: Landing page
Sets up the new window and home page of firefox
- Take the startpage directory from the repository
- Get the absolute path of the **index.html** file
- Go to firefox -> Preferences -> Home tab and set **index.html** as the home page
- Open a new window and you should see the startpage