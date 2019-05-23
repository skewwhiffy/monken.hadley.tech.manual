# The missing guide to updating the Monken Hadley school website

## Summary

The objective of this guide is to act a reference to how to update the school's website. It is a dynamic document in the sense that changes can be made to it relatively easily: please ask a system administrator if you spot errors here.

Once you're confident enough, try some of the tasks outlined in the [exercises](./exercises.md) to get yourself happy.

### Printing this document

I mean, I suppose you could, if you really wanted. But think of the trees that you would be directly responsible for killing, and what you would do if this document changes. It's probably worth you using this guide online. If you really want, you could look at this on your smartphone or pad so that you can have it by your side while you're doing work.

## Overview

The [Monken Hadley Website](https://monkenhadley.barnet.sch.uk) is a site to showcase the school on the internet. It also acts as an information hub for staff and parents of students alike.

The Monken Hadley website is hosted at [Nutty About Hosting](https://www.nuttyabouthosting.co.uk). Credentials for the account there are held by the headteacher.

Content and documents are managed using [Umbraco](https://umbraco.com/), a piece of software called a *Content Management System*, or *CMS*. CMSs are designed so that updates to relatively simple websites (like the school's) can be done with minimal technical knowledge. It's not the easiest piece of software to learn, but it doesn't require particularly technical/geeky/scary skills.

DNS records are hosted at [names.co.uk](https://login.names.co.uk/login). Credentials for the account there are held by the headteacher.

**WARNING** Changing the settings for the site is dangerous: make sure you know what you are doing before making any changes to the hosting or technical settings on this account.

**WARNING** Changing the DNS settings for the site is dangerous: make sure you know what you are doing before making any changes to the DNS settings on this account.

## Accessing the system

### Getting credentials

* Get some credentials. If you don't already have credentials, you will need to ask a site administrator. If you don't know who the site administrators are, you should ask the headteacher.
* If you've forgotten your username or password, you will have to ask for a password reset from the site administrator. Although the login page seems to link to a password reset page, this is actually a lie, and it won't work: a site administrator will have to reset your password for you.
* Keep your credentials safe, have a read of [this](./security.md).
* **WARNING** DO NOT share your credentials. This would mean that someone else can make changes to the website without any accountability, and their actions will be attributable to you.

### Logging in

* Just go to the [login page](https://monkenhadley.barnet.sch.uk/umbraco).

### Changing your password

* Log in.
* Click on your avatar at the top left. By default, this is just a sillhouetto of a man.
* You should see a side panel with a button marked 'Change password'. Click the button.
* Type your new password, and confirm.
* Click on the button marked 'Change password'.
* You might want to verify that this has worked: you can logout by clicking your avatar again.
* Keep your credentials safe, have a read of [this](./security.md).
* **WARNING** DO NOT share your credentials. This would mean that someone else can make changes to the website without any accountability, and their actions will be attributable to you.

### Forgotten your password

* You silly sausage. You should read [this](./security.md) for some ideas how not to forget your password.
* You need to find a system administrator to change your password for you.
* The headteacher should be an administrator, or at least will know who is.
* The procedure for resetting your password is outlined on [this page](./admin.md).

### Changing content

* Log in.

There are two types of content on the website, and the procedures for changing them are slightly different.

* Straight text - see [here](./change.text.md)
* Downloadable documents - **TODO**
