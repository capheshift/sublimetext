Sublimetext packages
============
A set of recommended packages and tooling configurations for Cà phê shift.

Our conventional IDE for Front End development is SubLime Text 3.
Inside this folders are predefined snippets and settings for it:

### Sublime Text Recommended Plugins:

- [Alignment](https://github.com/wbond/sublime_alignment): Help align code for better readability (especially in long properties list). Shortcut has been switch to `ctrl+shift+a` due to conflicts with SublimeLinter
- [All Autocomplete](https://github.com/alienhard/SublimeAllAutocomplete): List and suggest completion for all the words appeared in opened files
- [Babel](https://github.com/babel/babel-sublime): Language definitions for [ES6+ JavaScript](http://kangax.github.io/compat-table/es6/) with [React JSX syntax](http://facebook.github.io/react/docs/jsx-in-depth.html) extensions.
- [Color Highlighter](https://github.com/Monnoroch/ColorHighlighter): is a plugin for the Sublime text 2 and 3, which underlays selected hexadecimal colorcodes (like "#FFFFFF", "rgb(255,255,255)", "white", etc.) with their real color. Also, plugin adds color picker to easily modify colors.
- [CSS3](https://github.com/y0ssar1an/CSS3): The most complete CSS support for Sublime Text 3
- [DocBlockr](https://github.com/spadgos/sublime-jsdocs): Simplifies writing DocBlock comments in Javascript, PHP, CoffeeScript, Actionscript...
- [EditorConfig](https://github.com/sindresorhus/editorconfig-sublime): Helps developers maintain consistent coding styles between different editors. See `.editorconfig` snippet.
- [Emmet](http://emmet.io/): Previously known as Zen Coding. Greatly enhance HTML & CSS workflow.
- [FuzzyFilePath](https://github.com/sagold/FuzzyFilePath): Autocomplete relative or absolute file paths in Sublime Text project folder. Similar to AutoFileName but with fuzzy search capability.
- [GitGutter](http://www.jisaacks.com/gitgutter): A [ST3] plugin to see git diff in gutter
- [Handlebars](https://github.com/daaain/Handlebars/): [ST3] package for Handlebars.js templates
- [Hex to HSL Color Converter](https://github.com/atadams/Hex-to-HSL-Color): plugin to convert CSS Hex colors to HSL
- [HTML-CSS-JS Prettify](https://github.com/victorporof/Sublime-HTMLPrettify): HTML, CSS, JavaScript and JSON code formatter for Sublime Text 2 and 3 via node.js
- [Insert Nums](https://github.com/jbrooksuk/InsertNums): A Sublime Text 2 and 3 plugin, that inserts (consecutive) numbers across multiple selections or modifies the selections' contents with expressions. Huge configurability.
- [JSCS-Formatter](https://github.com/TheSavior/SublimeJSCSFormatter): Sublime Text 3 Plugin to autoformat your javascript code according to the JSCS configuration files you already have.
- [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview): Preview and build your markdown files quickly in your web browser from sublime text 2/3.
- [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing): Powerful Markdown package for Sublime Text with better syntax understanding and good color schemes.
- [Open Finder](https://github.com/kallepersson/Sublime-Finder/): (OSX only) Provides a command for opening Finder in the current directory.
- [Package Control](https://packagecontrol.io): The de facto package manager for Sublime Text. You already used it to install these plugins.
- [Pretty JSON](https://github.com/dzhibas/SublimePrettyJson): plugin for [ST3] to pretty [and minify] json
- [PxToEm](https://github.com/ningbit/sublime_pxtoem): plugin to convert px to em with comments. Shortcut was changed to `ctrl+shift+e` to avoid linter conflicts.
- [ReactJS](https://github.com/reactjs/sublime-react): Sublime Text helpers for React/JSX
- [SCSS](https://github.com/MarioRicalde/SCSS.tmbundle): The TextMate SCSS Official Bundle. Now Compatible with SublimeText2/3.
- [Select Quoted](https://github.com/int3h/SublimeSelectQuoted): A Sublime Text 2/3 plugin at add a "Expand Selection to Quoted" command
- [SublimeLinter](http://sublimelinter.com/): Interactive (real time feedback) code linting framework for Sublime Text 3. This is just the base framework, additional packages for related languages need to be installed.
- [SublimeLinter-contrib-scss-lint](https://github.com/attenzione/SublimeLinter-scss-lint): SublimeLinter plugin for Sass scss syntax, using the Ruby gem backend `scss-lint`
- [SublimeLinter-csslint](https://github.com/SublimeLinter/SublimeLinter-csslint): SublimeLinter plugin for CSS, using NodeJS package `csslint`.
- [SublimeLinter-jscs](https://github.com/mdevils/node-jscs/): SublimeLinter 3 plugin for NodeJS package `jscs`, a code style checking tool.
- [SublimeLinter-jshint](https://github.com/SublimeLinter/SublimeLinter-jshint): SublimeLinter plugin for JavaScript, using NodeJS package `jshint`.
- [SublimeLinter-json](https://github.com/SublimeLinter/SublimeLinter-json): SublimeLinter plugin for JSON. 
- [SublimeLinter-jsxhint](https://github.com/SublimeLinter/SublimeLinter-jsxhint): SublimeLinter 3 plugin for JSX (React.js), using the NodeJS package `jsxhint`. 
- [Terminal](http://wbond.net/sublime_packages/terminal): Launch terminals from the current file or the root project folder.

_Note: key bindings for the plugins to be added_

##### `Preferences.sublime-settings`

Here's an extract of the system preference with explanation comments:
```js
{
    //this must be set in user settings to be enabled in MAC OSX
    "scroll_past_end": true,
    // The delay, in ms, before the auto complete window is shown after typing
    // Note: Delaying this to have the completion files more likely
    // to be included in the auto complete list
    "auto_complete_delay": 200,
    // For best practices, will be overriden by EditorConfig
    "trim_trailing_white_space_on_save": true,
    // Esier to spot edited tabs
    "highlight_modified_tabs": true,
    // default tabsize is 2
    "tab_size": 2,
    // convert tabs into spaces
    "translate_tabs_to_spaces": true
}
```
Some of the entries were commented out in the real file to keep the preferences more agnostic. It's up to you to turn them on or use different settings.

Thanks to
---------

- [Paul Irish](https://github.com/paulirish) and his [dotfiles repository](https://github.com/paulirish/dotfiles) from which the OSX section is based on.
- [Thanh Tran](https://github.com/trongthanh) and his [dotfiles repository](https://github.com/trongthanh/dotfiles) from which this repo is forked and standardized further.

-------------------------------------------------------------------------------

© 2015 Cà phê shift