Features of this boilerplate:
-----------------------------

- Jinja2
- Markupsafe for speed
- NDB
- Python 2.7 multi-threaded
- base template for shared HTML
- .gitignore
- BaseHandler
 - Makes common globals available to template.
 - Streamlines common functions like template out and output to page.
- Robots.txt that disallows all appspot.com crawling to avoid duplicate crawls
- HTML5 Boilerplate
- Twitter Bootstrap
- Font Awesome icon font library
- Beautiful and versatile Open Sans Google Web Font
- Includes jQuery and JSON parser in lib.js
- Debug mode set only on local side
- favicon.ico to prevent 404's and extra requests
- 999 day expiration on static files.
- App version in query string to automate client-side cache expiration. (TODO: fix for squid proxy)
- Blank yaml configs with commented examples
 - queue.yaml for configuring task queue
 - dos.yaml for blacklisting IP's
 - backends.yaml
 - cron.yaml
- Proven folder structure for organizing large apps
 - templates/subtemplates for jinja2 {% include templates/subtemplates/name.html %}