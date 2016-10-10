# Vim React Snippets

A Vim snippet library for React in ES6.

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

[vim-react-snippets](http://i.imgur.com/ImgaW2k.gifv)

## Installation

Using vim-plug:

```vim
" React code snippets
Plug 'epilande/vim-react-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'
```

## Snippets

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rcc→`   | legacy component skeleton |
| `cdm→`   | `componentDidMount() {…}` |
| `cdup→`  | `componentDidUpdate(prevProps, prevState) {…}` |
| `cwm→`   | `componentWillMount() {…}` |
| `cwr→`   | `componentWillReceiveProps(nextProps) {…}` |
| `cwun→`  | `componentWillUnmount() {…}` |
| `cwup→`  | `componentWillUpdate(nextProps, nextState) {…}` |
| `fdn→`   | `React.findDOMNode(…)` |
| `gdp→`   | `getDefaultProps() {…}` |
| `gis→`   | `getInitialState() {…}` |
| `ren→`   | `render() {…}` |
| `sst→`   | `this.setState(…)` |
| `scu→`   | `shouldComponentUpdate(nextProps, nextState) {…}` |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `pt→`    | `propTypes { ... }` |
| `pta→`   | `PropTypes.arrayOf` |
| `ptai→`  | `PropTypes.arrayOf (Instances)` |
| `ptb→`   | `PropTypes.bool` |
| `pte→`   | `PropTypes.element` |
| `ptf→`   | `PropTypes.func` |
| `pti→`   | `PropTypes.instanceOf` |
| `ptn→`   | `PropTypes.number` |
| `ptn→`   | `PropTypes.node` |
| `pto→`   | `PropTypes.object` |
| `ptof→`  | `PropTypes.oneOf (Enum)` |
| `ptof→`  | `PropTypes.objectOf` |
| `ptoft→` | `PropTypes.oneOfType (Union)` |
| `pts→`   | `PropTypes.string` |
| `ptsp→`  | `PropTypes.shape` |

