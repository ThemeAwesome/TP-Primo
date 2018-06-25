# Changelog

### [1.1.0] 2018-06-26
###### `Added`
* Added inline styles to the activation area. The word "Active" is now more vertically centered and is bold.
* Added inline styles to the Customizer and Documentation links on the main plugin page. This was done to make them standout for new users.
* Added the `Sticky Nav`,`Scroll Hide Nav` and `Sticky Shrink Nav` options to the `Navigation > Layout` section.
* Added missing styles to `tp-primo-styles.css` pertaining to setting a page or post to 100% width in the `Post/Page Options` metabox. I thought I had added this previously, which I did, but there was another portion that need to be added.

###### `Changed`
* Moved the activation and licensing script to the admin folder instead of the asset folder.
* Modified code for the metaboxes. Now metaboxes will show for any custom post type. 

###### `Removed`
* Removed the changelog.txt file. The readme.txt file will hold all of the changes to the plugin. This is also used by the update script to deliver the changes to the update screen.
* Removed the option to switch to the old comment form and back. In general this is not used and just takes up space.

###### [1.0.3] 2018-05-12
###### `Changed`
* One of the new controls that was added to `General > Layout` called `Right and Left Sidebar Content Width` was set to a `number control` as I was trying to work out the best solution to implement this area. I had chosen a `select` control but wanted to see if the `number` control would possibly work better. r my tests I faild to switch it back to a `select` control.

###### [1.0.2] 2018-05-11
###### `Added`
* Plugin activation for licensing and updates - users who receive a license key, will now receieve a notification that an update is available for the plugin. Users of the Lifetime Access Pass will also receive an update notification.
* Ability to change the width of the main content container which changes the width of the sidebars.
* Made the notices that appear after installation closeable.
* Added the ability to change the background color of widgets in all of the sidebar areas.
* Background color control to the main Top Sidebar container.
* Background color control to the main Header container.
* Background color control to the main Navigation container.
* Background color control to the main Content container.
* Background color control to the main Footer Widgets container.
* Background color control to the main Footer container.

###### `Removed`
* All reference, styles and code for the Social Icons which were a part of TotalPress as well as TP Primo. These were removed because of the removal of Font Awesome.

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


