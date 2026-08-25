# Awesome Babel with stars

[<img src="https://babeljs.io/images/logo.svg" width="160" align="right" alt="babel">](http://babeljs.io)

> A list of awesome Babel plugins, presets, etc. Many of these are from the community, but some are lesser-known
> plugins in the Babel organization that may be useful to you.

> As always, use caution when trying out Babel plugins, especially those marked as 🔧 *experimental* or 🔧🚧 *under construction*.

If you want to contribute, please read the [contribution guidelines](contributing.md).

## Parsers

* [babel-eslint](https://github.com/babel/babel-eslint) ⚠️ Archived - ESLint using Babel as the parser.
  * Note: ESLint now lints most ES6+ syntax. This parser is only necessary if you are using Flow types or other experimental features.

## Plugins

### General Plugins

* [idx](https://github.com/facebookincubator/idx) ⚠️ Archived - library + babel plugin for a existential function.
* [fast-async](https://github.com/MatAtBread/fast-async) ⭐ 600 | 🐛 6 | 🌐 JavaScript | 📅 2018-10-08 - Uses nodent to compile async/await to fast Promise output.
* [transform-builtin-extend](https://github.com/loganfsmyth/babel-plugin-transform-builtin-extend) ⭐ 148 | 🐛 13 | 🌐 JavaScript | 📅 2022-01-18 - Enable extending builtin types like `Error` and `Array`, which require special treatment and require static analysis to detect.
* [feature-flags](https://github.com/ember-cli/babel-plugin-feature-flags) ⭐ 56 | 🐛 6 | 🌐 JavaScript | 📅 2021-07-28 - Helper for managing application feature flags.
* [console-source](https://github.com/peteringram0/babel-plugin-console-source) ⭐ 38 | 🐛 2 | 🌐 JavaScript | 📅 2020-10-31 - Prepends the file name and line numbers for all console commands
* [version](https://github.com/hustcc/babel-plugin-version) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2019-01-19 - Babel plugin replace defined identifier `__VERSION__` to pkg.version.
* [external-helpers](https://www.npmjs.com/package/babel-plugin-external-helpers) - Moves helper functions to a single imported module.
* [babel-plugin-debug-tools](https://www.npmjs.com/package/babel-plugin-debug-tools) Babeljs Debug Tools helps you insert debug code and easely remove it when deploy to production

### Module Resolution

* [module-resolver](https://github.com/tleunen/babel-plugin-module-resolver) ⭐ 3,476 | 🐛 109 | 🌐 JavaScript | 📅 2026-03-16 - Custom module resolver.
* [lodash](https://github.com/lodash/babel-plugin-lodash) ⚠️ Archived - Cherry-picks Lodash modules so you don’t have to.
* [root-import](https://github.com/entwicklerstube/babel-plugin-root-import) ⭐ 1,169 | 🐛 21 | 🌐 JavaScript | 📅 2022-12-03 - Import modules from the root with `require('~/foo')` syntax.
* [ramda](https://github.com/megawac/babel-plugin-ramda) ⭐ 312 | 🐛 16 | 🌐 JavaScript | 📅 2023-03-01 - Cherry-picks Ramda modules so you don’t have to.
* [webpack-alias](https://github.com/trayio/babel-plugin-webpack-alias) ⚠️ Archived - Allows you to use webpack aliases and most of webpack resolve features in Babel.
* [hash-resolve](https://github.com/miketamis/babel-plugin-hash-resolve) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2020-04-28 - Allows you to use `require('#/path')` instead of `require('../../path')`, the number of `../` needed is worked out by the plugin
* [rewrite-module-path](https://github.com/zheeeng/babel-plugin-rewrite-module-path) ⭐ 3 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-26 - Rewrite module resolving path.

### React

* [transform-react-jsx-self](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-react-jsx-self) ⭐ 43,989 | 🐛 783 | 🌐 TypeScript | 📅 2026-08-23 - Adds a `__self` property to JSX tags for debugging. Don't use in production. [More info](https://github.com/babel/babel/pull/3540) ⭐ 43,989 | 🐛 783 | 🌐 TypeScript | 📅 2026-08-23
* [React Optimize](https://github.com/thejameskyle/babel-react-optimize) ⭐ 1,666 | 🐛 20 | 🌐 JavaScript | 📅 2017-04-06 - A Babel preset and plugins for optimizing React code.
* [React Transform](https://github.com/gaearon/babel-plugin-react-transform) ⚠️ Archived - Instrument React components with custom transforms.
* [transform-react-remove-prop-types](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) ⭐ 889 | 🐛 17 | 🌐 JavaScript | 📅 2021-11-28 - Removes unnecessary React propTypes from the production build.
* [zacs](https://github.com/nozbe/zacs) ⭐ 430 | 🐛 1 | 🌐 JavaScript | 📅 2023-08-28 - "styled components"-ish syntax without performance overhead
* [babel-plugin-typescript-to-proptypes](https://github.com/milesj/babel-plugin-typescript-to-proptypes) ⭐ 364 | 🐛 12 | 🌐 TypeScript | 📅 2023-04-12 - Generate React PropTypes from TypeScript interfaces or type aliases.
* [react-docgen](https://github.com/kadirahq/babel-plugin-react-docgen) ⭐ 163 | 🐛 7 | 🌐 JavaScript | 📅 2024-11-26 - Makes propTypes comments accessible at runtime for use with documentation generators.
* [react-require](https://github.com/vslinko/babel-plugin-react-require) ⚠️ Archived - Adds React import declaration if file contains JSX tags.
* [babel-plugin-react-directive](https://github.com/evolify/babel-plugin-react-directive) ⭐ 30 | 🐛 1 | 🌐 TypeScript | 📅 2023-09-06 - Use directive in React, for example, you can use `r-if`、`r-for` in jsx just as `v-if`、`v-for` in Vue.
* [babel-plugin-transform-react-class-to-function](https://github.com/remcohaszing/babel-plugin-transform-react-class-to-function) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2021-11-06 - Transforms React class components into a function, if possible.
* [react-hyperscript](https://github.com/roman01la/babel-plugin-react-hyperscript) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-28 - HyperScript syntax for React components without runtime overhead.
* [react-hiccup](https://github.com/callwait/babel-plugin-react-hiccup) ⭐ 17 | 🐛 11 | 🌐 JavaScript | 📅 2023-03-04 - Hiccup syntax for React components.
* [babel-plugin-framer-x](https://github.com/eschaefer/babel-plugin-framer-x) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-08 - Removes Framer X markup from your components. Lets you use Framer X components in a Storybook or real application.
* [react-import-extends](https://github.com/vijaysutrave/babel-plugin-react-import-extends) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-01 - Extends `Component` if a class renders a JSX element, also adds `import` statement if it detects a JSX component in the file.
* [babel-plugin-hoist-facc](https://github.com/strayiker/babel-plugin-hoist-facc) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-06 - Transforms function as child components to hoist the children function to highest scope.
* [transform-react-constant-elements](https://www.npmjs.com/package/babel-plugin-transform-react-constant-elements) - Hoist elements that can be marked as constant to the highest scope for reuse.
* [transform-react-inline-elements](https://www.npmjs.com/package/babel-plugin-transform-react-inline-elements) - Replaces `React.createElement()` with a helper that is more optimized for production.

### Internationalization

* [react-intl](https://github.com/yahoo/react-intl) ⭐ 14,743 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-24 - Extracts string messages for translation from modules that use [React Intl](https://github.com/yahoo/react-intl) ⭐ 14,743 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-24.
* [localize](https://github.com/amerani/babel-plugin-localize) ⭐ 12 | 🐛 3 | 🌐 JavaScript | 📅 2018-07-21 - Modify static jsx text and string attributes with function call. 🔧
* [c-3po](https://c-3po.js.org) - Localization tool based on es6 template literals.

### Types

* [flow-runtime](https://github.com/codemix/flow-runtime/tree/master/packages/babel-plugin-flow-runtime) ⭐ 797 | 🐛 101 | 🌐 JavaScript | 📅 2022-12-10 - Turns Flow annotations into runtime checks. Part of [Flow-Runtime](https://codemix.github.io/flow-runtime).
* [tcomb](https://github.com/gcanti/babel-plugin-tcomb) ⚠️ Archived - Turns Flow annotations into typechecks with [tcomb](https://github.com/gcanti/tcomb) ⚠️ Archived.
* [runtyper](https://github.com/vitalets/babel-plugin-runtyper) ⭐ 116 | 🐛 13 | 🌐 JavaScript | 📅 2022-12-07 - Detects type-mismatch operations in runtime without annotations.
* [jsdoc-to-assert](https://github.com/azu/babel-plugin-jsdoc-to-assert) ⭐ 55 | 🐛 5 | 🌐 JavaScript | 📅 2019-11-06 - Turns JSDoc into runtime checks.

### Testing

* [rewire](https://github.com/speedskater/babel-plugin-rewire) ⭐ 837 | 🐛 58 | 🌐 JavaScript | 📅 2023-08-17 - Adds the ability to rewire module dependencies. This enables to mock modules for testing purposes.
* [istanbul](https://github.com/istanbuljs/babel-plugin-istanbul) ⭐ 657 | 🐛 69 | 🌐 JavaScript | 📅 2026-07-20 - Instruments your code with Istanbul coverage.
* [espower](https://github.com/power-assert-js/babel-plugin-espower) ⭐ 93 | 🐛 9 | 🌐 JavaScript | 📅 2023-01-03 - Annotates call sites for descriptive messages when using [power-assert](https://github.com/power-assert-js/power-assert) ⭐ 2,807 | 🐛 43 | 🌐 JavaScript | 📅 2023-01-07.

### Optimization

* [preval](https://github.com/kentcdodds/babel-plugin-preval) ⭐ 1,363 | 🐛 11 | 🌐 TypeScript | 📅 2022-02-02 - Pre-evaluate code at build-time.
* [faster.js](https://github.com/vzhou842/faster.js) ⭐ 437 | 🐛 6 | 🌐 JavaScript | 📅 2022-12-30 - Transforms native `Array` methods into faster equivalents. 🔧
* [closure-elimination](https://github.com/codemix/babel-plugin-closure-elimination) ⭐ 366 | 🐛 4 | 🌐 JavaScript | 📅 2022-12-11 - Transforms closures into separate functions.
* [object-to-json-parse](https://github.com/nd-02110114/babel-plugin-object-to-json-parse) ⚠️ Archived - Converts from object literal to `JSON.parse`.
* [loop-optimizer](https://github.com/vihanb/babel-plugin-loop-optimizer) ⭐ 74 | 🐛 9 | 🌐 JavaScript | 📅 2020-07-19 - Transforms `.forEach` and `.map` calls to for loops. 🔧
* [groundskeeper-willie](https://github.com/betaorbust/babel-plugin-groundskeeper-willie) ⭐ 62 | 🐛 6 | 🌐 TypeScript | 📅 2022-11-11 - Removes debugger and console calls.
* [transform-named-imports](https://github.com/SectorLabs/babel-plugin-transform-named-imports) ⭐ 37 | 🐛 16 | 🌐 JavaScript | 📅 2023-01-03 - Avoid including code that you don't need from modules you're importing.
* [cloudinary](https://github.com/trivago/babel-plugin-cloudinary) ⚠️ Archived - Compile cloudinary URLs at build time.
* [optimize-i18n](https://github.com/hustcc/babel-plugin-optimize-i18n) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-01 - Optimizing i18n bundle file by shorten the locale key.

### Syntax Sugar

* [trace](https://github.com/codemix/babel-plugin-trace) ⭐ 64 | 🐛 1 | 🌐 JavaScript | 📅 2018-05-30 - Syntax shortcuts for console logging.
* [function-composition](https://github.com/haskellcamargo/babel-plugin-function-composition) ⭐ 63 | 🐛 0 | 🌐 JavaScript | 📅 2018-08-10 - Function piping and composition via `&` operator, for example, `toUpper & console.log`.
* [meaningful-logs](https://github.com/furstenheim/babel-plugin-meaningful-logs) ⭐ 50 | 🐛 7 | 🌐 JavaScript | 📅 2023-01-03 - Adds file name and line number of caller to `console.log()` calls.
* [auto-await](https://github.com/ziolko/babel-plugin-auto-await) ⭐ 27 | 🐛 1 | 🌐 JavaScript | 📅 2019-02-25 - Automatically `await` every `Promise` in `async` functions.
* [implicit-return](https://github.com/miraks/babel-plugin-implicit-return) ⭐ 25 | 🐛 2 | 🌐 JavaScript | 📅 2019-02-08 - Transforms last statement in a function block to a return statement.
* [implicit-function](https://github.com/haskellcamargo/babel-plugin-implicit-function) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-04 - Implicit functions via `~` operator, transforming, for example, `~x` in `() => x`.
* [offside-js](https://github.com/shanewholloway/babel-plugin-offside-js) ⚠️ Archived - Coffeescript-like indented block syntax hack. 🔧🚧
* [transform-iota](https://github.com/passcod/babel-plugin-transform-iota) ⚠️ Archived - Golang-style `iota()`. 🔧

### Alternative Programming Paradigms

* [babel-macros](https://github.com/kentcdodds/babel-macros) ⭐ 2,633 | 🐛 12 | 🌐 JavaScript | 📅 2023-05-30 - Enables zero-config, importable babel plugins.
* [contracts](https://github.com/codemix/babel-plugin-contracts) ⭐ 269 | 🐛 3 | 🌐 JavaScript | 📅 2019-04-29 - Design by Contract; Includes preconditions, postconditions, and invariant conditions.
* [macros](https://github.com/codemix/babel-plugin-macros) ⭐ 261 | 🐛 0 | 🌐 JavaScript | 📅 2016-03-12 - Hygienic, non-syntactic macros. 🔧
* [partial-application](https://github.com/citycide/babel-plugin-partial-application) ⚠️ Archived - Scala/Kotlin-esque partial application syntax for JavaScript (using `_`). 🔧
* [transform-scala-lambda](https://github.com/xtuc/babel-plugin-transform-scala-lambda) ⭐ 54 | 🐛 1 | 🌐 JavaScript | 📅 2019-02-21 - Enable Scala-style lambdas (using `_`). 🔧
* [holes](https://github.com/rung-tools/babel-plugin-holes) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-03 - Holes (like Scala and Elixir) to help point-free programming, using operators as functions. 🔧
* [overload](https://github.com/foxbenjaminfox/babel-plugin-overload) ⭐ 46 | 🐛 2 | 🌐 JavaScript | 📅 2017-07-21 - Allow overloading default operators like `+` or `===` for specific classes. 🔧🚧

## Presets

* [env](https://github.com/babel/babel/tree/master/packages/babel-preset-env) ⭐ 43,989 | 🐛 783 | 🌐 TypeScript | 📅 2026-08-23 - **The recommended preset** which includes transforms based on the specified environment (browsers, node, electron, etc).
* [React Optimize](https://github.com/thejameskyle/babel-react-optimize) ⭐ 1,666 | 🐛 20 | 🌐 JavaScript | 📅 2017-04-06 - A Babel preset and plugins for optimizing React code.
* [React](https://www.npmjs.com/package/babel-preset-react) - Babel preset for all React plugins.

## Tooling

* [babel-watch](https://github.com/kmagiera/babel-watch) ⭐ 525 | 🐛 6 | 🌐 JavaScript | 📅 2023-07-12 - Reloads a node app on file changes.
* [babel-time-travel](https://github.com/boopathi/babel-time-travel) ⚠️ Archived - Time travel through babel transformations one by one.
* [react-ast](https://github.com/codejamninja/react-ast) ⭐ 338 | 🐛 5 | 🌐 TypeScript | 📅 2024-01-12 - Render babel ASTs with react

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
