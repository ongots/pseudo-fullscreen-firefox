![alt text](demo.gif)

### Firefox
1. If you have compact icons enabled, switch to normal
2. In about:config (enter into the address bar) `toolkit.legacyUserProfileCustomizations.stylesheets` `true`
3. Create a "chrome" folder in 'Profile Folder' (Menu > Help > Troubleshooting Information > Profile Folder)
4. Copy there userChrome.css
5. Restart Firefox

- Use padding around the edges of the address bar to scale and move the window
- Drag Bookmarks Toolbar Items to the left of the address bar
- Use "System theme - auto" (Third-party themes are not supported because variables are not available for all elements)



### Sidebery
1. [Install Sidebery](https://github.com/mbnuqw/sidebery)
2. Copy code from Sidebery.css to Sidebery / Settings / Styles editor / Sidebar
<details><summary><b1>3. Copy code to Styles editor / Group page </b1></summary>

> #root[data-frame-color-scheme=dark] {--s-toolbar-bg: hsl(252, 4%, 9%) !important}
> 
> html {background-color: var(--s-toolbar-bg) !important}
> 
> .title {opacity: .7}

</details>


### YouTube
1. [Install Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)
2. Open [YouTube](https://youtube.com)
3. Stylus: `New Style` > `Import` > Copy code from YouTube.css > `Replace style` > `Save`

- To open the header, move the cursor to the top edge, but not all the way


### about:config
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
- Restore pinned tabs on demand
`browser.sessionstore.restore_pinned_tabs_on_demand` `true`
- OS text scaling settings should only affect text scaling (prevents blurring of icons)
`browser.display.os-zoom-behavior` `2`
- Trim https
`browser.urlbar.trimHttps` `true`
- Decode URLs on copy
`browser.urlbar.decodeURLsOnCopy` `true`
- Custom wallpapers (FF138)
`browser.newtabpage.activity-stream.newtabWallpapers.customWallpaper.enabled`
