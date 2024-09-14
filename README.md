<h1>Firefox Vertical Tabs</h1>
<h3>working for Version 130.0 (64-bit)</h3>
<p>
As of now, september 2024, Firefox's vertical tabs are still in an 
experimental version and they are absolute trash. By following below steps 
I provide you an 'acceptable' styling and functionality for the vertical tabs.
It might be though that Firefox updates it and breaks everything again. 
Please notify me or fork and pull request on this yourself (:
</p>
<h2>Installation:</h2>
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

