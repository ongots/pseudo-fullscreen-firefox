![alt text](demo.gif)


### Install Firefox style
1. If you are using compact density switch to normal
2. In about:config enable:
- `toolkit.legacyUserProfileCustomizations.stylesheets`
- `layout.css.backdrop-filter.enabled` (for blur)
- `gfx.webrender.enabled` (for blur)
- `layout.css.color-mix.enabled`
3. Open about:support
4. Click on "Profile Folder" -> "Open Folder"
5. Copy the chrome folder here
6. Restart Firefox

- Drag Bookmarks Toolbar Items to the left of the address bar. Disable Bookmarks Toolbar
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


### Useful settings about:config
- Opening a bookmark in a new tab
`browser.tabs.loadBookmarksInTabs` `true`
- Open tabs to the right of the current one
`browser.tabs.insertAfterCurrent` `true`
- Scroll step
`mousewheel.min_line_scroll_amount` `25`
- Smoothness of scrolling
`general.smoothScroll.mouseWheel.durationMaxMS` `380`
- Disable sponsored sites
`browser.newtabpage.activity-stream.showSponsored` `false`
- Disable add-on recommendations
`extensions.htmlaboutaddons.recommendations.enabled` `false`
