old Todda.us code
=================

Overview
--------

A simple blog that lets one create posts and readers
can leave comments.

Official hosted version
at [www.anyblog.co](http://www.anyblog.co).

Setup
-----

1. Created a new app on Parse, see [getting started guide for Cloud Code](https://parse.com/docs/cloud_code_guide#started-installing).

2. Type `parse new .` in the directory where this
README resides, authenticate with your Parse credentials,
and choose the app name you created.

3. Delete `public/index.html`

4. Edit `cloud/app.js` and specify your `userEmail`, `userDisplayName`
and `userDescription`.

5. Type `parse deploy`. This deploys your app to Parse.

6. Configure the url where you can
reach your app. Go to your app's setting page and set
a unique subdomain for your Web Hosting url.

7. Go to yoursubdomain.parseapp.com and view your site

