# firefox-styling
My custom Firefox CSS config to make Firefox look better.

# Setup
### Enable userChrome customization in about:config

    - Navigate to about:config in the address bar and accept the risks.

    - Search for toolkit.legacyUserProfileCustomizations.stylesheets and toggle it to true (by double clicking on it).

### Locate and open your profile folder using about:support

    - Click on ☰ ➝ Help ➝ "More Troubleshooting Information" or navigate to about:support in your address bar.

    - Under Application Basics, click on the the Open Folder button next to "Profile folder". You should now see your profile folder being opened in your file manager.

Some people on on MacOS have had the button open the parent folder of the current profile folder. Make sure the opened folder path matches what is listed in about:support.

### Live-editing userChrome.css

If you're writing the styles yourself, you can set up browser toolbox and edit the files directly in it without having to restart Firefox for changes to apply. (You still need to restart Firefox when creating userChrome.css). 

On top of being able to live-edit userChrome.css, the browser toolbox is essential in figuring out how to add custom styling to various parts of Firefox.

You can find userChrome.css in the browser toolbox like this:

    - Open browser toolbox
    
    - Activate the Style Editor tab of the toolbox
    
    - Locate userChrome.css in the sidebar list of all the stylesheet
