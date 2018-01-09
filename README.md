# 30-seconds-of-code-texteditorsnippets

Included in this repository are the files you need to import all the snippets from the amazing resource [30-seconds-of-code](https://30secondsofcode.org/) into you text editor of choice (VSCode, Atom + Sublime).

Make sure you ⭐️ the original repo [here](https://github.com/Chalarangelo/30-seconds-of-code)!

The files in this repo contain the **30-seconds-of-code** Snippets as of December 30th, 2017's release. The project is still under active development and not all the snippets contained herein are production ready. *You've been warned*.

## How to import the snippets

**VSCode**: Go to 'Preferences' > 'User snippets' and select the language 'Javascript', then paste in all the code from the `javascript.json` file. For more information checkout the [VSCode snippets docs.](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

**Atom**: Copy the code in the `snippets.cson` file into your own `snippets.cson` file located in `~./atom` directory. For more information checkout the [Atom snippets docs.](http://flight-manual.atom.io/using-atom/sections/snippets/)

**Sublime**: Move all the `*.sublime-snippet`'s into your `Packages/User` folder (technically you can store `*.sublime-snippet`'s in any package's folder but for simplicities sake `Packages/User` will be easiest to find). If your stuck make sure you check out the [Sublime snippets docs.](http://docs.sublimetext.info/en/latest/extensibility/snippets.html)

**Alfred**: If you're an Alfred powerpack user your in luck, there is an easy way to import the snippets using the file in this [repo](https://github.com/lslvxy/30-seconds-of-code-alfredsnippets).

**NPM**: You can of course access all of these snippets and more with the official 30-seconds-of-code [npm](https://www.npmjs.com/package/30-seconds-of-code) package by running `npm install 30-seconds-of-code`.

After the package is installed you may access a snippet(s) with the following notation for **node.js**: `import { snippetName, otherSnippet } from '_30s'` and/or **javascript**: `const { snippetName, otherSnippet } = require('_30s')`
## Special thanks

Mad props go out to the core team and all the contributors at [30-seconds-of-code](https://github.com/Chalarangelo/30-seconds-of-code) who have worked hard putting these snippets together. 🙏

## License

Creative Commons License

CC0 1.0 Universal