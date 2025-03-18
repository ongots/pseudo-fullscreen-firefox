![alt text](demo.gif)

### Firefox
1. If you have compact icons enabled, switch to normal
3. In about:config enable `toolkit.legacyUserProfileCustomizations.stylesheets`
5. Copy 'chrome' folder in 'Profile Folder' (Menu > Help > Troubleshooting Information > Profile Folder)
6. Restart Firefox

- Use padding around the edges of the address bar to scale and move the window
- Drag Bookmarks Toolbar Items to the left of the address bar
- ~~To set the wallpaper in a new tab, place a .jpg or .png image in the Chrome folder and rename it to "bg". Restart Firefox~~ (Custom wallpapers added to FF138 `browser.newtabpage.activity-stream.newtabWallpapers.customWallpaper.enabled`)
- Use "System theme - auto"


### Sidebery
1. [Install Sidebery](https://github.com/mbnuqw/sidebery)
2. Copy the code from Sidebery-Sidebar.css to Sidebery / Settings / Styles editor / Sidebar
3. Copy the code from Sidebery-GroupPage.css to Sidebery / Settings / Styles editor / Group page


### YouTube
1. [Install Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)
2. Open YouTube
3. In Stylus, click New Style ...
4. In the window that opens, click Import
5. Copy the code here from the Stylus-YouTube.css file and click replace style
6. Save

- To open the header, move the cursor to the top edge, but not all the way


### about:config (enter into the address bar)
- ⚠️Disable native vertical tabs for correct display Sidebery
`sidebar.revamp` `false`
- Thin scrollbars
`widget.non-native-theme.scrollbar.style` `3`
- Opening a bookmark in a new tab
`browser.tabs.loadBookmarksInTabs` `true`
- Smoothness of scrolling
`general.smoothScroll.mouseWheel.durationMaxMS` `380`
- Disable add-on recommendations
`extensions.htmlaboutaddons.recommendations.enabled` `false`
- Do not open download panel
`browser.download.alwaysOpenPanel` `false`
- Restore pinned tabs on demand
`browser.sessionstore.restore_pinned_tabs_on_demand` `true`
- OS text scaling settings should only affect text scaling
`browser.display.os-zoom-behavior` `2`
- Trim https
`browser.urlbar.trimHttps` `true`
- Decode URLs on copy
`browser.urlbar.decodeURLsOnCopy` `true`
