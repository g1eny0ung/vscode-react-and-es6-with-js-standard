# react-and-es6-with-js-standard

![Version](https://vsmarketplacebadge.apphb.com/version/g1eny0ung.react-and-es6-with-js-standard.svg)
![Installs](https://vsmarketplacebadge.apphb.com/installs/g1eny0ung.react-and-es6-with-js-standard.svg)
![Rating](https://vsmarketplacebadge.apphb.com/rating/g1eny0ung.react-and-es6-with-js-standard.svg)

This extension combines these extensions' features in one with [JS Standard](https://standardjs.com/):

- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)

At the same time, some of useless and ambiguous snippets have been removed.

## Supported languages

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

## Snippets

### Import and export

| Trigger | Content                                                                                               |
| ------: | ----------------------------------------------------------------------------------------------------- |
|  `imp→` | imports entire module `import fs from 'fs'`                                                           |
|  `imn→` | imports entire module without module name `import 'animate.css'`                                      |
|  `imd→` | imports only a portion of the module using destructing `import {rename} from 'fs'`                    |
|  `ime→` | imports everything as alias from the module `import * as localAlias from 'fs'`                        |
|  `ima→` | imports only a portion of the module as alias `import { rename as localRename } from 'fs'`            |
|  `rqr→` | require package `require('')`                                                                         |
|  `req→` | require package to const `const packageName = require('packageName')`                                 |
|  `mde→` | default module.exports `module.exports = {}`                                                          |
|  `env→` | exports name variable `export const nameVariable = localVariable`                                     |
|  `enf→` | exports name function `export const log = (parameter) => { console.log(parameter)}`                   |
|  `edf→` | exports default function `export default function fileName (parameter){ console.log(parameter)}`      |
|  `ecl→` | exports default class `export default class Calculator { }`                                           |
|  `ece→` | exports default class by extending a base one `export default class Calculator extends BaseClass { }` |

### Class helpers

| Trigger | Content                                                         |
| ------: | --------------------------------------------------------------- |
|  `cla→` | Create a basic class `class A {}`                               |
| `clae→` | Create a basic class with extends `class A extends B {}`        |
|  `con→` | adds default constructor in the class `constructor() {}`        |
|  `met→` | creates a method inside a class `add() {}`                      |
|  `pge→` | creates a getter property `get propertyName() { return value }` |
|  `pse→` | creates a setter property `set propertyName(value) {}`          |

### Various methods

|  Trigger | Content                                                                              |
| -------: | ------------------------------------------------------------------------------------ |
|   `fre→` | forEach loop in ES6 syntax `array.forEach(currentItem => {})`                        |
|   `fof→` | for ... of loop `for(const item of object) {}`                                       |
|   `fin→` | for ... in loop `for(const item in object) {}`                                       |
|  `anfn→` | creates an anonymous function `(params) => {}`                                       |
|   `nfn→` | creates a named function `const add = (params) => {}`                                |
|   `dob→` | destructing object syntax `const {rename} = fs`                                      |
|   `dar→` | destructing array syntax `const [first, second] = [1,2]`                             |
|   `sti→` | set interval helper method `setInterval(() => {})`                                   |
|   `sto→` | set timeout helper method `setTimeout(() => {})`                                     |
|  `prom→` | creates a new Promise `return new Promise((resolve, reject) => {})`                  |
| `thenc→` | adds then and catch declaration to a promise `.then((res) => {}).catch((err) => {})` |

### Console methods

| Trigger | Content                             |
| ------: | ----------------------------------- |
|  `cas→` | console assert `console.assert`     |
|  `ccl→` | console clear `console.clear`       |
|  `cde→` | console debug `console.debug`       |
|  `cer→` | console error `console.error`       |
|  `cgr→` | console group `console.group`       |
|  `cge→` | console groupEnd `console.groupEnd` |
|  `cin→` | console info `console.info`         |
|  `clg→` | console log `console.log`           |
|  `cwa→` | console warn `console.warn`         |

### React

|  Trigger | Content                                            |
| -------: | -------------------------------------------------- |
|   `rcc→` | class component skeleton                           |
|  `rccp→` | class component skeleton with propTypes            |
|   `rfc→` | functional class component skeleton                |
|  `rfcp→` | functional class component skeleton with propTypes |
|   `con→` | class default constructor with props               |
|   `est→` | empty state object                                 |
|   `cwm→` | `componentWillMount method`                        |
|  `ucwm→` | `UNSAFE_componentWillMount method`                 |
|   `cdm→` | `componentDidMount method`                         |
|   `cwr→` | `componentWillReceiveProps method`                 |
|  `ucwr→` | `UNSAFE_componentWillReceiveProps method`          |
|   `scu→` | `shouldComponentUpdate method`                     |
|  `cwup→` | `componentWillUpdate method`                       |
| `ucwup→` | `UNSAFE_componentWillUpdate method`                |
|  `cdup→` | `componentDidUpdate method`                        |
|  `cwun→` | `componentWillUnmount method`                      |
|  `gsbu→` | `getSnapshotBeforeUpdate method`                   |
| `gdsfp→` | `static getDerivedStateFromProps method`           |
|   `ust→` | `useState hook`                                    |
|   `uef→` | `useEffect hook`                                   |
|   `uco→` | `useContext hook`                                  |
|   `ure→` | `useReducer hook`                                  |
|   `uca→` | `useCallback hook`                                 |
|   `ume→` | `useMemo hook`                                     |
|  `uref→` | `useRef hook`                                      |
|   `sst→` | `this.setState with object as parameter`           |
|   `ssf→` | `this.setState with function as parameter`         |
|   `rpt→` | empty propTypes declaration                        |
|   `rdp→` | empty defaultProps declaration                     |

### React type checking

|   Trigger | Content                                                                              |
| --------: | ------------------------------------------------------------------------------------ |
|    `pta→` | `PropTypes.array,`                                                                   |
|   `ptar→` | `PropTypes.array.isRequired,`                                                        |
|    `ptb→` | `PropTypes.bool,`                                                                    |
|   `ptbr→` | `PropTypes.bool.isRequired,`                                                         |
|    `ptf→` | `PropTypes.func,`                                                                    |
|   `ptfr→` | `PropTypes.func.isRequired,`                                                         |
|    `ptn→` | `PropTypes.number,`                                                                  |
|   `ptnr→` | `PropTypes.number.isRequired,`                                                       |
|    `pto→` | `PropTypes.object,`                                                                  |
|   `ptor→` | `PropTypes.object.isRequired,`                                                       |
|    `pts→` | `PropTypes.string,`                                                                  |
|   `ptsr→` | `PropTypes.string.isRequired,`                                                       |
|   `ptsm→` | `PropTypes.symbol,`                                                                  |
|  `ptsmr→` | `PropTypes.symbol.isRequired,`                                                       |
|   `ptan→` | `PropTypes.any,`                                                                     |
|  `ptanr→` | `PropTypes.any.isRequired,`                                                          |
|   `ptnd→` | `PropTypes.node,`                                                                    |
|  `ptndr→` | `PropTypes.node.isRequired,`                                                         |
|   `ptel→` | `PropTypes.element,`                                                                 |
|  `ptelr→` | `PropTypes.element.isRequired,`                                                      |
|    `pti→` | `PropTypes.instanceOf(ClassName),`                                                   |
|   `ptir→` | `PropTypes.instanceOf(ClassName).isRequired,`                                        |
|    `pte→` | `PropTypes.oneOf(['News', 'Photos']),`                                               |
|   `pter→` | `PropTypes.oneOf(['News', 'Photos']).isRequired,`                                    |
|   `ptet→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),`                         |
|  `ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,`              |
|   `ptao→` | `PropTypes.arrayOf(PropTypes.number),`                                               |
|  `ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,`                                    |
|   `ptoo→` | `PropTypes.objectOf(PropTypes.number),`                                              |
|  `ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,`                                   |
|  `ptoos→` | `PropTypes.objectOf(PropTypes.shape()),`                                             |
| `ptoosr→` | `PropTypes.objectOf(PropTypes.shape()).isRequired,`                                  |
|   `ptsh→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),`            |
|  `ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |

## License

MIT © [g1eny0ung](https://github.com/g1eny0ung)

Most of code by [Charalampos Karypidis](https://github.com/xabikos) with MIT license.
