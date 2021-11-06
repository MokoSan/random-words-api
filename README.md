# Random Word API
## Project Setup
1. `$ npm install`

2. `$ nodemon` or `$ node index.js`

## Current Languages:
- **EN** *- English*

- **NL** *- Dutch*

### How to use:

https://wordgenerator-api.herokuapp.com/api/v1/resources/words?lang=EN&amount=5

### There are 2 queries:

- **lang=EN** *- to specify the language.*

- **amount=5** *- the amount of random words. (max. 1000)*

### Example response:
```
{
    "data": {
        "language": "EN",
        "amount": 5,
        "words": [
            "humanitarian",
            "furniture",
            "committees",
            "surprised",
            "procedure"
        ]
    }
}
```