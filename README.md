# react-heroku-exercise
Instructions in [Geeks for Geeks](https://www.geeksforgeeks.org/how-to-deploy-react-app-to-heroku/)
- Created app on Heroku - heroku-react-exercise
- Add Buildpack in settings section of app<br>
    - https://buildpack-registry.s3.amazonaws.com/buildpacks/mars/create-react-app.tgz
- heroku git:remote -a heroku-react-exercise
- git remote -v
- git push heroku main