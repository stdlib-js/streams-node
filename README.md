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

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Node.js streams.



<section class="usage">

## Usage

```javascript
import streams from 'https://cdn.jsdelivr.net/gh/stdlib-js/streams-node@deno/mod.js';
```

You can also import the following named exports from the package:

```javascript
import { arrayStream, circularArrayStream, constantStream, debugSinkStream, debugStream, emptyStream, inspectSinkStream, inspectStream, iteratorStream, joinStream, splitStream, stderr, stdin, stdout, stridedArrayStream, transformStream } from 'https://cdn.jsdelivr.net/gh/stdlib-js/streams-node@deno/mod.js';
```

#### streams

Namespace containing Node.js stream functionality.

```javascript
var s = streams;
// returns {...}
```

The package contains the following streams:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`debugSinkStream( [options,] [clbk] )`][@stdlib/streams/node/debug-sink]</span><span class="delimiter">: </span><span class="description">writable stream for debugging stream pipelines.</span>
-   <span class="signature">[`debugStream( [options,] [clbk] )`][@stdlib/streams/node/debug]</span><span class="delimiter">: </span><span class="description">transform stream for debugging stream pipelines.</span>
-   <span class="signature">[`emptyStream( [options] )`][@stdlib/streams/node/empty]</span><span class="delimiter">: </span><span class="description">create an "empty" readable stream.</span>
-   <span class="signature">[`arrayStream( src[, options] )`][@stdlib/streams/node/from-array]</span><span class="delimiter">: </span><span class="description">create a readable stream from an array-like object.</span>
-   <span class="signature">[`circularArrayStream( src[, options] )`][@stdlib/streams/node/from-circular-array]</span><span class="delimiter">: </span><span class="description">create a readable stream from a circular array-like object.</span>
-   <span class="signature">[`constantStream( value[, options] )`][@stdlib/streams/node/from-constant]</span><span class="delimiter">: </span><span class="description">create a readable stream which always streams the same value.</span>
-   <span class="signature">[`iteratorStream( iterator[, options] )`][@stdlib/streams/node/from-iterator]</span><span class="delimiter">: </span><span class="description">create a readable stream from an iterator.</span>
-   <span class="signature">[`stridedArrayStream( N, buffer, stride, offset[, options] )`][@stdlib/streams/node/from-strided-array]</span><span class="delimiter">: </span><span class="description">create a readable stream from a strided array-like object.</span>
-   <span class="signature">[`inspectSinkStream( [options,] clbk )`][@stdlib/streams/node/inspect-sink]</span><span class="delimiter">: </span><span class="description">writable stream for inspecting streamed data.</span>
-   <span class="signature">[`inspectStream( [options,] clbk )`][@stdlib/streams/node/inspect]</span><span class="delimiter">: </span><span class="description">transform stream for inspecting streamed data.</span>
-   <span class="signature">[`joinStream( [options] )`][@stdlib/streams/node/join]</span><span class="delimiter">: </span><span class="description">transform stream which joins streamed data.</span>
-   <span class="signature">[`splitStream( [options] )`][@stdlib/streams/node/split]</span><span class="delimiter">: </span><span class="description">transform stream which splits streamed data.</span>
-   <span class="signature">[`stderr`][@stdlib/streams/node/stderr]</span><span class="delimiter">: </span><span class="description">standard error.</span>
-   <span class="signature">[`stdin`][@stdlib/streams/node/stdin]</span><span class="delimiter">: </span><span class="description">standard input.</span>
-   <span class="signature">[`stdout`][@stdlib/streams/node/stdout]</span><span class="delimiter">: </span><span class="description">standard output.</span>
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
import getKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@deno/mod.js';
import streams from 'https://cdn.jsdelivr.net/gh/stdlib-js/streams-node@deno/mod.js';

console.log( getKeys( streams ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/streams-node.svg
[npm-url]: https://npmjs.org/package/@stdlib/streams-node

[test-image]: https://github.com/stdlib-js/streams-node/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/streams-node/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/streams-node/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/streams-node?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/streams-node.svg
[dependencies-url]: https://david-dm.org/stdlib-js/streams-node/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/streams-node/tree/deno
[umd-url]: https://github.com/stdlib-js/streams-node/tree/umd
[esm-url]: https://github.com/stdlib-js/streams-node/tree/esm
[branches-url]: https://github.com/stdlib-js/streams-node/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/streams-node/main/LICENSE

<!-- <toc-links> -->

[@stdlib/streams/node/debug-sink]: https://github.com/stdlib-js/streams-node-debug-sink/tree/deno

[@stdlib/streams/node/debug]: https://github.com/stdlib-js/streams-node-debug/tree/deno

[@stdlib/streams/node/empty]: https://github.com/stdlib-js/streams-node-empty/tree/deno

[@stdlib/streams/node/from-array]: https://github.com/stdlib-js/streams-node-from-array/tree/deno

[@stdlib/streams/node/from-circular-array]: https://github.com/stdlib-js/streams-node-from-circular-array/tree/deno

[@stdlib/streams/node/from-constant]: https://github.com/stdlib-js/streams-node-from-constant/tree/deno

[@stdlib/streams/node/from-iterator]: https://github.com/stdlib-js/streams-node-from-iterator/tree/deno

[@stdlib/streams/node/from-strided-array]: https://github.com/stdlib-js/streams-node-from-strided-array/tree/deno

[@stdlib/streams/node/inspect-sink]: https://github.com/stdlib-js/streams-node-inspect-sink/tree/deno

[@stdlib/streams/node/inspect]: https://github.com/stdlib-js/streams-node-inspect/tree/deno

[@stdlib/streams/node/join]: https://github.com/stdlib-js/streams-node-join/tree/deno

[@stdlib/streams/node/split]: https://github.com/stdlib-js/streams-node-split/tree/deno

[@stdlib/streams/node/stderr]: https://github.com/stdlib-js/streams-node-stderr/tree/deno

[@stdlib/streams/node/stdin]: https://github.com/stdlib-js/streams-node-stdin/tree/deno

[@stdlib/streams/node/stdout]: https://github.com/stdlib-js/streams-node-stdout/tree/deno

[@stdlib/streams/node/transform]: https://github.com/stdlib-js/streams-node-transform/tree/deno

<!-- </toc-links> -->

</section>

<!-- /.links -->
