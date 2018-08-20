# event-target-polyfill

EventTarget polyfill for IE11 and Edge from https://developer.mozilla.org/en-US/docs/Web/API/EventTarget#Example

## Why?

Because Microsoft has been shitting the bed since forever.

## What's it do?

The __exact__ same thing that as `window.EventTarget`

## Installation

`@mattkrick/event-target-polyfill`

```js
import EventTargetPolyfill from '@mattkrick/event-target-polyfill'

window.EventTarget = EventTargetPolyfill
const foo = new EventTarget('open')
```


