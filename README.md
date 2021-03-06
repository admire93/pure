Pure
====

[Collaborative blogging theme](http://purepelican.com) based on [Purecss](http:purecss.io) for [Pelican](http://docs.getpelican.com/) blogs.
Theme is responsive.

## PELICANCONF.PY

* `COVER_IMG_URL` - Set the sidebar image.
* `PROFILE_IMAGE_URL` - Set the image for the top circle cutout.
* `TAGLINE` - Used for the page titles and some meta tags.
* `DISQUS_SITENAME` - Set this to enable disqus comments in articles.
* `GOOGLE_ANALYTICS` - Set the Google Analytics code (eg. "UA-000000-00"
* `SOCIAL` - Set some social links in the sidebar. The format should be like this:

    ```python
    SOCIAL = (
        ('github', 'https://github.com/example/'),
        ('twitter-square', 'https://twitter.com/example'),
    )
    ```
    where the first value of the tuple is the icon name from http://fontawesome.io/icons/ after stripping `fa-` (eg. `fa-github` will be `github`)


## Custom metadata:
* `about_author` - displayed on article page

## PREVIEW

![Pure preview](http://i.imgur.com/lqCJVrF.png)

![Pure preview](http://i.imgur.com/eCUsyGk.png)

![Pure preview](http://i.imgur.com/RkYxMIl.png)

See it live at [testpy.org](http://testpy.org/)

## Aditional features
* [FitVids](https://github.com/davatron5000/FitVids.js) jQuery plugin for fluid width video embeds.
