A Django-Python application to manage hard-copy comic books

# Introduction #

I recently got into comics and as a burgeonin pythonista, I decided to put together a django-python app to keep track of all of the comics I've bought, the comics I've subscribed too, and the comics I want.

As I mentioned, I am learning django, but "think" I know Python. If you see any suggestions in the source code, please let me know. Also, if you have any suggestions for how I can extend the app, I'll entertain those as well.


# Details #

This is my first attempt at a Django app. I'm pleased with how easy it is to learn and I hope it shows in the code. I didn't take the time to put together an install package. It is only offered as source code.

FWIW, I've developed this application on both Linux (Ubuntu 7.10) and Windows XP, both with Python 2.5 and MySql. Of course the beauty of Django is that the DB doesn't matter.


  * Text in **bold** or _italic_

# What is planned for the coming versions #
  * Master HTML template
  * Filtering the book list by title/publisher
  * paging through lists (books, subs, etc)
  * CSS and "prettifying" the site.
  * Want List
  * Manage Subscriptions
  * Login/Authentication/Session
  * Extend the models to accommodate entries by user id, so that multiple users can use the same application.
  * I've read the APress book on Django. They are pretty high on caching data, so I may put in some caching for some pages.
  * Edit books, subscriptions, wants...as opposed to view only or editing through the admin site.

# What is in the initial 0.1a version #
  * Main Menu and basic navigation
  * Adding a book
  * Seeing the book list
  * Searching by comic title
  * Test data
  * Exporting the entire data-base, by model, to XML