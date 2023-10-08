![alt text](demo.gif)

### Install Firefox style
1. In about:config enable `toolkit.legacyUserProfileCustomizations.stylesheets`
2. Copy 'chrome' folder in 'Profile Folder' (Menu > Help > Troubleshooting Information > Profile Folder)
3. Restart Firefox

- Use "System theme - auto"
- Drag Bookmarks Toolbar Items to the left of the address bar
- To set the wallpaper in a new tab, place a .jpg or .png image in the Chrome folder and rename it to "bg". Restart Firefox


### Install Sidebery style
1. [Install Sidebery v5](https://github.com/mbnuqw/sidebery/releases) (updated automatically)
2. Copy the code from Sidebery-Sidebar.css to Sidebery / Settings / Styles editor / Sidebar
3. Copy the code from Sidebery-GroupPage.css to Sidebery / Settings / Styles editor / Group page


### Install YouTube style
1. [Install Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)
2. Open YouTube
3. In Stylus, click New Style ...
4. In the window that opens, click Import
5. Copy the code here from the Stylus-YouTube.css file and click replace style
6. Save

- To open the header, move the cursor to the top edge, but not all the way


### Useful settings about:config
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
