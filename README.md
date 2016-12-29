# babel-preset-nite

> Babel preset for all Nite plugins.

## Install

Install the CLI and this preset

```sh
npm install --save-dev babel-cli babel-preset-nite
```

Make a .babelrc config file with the preset

```sh
echo '{ "presets": ["nite"] }' > .babelrc
```

Create a file to run on

```sh
echo '<h1>Hello, world!</h1>' > index.js
```

View the output

```sh
./node_modules/.bin/babel index.js
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["nite"]
}
```

### Via CLI

```sh
babel script.js --presets nite
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["nite"]
});
```
