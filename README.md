# chrome-extension-template

## Commands

|Command         |Description                                                                  |
|----------------|-----------------------------------------------------------------------------|
|`npm run start` |Starts a service that will build the dist files on file change               |
|`npm run build` |Builds the dist files                                                        |
|`npm run zip`   |Created a zip file of the dist folder to be uploaded to the Chrome App Store |
|`npm run lint`  |Lint the project and auto fix issues where possible                          |

## Testing

Generate the *dist* folder by executing `npm run build` or `npm run start`.

Navigate to `chrome://extensions/` on your Chrome browser.

Enable *Developer Mode* by clicking the toggle at the top right of the page, a sub menu should appear.
![enable developer mode](assets/Chrome%20extensions%20-%20Developer%20mode.jpg)

Click on *Load unpacked* and select the *dist* folder. The extension is now installed.
![click load unpacked](assets/Chrome%20extensions%20-%20Load%20unpacked.jpg)

When the *dist* folder is updated, either click on the reload icon next to your Chrome extension, or you can use [Extensions Reloader](https://chrome.google.com/webstore/detail/extensions-reloader/fimgfedafeadlieiabdeeaodndnlbhid) which gives the convenient ability to reload all unpacked extensions through a button click.

## Resources

* [Manifest file format (https://developer.chrome.com/docs/extensions/mv3/manifest/)](https://developer.chrome.com/docs/extensions/mv3/manifest/)