Stopwords Esperanto (EO)
=======

[![Build Status](https://travis-ci.org/stopwords-iso/stopwords-eo.svg?branch=master)](https://travis-ci.org/stopwords-iso/stopwords-eo)

The most comprehensive collection of stopwords for the esperanto language.

A [multiple language](https://github.com/stopwords-iso/stopwords-iso) collection is also available.

### Usage

The collection comes in a
[JSON format](https://raw.githubusercontent.com/stopwords-iso/stopwords-eo/master/stopwords-eo.json) and a
[text format](https://raw.githubusercontent.com/stopwords-iso/stopwords-eo/master/stopwords-eo.txt).
You are free to use this collection any way you like.
It is only currently published on [npm](https://www.npmjs.com/stopwords-eo) and [bower](https://bower.io).

```sh
$ npm install stopwords-eo
```

```sh
$ bower install stopwords-eo
```

```js
// Node
const stopwords = require('stopwords-eo'); // array of stopwords
```

### Contributing

If you wish to remove or update some of the stopwords, please file an issue first before sending a PR on the repo of the specific language.

If you would like to add a stopword or a new set of stopwords, please add them as a new text file insie the `raw` directory then send a PR.

Please send a separate PR on the [main repo](https://github.com/stopwords-iso/stopwords-iso) to credit the source of the added stopwords.

### Credits

All stopwords sources are [listed on the main repo](https://github.com/stopwords-iso/stopwords-iso/blob/master/CREDITS.md).
