# world-history-json

this repo uses JSON-files as a way to represent history of countries in a nice developer way. 
the primary goal is to make educational content so developers only have to make these informations beautiful and easy learnable.

## template

```json
{
  "year": 2020,
  "title": "TITLE",
  "shortDescription": "SHORT_DESC",
  "description": "DESC",
  "source": "",
  "type": 0
  "image": {
    "source": "",
    "width": 50
  }
}
```

there are 5 different types of historical events:

```json
"type": 0, //important historical event e.g. anschluss of austria, formation of the german empire
"type": 1, //political event e.g. government change (absolutismn to republic)
"type": 2, //cultural event e.g. goethe in germany, shakespeare in england
"type": 3, //scientifical event e.g. marie curie in poland
"type": 4, //militaristic event e.g. start of 30-years-war in austria
```
