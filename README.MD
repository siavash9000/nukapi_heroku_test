1. If you don't have one create a Heroku account https://signup.heroku.com/
2. Fork this repo on Github.
3. Create an App on Heroku via the Heroku Web-Ui and connect your Github Account with the Heroku app
4. Choose the forked repo for the deployment.
5. Install the heroku cli https://devcenter.heroku.com/articles/heroku-cli#download-and-install
6. Run `heroku addons:create matomo --app your-app-name` and wait 3 minutes while your private matomo instance is created.
7. Open your Matomo instance via the Heroku Dashboard ("installed addons")
8. Replace the tracking snippet in `index.html` with the shown one and commit and push it to your git repo. If you have not activated auto deployment, you need to manually deploy via the heroku app.
9. Check if Reailtime tracking shows your visit on your app. If not please open an issue in this repo or contact support@nukapi.com
