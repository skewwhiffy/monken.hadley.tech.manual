# Administrator tasks

## Introduction

As a system administrator, you have absolute power over the Umbraco system that powers the Monken Hadley School website. With great power comes great responsibility. As someone famous said once, [You've got the power](https://www.youtube.com/watch?v=_BRv9wGf5pk).

Administrator rights should only be used when necessary: if you get into the habit of using administrator rights to perform daily updates, you open up a security hole that someone could exploit. Moreover, depending on how badly you mess up, you have the potential to completely mess up the school website, whereas the damage you can do as a normal user is rather more limited.

If you are an administrator, and you are involved in updating the website as well, the first thing you should do is to make a user for everyday tasks. Reusing the password for both these accounts is okay (but it's probably better to not do so).

Below are certain tasks which you might need to do as an administrator.

## Recycling a user

* Login [here](https://monkenhadley.barnet.sch.uk/umbraco)
* In the left sidebar, there should be a 'Users' tab. Click on it.
* In the left side panel, expand the 'Users' folder.
* In the left side panel, click on a disabled user. Disabled users are faded out.
* Change the name, username, email, and user type as appropriate.
* Untick the 'Disable Umbraco Access' and 'Disable User' boxes
* Generally, new 'normal' users should only be granted rights to 'Content' and 'Media', so ensure that only the appropriate checkboxes are ticked under 'Sections' at the bottom of the page.
* Normal users should be set to *Writer* as *User type*. This allows them to change and rollback content without review, but not to change things like passwords.
* Click on the 'Save' button at the top right. If you don't do this, your changes will be forgotten, and you'll have to do it all again.

## Create new user

* It may be that the more appropriate course of action is to recycle an old user: Umbraco (for technical reasons) does not allow you to delete users for audit reasons.
* Login [here](https://monkenhadley.barnet.sch.uk/umbraco)
* In the left sidebar, there should be a 'Users' tab. Click on it.
* In the left side panel, if you float over the 'Users' folder, this should reveal an extension menu (indicated by three dots).
* Click on the three dots.
* Click on 'Create'.
* Umbraco will now guide you through the process. It will roughly match the instructions above for 'Recycling a user'.

## Change a user's password

* Login [here](https://monkenhadley.barnet.sch.uk/umbraco)
* In the left sidebar, there should be a 'Users' tab. Click on it.
* In the left side panel, expand the 'Users' folder.
* Click on the user whose password you want to change.
* Click on 'Change Your Password'. This is a little confusing as the text doesn't look like it's clickable, but it is.
* Enter a new password twice (or, even better, get the user in question to do it).
* If you have chosen a password for the user, tell that user what the new password is, and advise them that they should change their password as soon as they login for the first time.
* You should also direct the user to [here](./security.md) for some ideas how they can avoid forgetting their password again.

## Disabling a user

You should do this whenever someone should no longer have rights to access the website. For personal data reasons, you should also change any personal details of that user in the system.

It's very rare for a known user to access websites with malicious intent, but the consequences can be catastrophic: for example, imagine that a disgruntled ex-member of staff accidentally retains access to the website, and uploads illegal material to the official school website. Not only does this look bad for the school, not only does the reputation of the school suffer, there may also be cripplingly expensive legal repercussions.

It's very rare, of course, but best to be prepared, and make sure that the list of users who can access the system is kept up-to-date.

* Login [here](https://monkenhadley.barnet.sch.uk/umbraco)
* In the left sidebar, there should be a 'Users' tab. Click on it.
* In the left side panel, expand the 'Users' folder.
* Click on the user who you want to disable.
* Tick the 'Disable Umbraco Access' checkbox.
