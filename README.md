A simple one page static website where to serve as a testbed for front end development.

Stack:
- Vanilla HTML/CSS
- Bootstrap 3

Clone or download this project to see how it looks.

The app has been deployed to heroku and can be accessed here:

https://thehimalayas.herokuapp.com/

NOTES:

- I have connected my Heroku account with my github profile such that whenever a change is committed to this repo, the diff gets pushed to heroku automatically (CI/CD) which re-deploys the app. Heroku does this via web hooks.

- Heroku is an app server and as such doesn't 'allow' you to host purely static files. The workaround
is to make Heroku think this is a Python app serving the home.html on the '/' route. If you are familiar
with Flask, you will recognize the app structure pretty well.