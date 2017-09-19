# \<kwc-modal\>

Wraps content into a modal/dialog overlay

## Installation
Clone this repository.
Run `bower i`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test --skip-plugin junit-reporter
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## TODO
- Rewrite `transitionImage` so mocha can test it. Right now it won't trigger `animationend` event.
- Implement fallback if `animate` is not in `HTMLElement`
