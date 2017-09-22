# \<kwc-modal\>

Wraps content into a modal/dialog overlay

## Properties
 * assetsPath: Path to assets to be used by the modal.
 * closable: Flags if modal shows an UI for closing it.
 * motif: Path for the image placed on the top end of modal.
 * opened: Flags if modal is open.
 * wasAnimated: Flags if modal has been animated during previous transitions.

 If `assetsPath` is given the modal will look for a close modal icon at `${assetsPath}/icons/close-modal-icon.svg` so you need to provide that file.

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
