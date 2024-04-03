# API Translate Express

Create a Translate Api from google with Express JS

<img align="center" src="Screenshoot.png" />

## Installation
```sh
git clone https://github.com/fitri-hy/api-translate-express.git
cd api-translate-express
npm install api-translate-expressjs
```

## Create & Setup (.env)
```
# port
PORT='5000'

# rate 15 minute
LIMIT_RATE='15 * 60 * 1000'

# limit request
LIMIT_MAX='100'

# message over limit
LIMIT_MESSAGE='Too many requests from this IP, please try again later.'
```

## Create & Setup (index.js)
```
require('api-translate-expressjs');
```

## Run Project
```
node index.js
```

## Api Endpoint
```
http://localhost:5000/translate?text=<query>&from=<fromLang>&to=<toLang>
```

## Usage Example
```
http://localhost:5000/translate?text=cat&from=en&to=id
```

## Support Language
Go to <a href="https://www.ibm.com/docs/en/cognos-controller/10.4.2?topic=codes-language">Language Code</a>


Official Site: <a href="https://hy-tech.my.id/">VISIT</a>

