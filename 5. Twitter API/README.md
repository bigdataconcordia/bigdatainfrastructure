# Twitter API

Sign up for Twitter
```
https://twitter.com/signup
```

Twitter Apps Screen
```
https://apps.twitter.com/
```

Create New Twitter Apps
```
https://apps.twitter.com/app/new
```

Create a New File in nodejs-twitter Project folder
```
app.js
```

Install the Node Package for Twitter Streams using the NPM (node package manager) from the Project Folder (nodejs-twitter)
```
npm install twitter-stream-api --save
```
Note: --save makes it that you save a package.json file locally, so that the next time all you need to have is your package.json file saved to your git and typing npm install will install everything you need



Copy the Content from the Course App.js file to Yours

Add your Key, Secret, Tokens to the JSON
```
var keys = {
    consumer_key : "",
    consumer_secret : "",
    token : "",
    token_secret : ""
};
```
These Keys are available
```
https://apps.twitter.com/
Click App > Click Keys and Access Tokens
```

Run Twitter Streaming App from Project Folder in Terminal
```
node app.js
```
