# lint101

An example of linter use.

## Install and Run

```shell
git clone https://github.com/portsoc/lint101.git
cd lint101
npm install
npm test
```

Installing and running should highlight 15 errors.  These are
identified using the [ESLinter recommended
rules](http://eslint.org/docs/rules/), as well as extras that are
added by our [eslint-config-portsoc](https://github.com/portsoc/eslint-config-portsoc) extension`

## Rule Extensions

There are many different rule sets that can be used as a base for your
linting.  We have created the `eslint-config-portsoc` rule set so you
have a standard that you can code against that will make your code
look the same as ours.  This consistency should help you read our,
code and it will make it easier when you ask for help because we'll be
able to discount many potential sources of error immediately.


## Installing a linter in your preferred editor
### Atom
There are several linter options in Atom; for example, the [linter](https://atom.io/packages/linter) package is an extensible base-linter that supports [eslint](https://atom.io/packages/linter-eslint) and [many other linting tools](http://atomlinter.github.io/)

```shell
apm install linter
apm install linter-eslint
```

Once installed, the errors that are reported by `npm test` should appear alongside the code in your editor, giving you edit-time feedback.

