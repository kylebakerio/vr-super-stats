## aframe-stats-in-vr-component

stats-in-vr component for [A-Frame](https://aframe.io).

The stats-in-vr component allows the A-Frame scene stats component to be visible in VR.

## Example

```html
<a-scene stats-in-vr></a-scene>
```

## Value

| Property             | Description                                        | Default Value        |
|----------------------|----------------------------------------------------|----------------------|

## Events

| Event Name   | Description             |
| ----------   | -----------             |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.4.0/aframe.min.js"></script>
  <script src="https://rawgit.com/chenzlabs/stats-in-vr/master/dist/aframe-stats-in-vr-component.min.js"></script>
</head>

<body>
  <a-scene stats-in-vr></a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-stats-in-vr-component
```

Then register and use.

```js
require('aframe');
require('aframe-stats-in-vr-component');
```
