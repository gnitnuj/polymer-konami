# \<polymer-konami\>

a polymer element that fires an event once a user types in the konami code. the event can be listened to in order to fire custom callbacks. custom key combinations can also be passed to the element to be used instead of the konami code default.

## Installation & Usage

Install polymer-konami with Bower

```sh
$ bower i polymer-konami --save
```

Import it into the `<head>` of your page

```html
<link rel="import" href="/bower_components/polymer-konami/polymer-konami.html">
```

Then use polymer-konami in your project

```html
<polymer-konami></polymer-konami>
```

## Development

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

### Viewing Your Element

```
$ polymer serve
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
