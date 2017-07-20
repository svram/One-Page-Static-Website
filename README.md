A simple one page static website where to serve as a testbed for front end development.

Stack:
- Vanilla HTML/CSS
- Bootstrap 3

Clone or download this project to see how it looks.

The app has been deployed to heroku and can be accessed here:

http://thehimalayas.herokuapp.com/

NOTES:

- I have connected my Heroku account with my github profile such that whenever a change is push to this repo, the diff gets
pushed to heroku automatically (CI/CD). Heroku does this via web hooks

- Heroku is an app server and as such doesn't 'allow' you to host purely static files. The workaround
is to make Heroku think this is a PHP app (attribution to stack overflow here). The index.html is server
from the index.php. 

TODO:

Convert to Flask app
