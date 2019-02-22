# eslint-plugin-eslint-gammadia

Gammadia&#39;s ESLint rules

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-eslint-gammadia`:

```
$ npm install eslint-plugin-eslint-gammadia --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-eslint-gammadia` globally.

## Usage

Add `eslint-gammadia` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "eslint-gammadia"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "eslint-gammadia/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





