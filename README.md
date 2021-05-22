![alt text](demo.gif)

### :warning: Supported only Proton and only normal density


### Install Firefox style
1. In about:config enable prefs:
- toolkit.legacyUserProfileCustomizations.stylesheets
- layout.css.backdrop-filter.enabled
- gfx.webrender.enabled
2. Open about:support
3. Click on "Profile Folder" -> "Open Folder"
4. Copy the chrome folder here
5. Restart Firefox

- Drag Bookmarks Toolbar Items to the left of the address bar. Disable Bookmarks Toolbar

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
