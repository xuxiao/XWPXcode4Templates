Personal Xcode 4 templates


Mac OS
/Developer/Library/Xcode/Templates/

iOS
/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/

User's
~/Library/Developer/Xcode/Templates/


UIViewController
================

initReloadable
--------------

This method will be called in viewDidLoad.

What this method should do:

- Additional initialization of objects loaded with the nib file.
- Create and initalize reloadable objects.


deallocReloadable
-----------------

This method will be called in two places: viewDidUnload and dealloc.

This method should release:

- Objects loaded with the nib file (outlets)
- Objects created in initReloadable
- Objects created lazily at runtime and added to the view hierarchy (or retained as instance variables)

