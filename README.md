## Description

A simple Quran API with GET endpoints by chapter/verse

## Demo

[Try it here](https://nomadigital.github.io/simple-quran-api)

## Quickstart

### Base GET endpoint

```
https://nomadigital.github.io/simple-quran-api/api
```

| variable | description   | format          | example |
|:--------:|:-------------:|:---------------:|:-------:|
| lang     | language code | string          | ar      |
| sura     | sura number   | 3 digits number | 002     |
| aya      | aya number    | 3 digits number | 003     |
| page     | page number   | integer         | 4       |

### GET Sura page

```
/:lang/s:sura-:page.json
```

Example to get third page of Sura Al-Baqara in Arabic:

https://nomadigital.github.io/simple-quran-api/api/ar/s002-3.json

### GET Aya page

```
/:lang/s:sura/v:aya.json
```

Example to get Aya 286 (Aya Al-Kursi) of Sura Al-Baqara in English:

https://nomadigital.github.io/simple-quran-api/api/en/s002/v255.json

## Credits

- API build: [static-api-generator](https://github.com/eduardoboucas/static-api-generator)
- Translation: [tanzil.net](http://tanzil.net/docs/)
