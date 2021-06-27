<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Node Streams

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Standard library Node.js streams.

<section class="installation">

## Installation

```bash
npm install @stdlib/streams-node
```

</section>

<section class="usage">

## Usage

```javascript
var streams = require( '@stdlib/streams-node' );
```

#### streams

Standard library Node.js streams.

```javascript
var s = streams;
// returns {...}
```

The package contains the following streams:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`debugStream( [options,] [clbk] )`][@stdlib/streams/node/debug]</span><span class="delimiter">: </span><span class="description">transform stream for debugging stream pipelines.</span>
-   <span class="signature">[`inspectStream( [options,] clbk )`][@stdlib/streams/node/inspect]</span><span class="delimiter">: </span><span class="description">transform stream for inspecting streamed data.</span>
-   <span class="signature">[`joinStream( [options] )`][@stdlib/streams/node/join]</span><span class="delimiter">: </span><span class="description">transform stream which joins streamed data.</span>
-   <span class="signature">[`splitStream( [options] )`][@stdlib/streams/node/split]</span><span class="delimiter">: </span><span class="description">transform stream which splits streamed data.</span>
-   <span class="signature">[`transformStream( [options] )`][@stdlib/streams/node/transform]</span><span class="delimiter">: </span><span class="description">transform stream.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var getKeys = require( '@stdlib/utils-keys' );
var streams = require( '@stdlib/streams-node' );

console.log( getKeys( streams ) );
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/streams-node.svg
[npm-url]: https://npmjs.org/package/@stdlib/streams-node

[test-image]: https://github.com/stdlib-js/streams-node/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/streams-node/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/streams-node/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/streams-node?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/streams-node.svg
[dependencies-url]: https://david-dm.org/stdlib-js/streams-node/main

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/streams-node/main/LICENSE

<!-- <toc-links> -->

[@stdlib/streams/node/debug]: https://github.com/stdlib-js/streams-utils-debug

[@stdlib/streams/node/inspect]: https://github.com/stdlib-js/streams-utils-inspect

[@stdlib/streams/node/join]: https://github.com/stdlib-js/streams-utils-join

[@stdlib/streams/node/split]: https://github.com/stdlib-js/streams-utils-split

[@stdlib/streams/node/transform]: https://github.com/stdlib-js/streams-utils-transform

<!-- </toc-links> -->

</section>

<!-- /.links -->
