![alt text](demo.gif)

### Install Firefox style
1. In about:config enable:
- `toolkit.legacyUserProfileCustomizations.stylesheets`
- `layout.css.color-mix.enabled`
2. Open about:support
3. Click on "Profile Folder" -> "Open Folder"
4. Copy the chrome folder here
5. Restart Firefox

⚠️ For Firefox <101 [windows] add to userChrome.css:
```
/* Important! Remove when using Firefox 101 and newer */
@media(-moz-windows-default-theme) {[sizemode="maximized"] #nav-bar {margin-top: 8px}}
```

- Drag Bookmarks Toolbar Items to the left of the address bar
- To set the wallpaper in a new tab, place a .jpg or .png image in the Chrome folder and rename it to "bg". Restart Firefox


### Install Sidebery style
1. [Install Sidebery](https://addons.mozilla.org/firefox/addon/sidebery/)
2. Copy the code from Sidebery-Sidebar.css to Sidebery / Settings / Styles editor / Sidebar
3. Copy the code from Sidebery-GroupPage.css to Sidebery / Settings / Styles editor / Group page


### Install YouTube style
1. [Install Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)
2. Open YouTube
3. In Stylus, click New Style ...
4. In the window that opens, click Import
5. Copy the code here from the Stylus-YouTube.css file and click replace style
6. Save

or

- Copy the code from Stylus-YouTube.css to /chrome/userContent.css



### Useful settings about:config
- Opening a bookmark in a new tab
`browser.tabs.loadBookmarksInTabs` `true`
- Scroll step
`mousewheel.min_line_scroll_amount` `25`
- Smoothness of scrolling
`general.smoothScroll.mouseWheel.durationMaxMS` `380`
- Disable add-on recommendations
`extensions.htmlaboutaddons.recommendations.enabled` `false`
- Not open download panel
`browser.download.alwaysOpenPanel` `false`
- Restore pinned tabs on demand
`browser.sessionstore.restore_pinned_tabs_on_demand` `true`
