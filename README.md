This is a CSS file to create a clone of the new tab page found in Chromium based browsers for use with the Heimdall Application Dashboard. https://heimdall.site/

It wraps the line of icons at 10. 

When creating items, this works best if you put an icon on the item. Find the icons here: https://dashboardicons.com/

<b>Menu Iitems</b>

This CSS hides the menu bars - so to access settings, items etc, you will need to use the URL directly. 

<ul>
<li>/settings - for the settings page</li>
<li>/items - for the list of items displayed on the page</li>
<li>/users - for the list of users</li>
</ul>

<b>Deployment</b>

To deploy, open settings. 
Under Miscellaneous ensure that "Homepage Search" is set to Yes.
Default Search Provider is to set Google.
Link Opens in "Open in this tab"

Under Advanced, but the contents of the CSS file in the box for Custom CSS.
Optionally, but the contents of the JS file in to the Custom JaveScript. This allows you to change the page title - but it applies to allow pages. 

<b>Replacing the new tab page</b>

If you are in an Enterprise environment, then you can use Group Policy to use this page to replace the new tab page.

For home users, use one of the many extensions to override the new tab page. 
