# ldstats - Ludum Dare Ratings
Ratings API for Ludum Dare. Check it [out here](http://ldstats.info)

## Compile and run the project

### It's required to have installed
* [Node 0.10+](http://nodejs.org/)
* [Mongo 2.4+](https://www.mongodb.org/)
* [NPM 2+](http://npmjs.org/)

if you have npm v1 update it by
```bash
npm install -g npm
```

To get started:  
1. Clone this project  
2. `cd ldstats/`

To configure the server you must add a `config/config.json`, a config.sample file can be used as a base for that file.

After created that config file:

```bash
npm install
```

Now run the server:
```bash
npm start
```
