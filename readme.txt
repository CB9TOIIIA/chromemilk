ChromeMilk
A Remember the Milk extension for Google Chrome.

ChromeMilk lets you access your tasks right from your Chrome toolbar.
Clicking the button can show a popup with RTM's iGoogle, Gmail, or iPhone gadgets, or just open the RTM page when clicked.
Button can also show the number of incomplete tasks due today, or a custom search.
Go to the options page to customize the extension to your liking.

Known Issues

* iPhone version doesn't log in and the password isn't obscured when using Tab to type the password. The workaround is to use the mouse to select the password input box instead. This is an issue of the Remember the Milk iPhone web app itself and I cannot fix this.
* Sometimes authentication will fail. Erase all settings and try to authenticate again.

This extension is still under heavy development and may be buggy. Please report any issues on the Google Code project page: http://code.google.com/p/chromemilk/issues/

Changelog

0.9.6 - 11 Mar 2010
* New icon, by the amazing Camila Gonz�lez
* Fixed a bug when using OR in the custom filter (thanks downing.c!)
* Popups now use HTTPS instead of HTTP
* Icons to open extenions settings and RTM page added to popup.
* When "No popup, load Remember the Milk web page" option is selected, or New Window icon is clicked, if an existing RTM tab exists, it will be selected instead of opening a new tab. (thanks Gordon Fontenot!)

0.9.5 - 22 Jan 2010
* Badge is now reloaded after clicking the icon, in addition to once a minute.
* No more flashing popup when No Popup option is selected

0.9.4 - 16 Dec 2009
* Reverted permissions back to only tabs and api.rememberthemilk.com
* Added error detection for authentication

0.9.3 - 11 Dec 2009
* New mobile view option added.
* Cosmetic changes to the options page.
* Popup now has extension name and link to options for changing setting more quickly.
* Changes to badge-related options now appear immediately. No more waiting a minute to turn the badge on and off.

0.9.2 - 8 Dec 2009
* New icon; due to RTM's branding guidelines I can't use the cow icon.
* Better authentication management. Hopefully this will fix all authentication errors.
* Button to erase all settings added.

0.9.1 - 7 Dec 2009
* Corrected bugs in counting incomplete tasks.

0.9 - 6 Dec 2009
* Initial release

Credits and License

Author: Juliana Pe�a
Website: http://julianapena.com
Twitter: @limitedmage

Acknowledgements:
* Remember the Milk http://rememberthemilk.com
for their awesome service and open API
* jQuery http://jquery.com
for the amazing JavaScript library that makes Ajax super-simple
* Gamila Gonz�lez http://aconitehikaru.deviantart.com/
for the great icon (Icon under a Creative Commons Attribution-Attribution-Share Alike 3.0 License. http://creativecommons.org/licenses/by-sa/3.0/)

This extension is open source under the GPLv2.
http://creativecommons.org/licenses/GPL/2.0/
Source code is available at http://code.google.com/p/chromemilk/