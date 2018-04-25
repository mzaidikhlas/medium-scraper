# medium-scraper

### Installing
```
npm install medium-scraper
```

## Getting Started
medium-scrapper allows for you to scrape latests article from a user

### Example
```javascript
  scraper = require("medium-scraper");

  var medium = {user: "@nearbycoder"}

  scraper.getPosts(medium).then(function(results) {
    console.log(results)
  })
```

### Results
```json
[
    {
        "title":"How To Start a Pair Programming Routine",
        "time":"Jun 26, 2017",
        "image":"https://cdn-images-1.medium.com/max/900/1*oIhBCXd78UWsbA0T2EVApQ.jpeg",
        "url":"https://medium.com/made-by-munsters/how-to-start-a-pair-programming-routine-3d51a349dcd3",
        "claps":"1"
    },
    {
        "title":"",
        "time":"May 24, 2017",
        "image":"https://cdn-images-1.medium.com/max/900/1*rVK1L0kH1ABLvtY2Z0qIDg.jpeg",
        "url":"https://medium.com/made-by-munsters/automate-your-slack-status-612087714d3b",
        "claps":"12"
    },
    {
        "title":"We’re Presenting at Tulsa TechFest",
        "time":"Jul 22, 2016",
        "image":null,
        "url":"https://medium.com/made-by-munsters/were-presenting-at-tulsa-techfest-682efde980d9",
        "claps":"1"
    },
    {
        "title":"",
        "time":"Jul 1, 2016",
        "image":"https://cdn-images-1.medium.com/max/900/0*qOVLWAPfZPY6bNcF.png",
        "url":"https://medium.com/made-by-munsters/ruby-remote-conf-recap-c87f00c05db2",
        "claps":"2"
    },
    {
        "title":"Getting Around API Rate Limiting",
        "time":"May 19, 2016",
        "image":null,
        "url":"https://medium.com/made-by-munsters/getting-around-api-rate-limiting-642b7790b225",
        "claps":"1"
    },
    {
        "title":"Welcome Back TulsaJS",
        "time":"May 11, 2016",
        "image":null,
        "url":"https://medium.com/made-by-munsters/welcome-back-tulsajs-cd73fec008ac",
        "claps":"1"
    },
    {
        "title":"Writing Angular with Webpack and es6",
        "time":"Apr 14, 2016",
        "image":null,
        "url":"https://medium.com/made-by-munsters/writing-angular-with-webpack-and-es6-e84cc668f827",
        "claps":"3"
    },
    {
        "title":"",
        "time":"Apr 5, 2016",
        "image":"https://cdn-images-1.medium.com/max/900/1*3jXyhPHEuXR4kTcaJmoBVQ.jpeg",
        "url":"https://medium.com/made-by-munsters/authorizing-trello-integration-with-angular-13eb6b85de88",
        "claps":"1"
    },
    {
        "title":"Commit with Intent",
        "time":"Mar 15, 2016",
        "image":null,
        "url":"https://medium.com/made-by-munsters/commit-with-intent-b0bb67bea50a",
        "claps":"1"
    },
    {
        "title":"How I learned failure as a developer",
        "time":"Jan 12, 2016",
        "image":null,
        "url":"https://medium.com/@nearbycoder/how-i-learned-failure-as-a-developer-94429e4a971c",
        "claps":"2"
    }
]
```
