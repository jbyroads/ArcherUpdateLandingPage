# ArcherUpdateLandingPage
Utility for updating a user's landing page in Archer.

## Background
The RSA Archer eGRC platform has a limitation when it comes to updating the landing page a given user is passed to upon logging into the web interface.  Once a user account has been created and a landing page has been assigned, it is not possible to bulk update a set of users that may belong to the same group.  The only way to update users is to go one by one into their profile and manually change the landing page.  This utility provides a mechanism for bulk update.

## Instructions
1) Provide an IP address or hostname of the Archer SQL database.
2) Select the appropriate mechanism for authentication.
3) Click the dropdown box under "Select Instance Database" to choose the appropriate Archer instance database.
4) Optionally test the connectivity.
5) Select the method for updating landing pages.
  A) Select User.  Search for a specific user.  Set values for landing page.
  B) Select Group.  Search for a group.  Set values for landing page.
6) Click execute.  This will update the user(s) landing page appropriately.

![alt text](https://github.com/jbyroads/ArcherUpdateLandingPage/blob/master/updatelandingpage.PNG)
