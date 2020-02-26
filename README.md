# prompt.js

prompt.js is a drop-in replacement for the JavaScript’s prompt.

## Installation

Add [`prompt.js`](scripts/prompt.js) to your project.

## Usage

``` javascript
const prompt = new Prompt
const value = await prompt.fire('Ping')
console.log(value)
```

## Methods

See the [source](scripts/prompt.js) for a complete reference.

###### `fire(message)`

Fires the prompt.
Returns a [`Promise`] that resolves to the text entered by the user, or `null`.

[`Promise`]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

## Events

###### `open()`

Fired when the prompt is opened.

###### `close()`

Fired when the prompt is closed.
