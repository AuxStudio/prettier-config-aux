# prettier-config-aux

The Prettier config that we use internally.

## Installation

1. Add dependencies:

```
yarn add --dev prettier prettier-config-aux
```

2. Create `prettier.config.js` in `./`:

```js
module.exports = require('prettier-config-aux');
```

## Development

1. Clone the project:

```
git clone https://github.com/AuxStudio/prettier-config-aux
```

2. Do some work.
3. Create a PR.

## Releases

1. Run tests to make sure that they're passing.

```
yarn test
```

2. Login to npm

```
npm login
```

3. Run the publish script.

```
npm publish
```
