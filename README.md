# eslint-plugin-format-check

## init project
```bash
npm i -g yo
npm i -g generator-eslint
# eslint plugin
yo eslint:plugin
# eslint rule
yo eslint:rule
```

eslint check

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-format-check`:

```
$ npm install eslint-plugin-format-check --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-format-check` globally.

## Usage

Add `format-check` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "format-check"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "format-check/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





