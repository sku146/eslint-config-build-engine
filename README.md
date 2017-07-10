# eslint-config-build-engine
Collection of ESLint rules to use for all the development environments (ex: nodejs, react, webpack, etc..,)

## Installation

You'll install `eslint-config-build-engine`:

```
$ npm install eslint-config-build-engine --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-coonfig-build-engine` globally.

## Usage

Add `build-engine` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-config-` prefix:

```json
{
    "extends": [
        "build-engine"
    ]
}
```

## For React

```json
{
    "extends": [
        "build-engine/react"
    ]
}
```

## For Jasmine

```json
{
    "extends": [
        "build-engine/jasmine"
    ]
}
```


## For Lodash 

```json
{
    "extends": [
        "build-engine/lodash"
    ]
}
```

## For Jest 

```json
{
    "extends": [
        "build-engine/jest"
    ]
}
```

## For Webpack 

```json
{
    "extends": [
        "build-engine/webpack"
    ]
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)