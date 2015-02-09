# iOS prototype of Dropbox App

This is an iOS prototype of Dropbox, completed for Codepath. [See this week's assignment](http://courses.codepath.com/courses/ios_for_designers/week/1#!assignment).

__Time spent:__ About 12 hours

### Completed User Stories: 

__Project Requirements__
* [x] User can tap through the 3 welcome screens. (updated to use the optional swiping method)
* [x] User can follow the create user flow.
  * [x] On the create user form, the user can tap the back button to go to the page where they can sign in or create an account.
  * [x] Before creating the account, user can choose to read the terms of service.
  * [x] After creating the account, user can view the placeholders for Files, Photos, and Favorites as well as the Settings screen with scrolling.
  * [x] User can log out from the Settings screen.
* [x] User can follow the sign in flow.
  * [x] On the sign in form, the user can tap the back button to go to the page where they can sign in or create an account.
  * [x] User can tap the area for "Having trouble signing in?"
  * [x] User can log out from the Settings screen.

__Optional Work__
* [x] Optional: User can see a detail view for one of the files and can favorite the file.
* [x] Optional: User can actually type in the forms using UITextFields and can dismiss the keyboard with a tap.
  * [x] The keyboards match the text entry, including the email keyboard and a "secure text entry" for the password input.
* [x] Optional: User can swipe through the welcome screens instead of just tapping them.

__Notes__

* Played around with different keyboards for the forms
* Used a scroll view for the welcome screen swiping, stacked the three images horizontally, and included pagination. Got rid of horizontal scroll bar.
  * In the view controller's viewDidLoad section, added: 
``` scrollView.contentSize = CGSize(width: 960, height: scrollView.bounds.size.height) ```

### Walkthrough of App
![dropbox screencast](screencast/dropboxish-walkthrough.gif)
gif created with [licecap](http://www.cockos.com/licecap)
