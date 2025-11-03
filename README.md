![alt text](demo.gif)

### Firefox
1. If you have compact icons enabled, switch to normal
2. In about:config (enter into the address bar) turn it on:  
`toolkit.legacyUserProfileCustomizations.stylesheets` `true`  
`sidebar.revamp` `true`
3. The native auto-hiding of the sidebar should be disabled (In the sidebar settings)
4. Create a "chrome" folder in 'Profile Folder' (Menu > Help > Troubleshooting Information > Profile Folder)
5. Copy there userChrome.css
6. Restart Firefox

Use padding around the edges of the address bar to scale and move the window.  
Drag Bookmarks Toolbar Items to the left of the address bar. 


<details><summary><b1> To update without rebooting and live-editing userChrome.css </b1></summary>

>If you're writing the styles yourself, you can set up [browser toolbox](https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html) and edit the files directly in it without having to restart Firefox for changes to apply. (You still need to restart Firefox when creating userChrome.css). On top of being able >to live-edit userChrome.css, the browser toolbox is essential in figuring out how to add custom styling to various parts of Firefox.
>
>You can find userChrome.css in the browser toolbox like this:
>
>1. Open browser toolbox
>2. Activate the Style Editor tab of the toolbox
>3. Type userChrome.css in the 'Filter stylesheets' box on the left
>4. Your userChrome.css appears on the right. Once you are done editing it, you can either close the toolbox which won't save your edits, or save edits by clicking the 'Save' link on the left.
</details>

Note: Development is being carried out in Firefox Beta win10, and it is being tested on Linux (lubuntu 18.04) every six months.


### Sidebery
1. [Install Sidebery](https://github.com/mbnuqw/sidebery)
2. Enable [Sidebery] prefix in the Sidebery settings.
The enabled Sidebery (by icon or hotkey) replaces the native side tabs.
3. Copy code from Sidebery.css to Sidebery / Settings / Styles editor / Sidebar


### YouTube
1. [Install Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)
2. Open [YouTube](https://youtube.com)
3. Stylus: `New Style` > `Import` > Copy code from YouTube.css > `Replace style` > `Save`

To open the header, move the cursor to the top edge, but not all the way.


### about:config
Thin scrollbars
`widget.non-native-theme.scrollbar.style` `3`  
Open a bookmark in a new tab
`browser.tabs.loadBookmarksInTabs` `true`  
Open tab after current
`browser.tabs.insertAfterCurrent` `true`  
Smoothness of scrolling
`general.smoothScroll.mouseWheel.durationMaxMS` `380`  
Disable add-on recommendations
`extensions.htmlaboutaddons.recommendations.enabled` `false`  
Restore pinned tabs on demand
`browser.sessionstore.restore_pinned_tabs_on_demand` `true`  
OS text scaling settings should only affect text scaling (prevents blurring of icons)
`browser.display.os-zoom-behavior` `2`  
Trim https
`browser.urlbar.trimHttps` `true`  
Decode URLs on copy
`browser.urlbar.decodeURLsOnCopy` `true`  
