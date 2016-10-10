# Vim React Snippets

A Vim snippet library for React in ES6.

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

![vim-react-snippets](http://i.imgur.com/ImgaW2k.gif)

## Installation

Using vim-plug:

```vim
" React code snippets
Plug 'epilande/vim-react-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'
```

## Snippets

#### Skeleton

| Trigger  | Content |
| -------: | ------- |
| `rrcc→`  | React Redux Class Component |
| `rcc→`   | React Class Component |
| `rfc→`   | React Functional Component |


#### Lifecycle

| Trigger  | Content |
| -------: | ------- |
| `cwm→`   | `componentWillMount() {...}` |
| `cdm→`   | `componentDidMount() {...}` |
| `cwrp→`  | `componentWillReceiveProps(nextProps) {...}` |
| `scup→`  | `shouldComponentUpdate(nextProps, nextState) {...}` |
| `cwup→`  | `componentWillUpdate(nextProps, nextState) {...}` |
| `cdup→`  | `componentDidUpdate(prevProps, prevState) {...}` |
| `cwu→`   | `componentWillUnmount() {...}` |
| `ren→`   | `render() {...}` |


#### PropTypes

| Trigger    | Content |
| -------:   | ------- |
| `pt→`      | `propTypes {...}` |
| `pt.a→`    | `PropTypes.array` |
| `pt.b→`    | `PropTypes.bool` |
| `pt.f→`    | `PropTypes.func` |
| `pt.n→`    | `PropTypes.number` |
| `pt.o→`    | `PropTypes.object` |
| `pt.s→`    | `PropTypes.string` |
| `pt.no→`   | `PropTypes.node` |
| `pt.e→`    | `PropTypes.element` |
| `pt.io→`   | `PropTypes.instanceOf` |
| `pt.one→`  | `PropTypes.oneOf` |
| `pt.onet→` | `PropTypes.oneOfType (Union)` |
| `pt.ao→`   | `PropTypes.arrayOf (Instances)` |
| `pt.oo→`   | `PropTypes.objectOf` |
| `pt.sh→`   | `PropTypes.shape` |
| `ir→`      | `isRequired` |

#### Others

| Trigger  | Content |
| -------: | ------- |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `set→`   | `this.setState(...)` |
| `dp→`    | `defaultProps {...}` |
| `cn→`    | `className` |
| `ref→`   | `ref` |
