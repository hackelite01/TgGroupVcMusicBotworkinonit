# Group Music Vc Bot - Heroku

To make this repo compatible with heroku and avoid unnecessary conflicts
we have to break down this whole project into two different parts and
deploy as different apps so let's get started.
### Webserver setup
* deploy [this](https://github.com/hackelite01/TgGroupVcMusicBot) repo in heroku (you can use ```deploy to heroku``` button for easy peasy deployment)
* after deploying your app turn on the dyno and copy your app url (something like ```http://yourapp.herokuapp.com```)
* That's it 

### Bot
Here is the place where this repo (which you are reading this readme) comes into picture
* As usual hit deploy to heroku button
* Enter bot token and websocket url (which we got from the above step)
* click deploy and sit back until docker finishes the build
* turn on your dyno (if its off)
* if everything goes fine you should see something like ```@username is running...``` in the log
* Voila!



[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/hackelite01/TgGroupVcMusicBot)

# Join Us on Telegram

<a href="https://t.me/hackelite01"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram" width="190" height="28"></a>