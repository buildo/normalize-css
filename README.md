# normalize-css
CSS normalizer based on [normalize.css](https://github.com/necolas/normalize.css/) with a few custom normalization used at [buildo](http://buildo.io)

## Install
`npm i --save buildo-normalize-css`

## Usage
In you webpack entry file:

```js
import 'buildo-normalize-css';
```

#### Fullscreen app
If you want to create a fullscreen app you need to import the fullscreen module too:

```js
import 'buildo-normalize-css';
import 'buildo-normalize-css/fullscreenApp.css';
```
