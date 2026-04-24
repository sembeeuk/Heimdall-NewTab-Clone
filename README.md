# Chromium New Tab CSS for Heimdall

A CSS file that makes the [Heimdall Application Dashboard](https://heimdall.site/) look like the new tab page found in Chromium-based browsers.

The layout wraps the icon row after 10 items.

## Icons

This works best when each Heimdall item has an icon.

You can find suitable icons at [Dashboard Icons](https://dashboardicons.com/).

## Menu Items

This CSS hides the menu bars. To access settings, items, users, and other admin pages, use the URLs directly:

- `/settings` — settings page  
- `/items` — list of displayed items  
- `/users` — list of users  

## Deployment

1. Open **Settings** in Heimdall.  
2. Under **Miscellaneous**, configure the following:
   - **Homepage Search:** `Yes`
   - **Default Search Provider:** `Google`
   - **Link Opens In:** `Open in this tab`
3. Under **Advanced**, paste the contents of the CSS file into **Custom CSS**.  
4. *(Optional)* Paste the contents of the JavaScript file into **Custom JavaScript**.  

The optional JavaScript allows you to change the page title, but note that it applies to all pages.

## Replacing the New Tab Page

### Enterprise environments

In an enterprise environment, you can use Group Policy to replace the browser new tab page in MS Edge with your Heimdall dashboard.

Path:
Edge: Computer/User Configuration > Administrative Templates > Microsoft Edge > Startup, homepage and new tab page
Chrome: Computer/User Configuration > Administrative Templates > Google > Google Chrome > Startup, homepage and new tab page

Chrome requires the Google Chrome GPO which you can get from Google. 

### Home users

Use a browser extension that allows you to override the new tab page.
