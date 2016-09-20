Quick React starter app

![React](public/react.png)

##Dependency list

```bash
npm i -S react react-dom

```
make sure you have `webpack` installed locally or globally

then for our Dev Dependencies
sometimes better known as npm i --save-dev
```bash
npm i -D   babel-core babel-loader babel-preset-es2015 babel-preset-react
```

Starting it
```bash
webpack -w
```
open another tab:
```bash
open public/index.html
```
browser should be showing - Hello World

then when you want to start messing with routes
you'll need these two
```bash
npm i -D react-router history
```


For now our basic component consist of
```js
var React = require('react')
var ReactDom = require('react-dom')

var Main = React.createClass({
  render: function() {
    return (
      <div>
        Hello World
      </div>
    )
  }
})

ReactDom.render(<Main />,
document.getElementById('nom'))

```
