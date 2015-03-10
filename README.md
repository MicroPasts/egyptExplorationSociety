Photographic transcription of the Egypt Exploration Society Archives
====================================================================

An application for interacting with the Egypt Exploration Society Flickr stream to produce structured, transcribed data
from their rich image archive.

This application has three files:

* createTasks.py: for creating the application in PyBossa, and fill it with some tasks.
* template.html: the view for every task and deal with the data of the answers.
* tutorial.html: a simple tutorial for the volunteers.
* config.py.template: for configuring the Flickr API KEY (required!)

As Pybossa now has a built in Flickr, the createTasks.py file does not need to run the add tasks command, however, this
will be left in, so if you feel like using it, do.

Updating template
=================

After making changes to your source code and committing to github do the following:

*  Clone or pull changes from repo to your server and then issue this command:

```bash
    $ python createTasks.py -k APIKEY -s SERVERURL -t
```

*  Template should update

LICENSE
=======

Please, see the COPYING file.


Acknowledgments
===============

This application is on behalf of the Egypt Exploration Society.
[![EES logo](http://www.ees.ac.uk/images/logo.gif)](http://www.ees.ac.uk)




