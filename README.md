![ungrid logo](../gh-pages/favicon.png "ungrid logo")

# ungrid [![Financial Contributors on Open Collective](https://opencollective.com/ungrid/all/badge.svg?label=financial+contributors)](https://opencollective.com/ungrid) [![npm version](https://badge.fury.io/js/ungrid.svg)](http://badge.fury.io/js/ungrid) [![Bower version](https://badge.fury.io/bo/ungrid.svg)](http://badge.fury.io/bo/ungrid)

the simplest responsive css grid



## What's this?

__ungrid__ is a tiny, responsive, table-based CSS grid system. The entire `ungrid.css` file is 97 bytes minified.

```css
@media (min-width: 30em) {
    .row { width: 100%; display: table; table-layout: fixed; }
    .col { display: table-cell; }
}
```



## Get started

- Install with [npm](//www.npmjs.com/package/ungrid) `npm install ungrid`
- Install with [Bower](//bower.io) `bower install ungrid`
- Or just copy and paste the contents of ungrid.min.css into your CSS file.



## How to use

To use, simply put as many `.col`s as you wish in your `.row`s and the `.col`s will automatically be evenly spaced. This allows you to roll your own simple grids. [See it in action](//codepen.io/chrisnager/pen/ypokv?editors=1100).

```html
<div class="row">
    <div class="col">⚜</div>
    <div class="col">⚜</div>
    <div class="col">⚜</div>
    …
    <div class="col">⚜</div>
</div>
```

![ungrid grid system](../gh-pages/ungrid-screenshot.png "ungrid grid system")



## Helpful resources

- [Nested rows with ungrid](//codepen.io/chrisnager/pen/EeJqH) (addresses [issue #1](//github.com/chrisnager/ungrid/issues/1)).
- [Gutters with ungrid](//codepen.io/chrisnager/pen/arKBu) (addresses [issue #2](//github.com/chrisnager/ungrid/issues/2)).
- [Offset columns with ungrid](//codepen.io/chrisnager/pen/QbqxJO) (addresses [issue #6](//github.com/chrisnager/ungrid/issues/6)).
- [Use ungrid with React](//codepen.io/chrisnager/pen/oYRzPz) (addresses [issue #13](//github.com/chrisnager/ungrid/issues/13)).
- [Flexbox flavor (ungrid-flex.css)](//codepen.io/chrisnager/pen/BNejRQ) (addresses [pull request #4](//github.com/chrisnager/ungrid/pull/4)).



## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/chrisnager/ungrid/graphs/contributors"><img src="https://opencollective.com/ungrid/contributors.svg?width=890&button=false" /></a>

### Financial Contributors

Become a financial contributor and help us sustain our community. [[Contribute](https://opencollective.com/ungrid/contribute)]

#### Individuals

<a href="https://opencollective.com/ungrid"><img src="https://opencollective.com/ungrid/individuals.svg?width=890"></a>

#### Organizations

Support this project with your organization. Your logo will show up here with a link to your website. [[Contribute](https://opencollective.com/ungrid/contribute)]

<a href="https://opencollective.com/ungrid/organization/0/website"><img src="https://opencollective.com/ungrid/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/1/website"><img src="https://opencollective.com/ungrid/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/2/website"><img src="https://opencollective.com/ungrid/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/3/website"><img src="https://opencollective.com/ungrid/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/4/website"><img src="https://opencollective.com/ungrid/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/5/website"><img src="https://opencollective.com/ungrid/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/6/website"><img src="https://opencollective.com/ungrid/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/7/website"><img src="https://opencollective.com/ungrid/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/8/website"><img src="https://opencollective.com/ungrid/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/ungrid/organization/9/website"><img src="https://opencollective.com/ungrid/organization/9/avatar.svg"></a>

## License

The MIT License (MIT)

Copyright (c) 2014-2020 [Chris Nager](//twitter.com/chrisnager)

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
