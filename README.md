# remove-undefined

Remove properties with the value `undefined` from an `Object`.

## Installation

npm

```
$ npm install remove-undefined
```

yarn

```
$ yarn add remove-undefined
```

## Usage

```js
const removeUndefined = require('remove-undefined');

const ringDonut = { sugar: true, filling: undefined };

console.log(ringDonut); // -> { sugar: true, filling: undefined }
console.log(removeUndefined(ringDonut)); // -> { sugar: true }
```

## License

MIT
