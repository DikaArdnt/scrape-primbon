# scrape-primbon

## Instalation :
```
npm i primbon-scraper
```

## Usage:
```js
const Primbon = require('scrape-primbon')
const primbon = new Primbon()
```

## Example
```js
const Primbon = require('scrape-primbon')
const primbon = new Primbon()

//Nomer Hoki
primbon.nomer_hoki('6288292024190').then((res) => {
    console.log(res)
})

//Penafsiran Mimpi
primbon.tafsir_mimpi('pipis').then((res) => {
    console.log(res)
})

```
