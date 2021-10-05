# Messaging App with Node.js
API to push User data to React FrontEnd Messaging App
Pusher used for real-time data in combination with Mongodb

## VALUES TO REPLACE
- server.js - Pusher API & Mongo Connection Data
```console
const connection_url = 'mongodb+srv://<username>:<password>@<cluster>.onmdo.mongodb.net/<database>?retryWrites=true&w=majority'
const pusher = new Pusher({
    appId: "APPID",
    key: "KEY",
    secret: "SECRET",
    cluster: "LOCATION",
    useTLS: true
  });
```

## Heroku Hosting
```console
heroku login
heroku create
heroku git:remote -a <app>
git push heroku <branch>
```