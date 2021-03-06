# DemoWebApp

Check it out at: http://hs-mongodb-demo.herokuapp.com/

Before starting: 
- create Heroku account
  - primary language = node
- create Github account
- install command line tools for each 
  - heroku: https://toolbelt.heroku.com/ 
  - github: https://help.github.com/articles/set-up-git/#setting-up-git
- install Node.js and npm

To set up and run:

- fork project at https://github.com/allivent/DemoWebApp.git

- `heroku login`
- `git clone https://github.com/YourUserName/DemoWebApp.git`
- `cd DemoWebApp`

- `heroku create`
- `git push heroku master`
- `heroku open` 

- `npm install`
- `heroku local web`
- check out http://localhost:5000

To set up mongodb:

- Add mLab MongoDB Sandbox to Heroku
  - (https://devcenter.heroku.com/articles/mongolab)
  - Add db credentials/URI to your .env file to test locally
- Setup and add Mongoose to your webapp
  - (http://mongoosejs.com/docs/index.html)
