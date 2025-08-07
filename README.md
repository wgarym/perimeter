# Simple JSON API using GitHub Pages

This repo serves `data.json` as a static API.

## Access JSON

Once GitHub Pages is enabled, visit:

https://<your-username>.github.io/json-api-example/data.json

## How to Use

You can fetch this in any web or mobile app:

```js
fetch("https://<your-username>.github.io/json-api-example/data.json")
  .then(res => res.json())
  .then(data => console.log(data));
