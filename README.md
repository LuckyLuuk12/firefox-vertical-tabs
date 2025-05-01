<h1>Firefox Vertical Tabs</h1>
<h3>working for Versions 130.0, 132, 132.0.1, 133, 134, 135, 137 &amp; 138 (64-bit)</h3>
<p>
This project started September 2024, Firefox's vertical tabs were basically completely
absent. That's why I made this stylesheet. Now since May 2025, Firefox has provided 
a very decent implementation of vertical tabs that can be expanded on-hover.
This features exists since version 138.0 and can be enabled by going to the settings wheel
in the vertical tabs after enabling vertical tabs in the normal settings.
</p>

<h2>Continuation of this project?</h2>
I will only keep updating the stylesheet as long as Firefox keeps the &quot;small annoyances&quot;
I encounter like: Too wide scrollbar, resizing the vertical tabs and no red indicator for the close-tab icon.
If they fix these issues, I will stop updating the stylesheet.

**To prevent confusion:
The [userChrome.css](https://github.com/LuckyLuuk12/firefox-vertical-tabs/blob/master/userChrome.css) 
file in the root of this repository will stay at the v137 version.**

<h2>Installation:</h2>
Note that if the latest userChrome.css works in the latest version of Firefox, that we do not have a folder for that version
as we only update the userChrome.css file when it breaks. So if you are using a newer version of Firefox just try the latest.
<ol>
  <li>Go to <code>about:config</code> in your Firefox browser.</li>
  <li>Accept the risk and continue.</li>
  <li>Search for <code>sidebar.revamp</code> and set it to <code>true</code></li>
  <li>Search for <code>sidebar.verticalTabs</code> and set it to <code>true</code></li>
  <li>Search for <code>toolkit.legacyUserProfileCustomizations.stylesheets</code> and set it to <code>true</code>.</li>
  <li>Go to <code>about:support</code> and click on <code>Open Folder</code> in the Profile Folder row.</li>
  <li>Create/open a folder called <code>chrome</code> in the profile folder.</li>
  <li>Download the <code>userChrome.css</code> file from this repository and place it in the <code>chrome</code> folder.</li>
  <li>Restart your Firefox browser.</li>
</ol>
<h2>Contributing:</h2>
<p>
If you want to modify Firefox as well you could take a look at 
this documentation of them where they explain how you can use the
devtools to inspect the browser and modify it:
<a href="https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html">Mozilla Browser Toolbox</a>
</p>
<h6><i>Note that changes you make in the <code>userChrome.css</code> require a restart of the browser.</i></h6>
So after you modified the file you can make a pull request and I will review it.
<p>Want to contribute? Be sure to read <a href="https://github.com/LuckyLuuk12/firefox-vertical-tabs/blob/master/CONTRIBUTING.md">this</a></p>

