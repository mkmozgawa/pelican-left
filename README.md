# Pelican Left

Left is a clean, whitespace-happy theme for [Pelican](http://getpelican.com).
Although the original theme was extracted from [scottchacon.com](http://scottchacon.com/)
and targeted to [Jekyll](https://github.com/mojombo/jekyll), I've tried to adapt it so
that it can be used with Pelican and modernized to use HTML5 semantic elements.


[![Pelican Left](http://i.imgur.com/NT0iQ70.png)](http://hernantz.github.io "Live Demo")


## Customization

This theme tries to be compatible with the other themes and can be tuned 
with the following settings in your `pelicanconf.py` file.

| Setting name     | What does it do?                                                                                                        |
|------------------|-------------------------------------------------------------------------------------------------------------------------|
| SITENAME         | The title of the blog that appears only in the index page                                                               |
| SITESUBTITLE     | A subtitle to appear next to the `SITENAME`.                                                                            |
| DISQUS_SITENAME  | Pelican can handle Disqus comments. Specify the Disqus sitename identifier here.                                        |
| GOOGLE_ANALYTICS | Set to 'UA-XXXX-YYYY' to activate Google Analytics.                                                                     |
| MENUITEMS        | A list of tuples (Title, URL) for additional menu, items to appear at the left side column.                             |
| PIWIK_URL        | URL to your Piwik server - without 'http://' at the beginning.                                                          |
| PIWIK_SSL_URL    | If the SSL-URL differs from the normal Piwik-URL you have to include this setting too. (optional)                       |
| PIWIK_SITE_ID    | ID for the monitored website. You can find the ID in the Piwik admin interface > Settings > Websites.                   |
| LINKS            | A list of tuples (Title, URL) for links to appear at the left side column.                                              |
| SOCIAL           | A list of tuples (Title, URL) to appear as `font-awesome` icons in the. "social" section, below the avatar/author name. |

Next, place your custom `avatar.png` and `favicon.ico` files in the `images/` folder of
your pelican blog.


## Licensing

This is [MIT](https://github.com/hernantz/pelican-left/blob/master/LICENSE) with no
added caveats, so feel free to use this on your site without linking back to
me or using a disclaimer or anything silly like that.
