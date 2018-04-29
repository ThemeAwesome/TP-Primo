# Changelog

### [1.0.1] 2018-04-29
###### `Added`
* `changelog.txt` to keep track of any and all changes made to the plugin. Also created a GitHub repo to maintain a changelog file as well.
* Added the function to remove the upsell section when the plugin is activated.

###### `Removed`
* Removed Public folder. It was not being used so not needed.
* The entire list of Google Fonts (over 800 of them) with an empty array. This seems to pull in all of the Google fonts and makes the plugin size smaller. See this thread: https://wordpress.org/support/topic/load-all-google-fonts/
* Removed theme notification that displayed if the plugin is deactivated. This was causing an error when the plugin was deactivated and you tried to leave the plugin page.
* Reworked the `back to top` section, the arrow specifically. Font Awesome was removed in Totalpress so this removed the arrow from the back to top button. Back to Top button uses a pure css arrow.

##### [1.0.0] 2018-04-16
* Hello World.
