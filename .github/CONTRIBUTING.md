# Contributing

The primary grammar file is available in [`prim.tmLanguage.yml`](../syntaxes/prim.tmLanguage.yml). The other grammar, [`prim.md.tmLanguage.yml`](../syntaxes/prim.md.tmLanguage.yml), provides support for `prim` highlighting in Markdown files.

## Local Installation

To install this extension, run:

```sh
$ npm run install-package
```

## Testing

Tests are written using [`vscode-tmgrammar-test`](https://github.com/PanAeon/vscode-tmgrammar-test). See their README for instructions on how to interpret the syntax of these `.snap` files.

To run these tests locally:

```sh
$ npm install
$ npm test
# To apply changes to the snapshots, run:
$ npm test -- -u
```

## Resources

See:

- [VSCode Syntax Highlighting Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [TextMate Grammars](https://macromates.com/manual/en/language_grammars): includes the [canonical explanation of common scopes](https://macromates.com/manual/en/language_grammars#naming_conventions)
- [Exhaustive list of common TextMate scopes](https://github.com/psmitt/metalanguage/blob/master/examples/ScopeList.ScopeList)
- [Example Go TextMate Grammar](https://github.com/microsoft/vscode-textmate/blob/main/test-cases/themes/go/go.json)
- [Example TypeScript TextMate Grammar](https://github.com/microsoft/TypeScript-TmLanguage/blob/master/TypeScript.YAML-tmLanguage)
- [TextMate Grammar Guide](http://www.apeth.com/nonblog/stories/textmatebundle.html): good introduction to TextMate grammars
- [TextMate Grammar Guide (for Atom)](https://gist.github.com/Aerijo/b8c82d647db783187804e86fa0a604a1): bit more modern than the one above. you can ignore the Atom content.
- [How to inject custom language highlighting into Markdown](https://github.com/mjbvz/vscode-fenced-code-block-grammar-injection-example)
