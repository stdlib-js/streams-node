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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Node Streams

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Node.js streams.



<section class="usage">

## Usage

To use in Observable,

```javascript
streams = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/streams-node@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var streams = require( 'path/to/vendor/umd/streams-node/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/streams-node@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.streams;
})();
</script>
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

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/streams-node@umd/browser.js"></script>
<script type="text/javascript">
(function () {

console.log( getKeys( streams ) );

})();
</script>
</body>
</html>
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

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2026. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/streams-node.svg
[npm-url]: https://npmjs.org/package/@stdlib/streams-node

[test-image]: https://github.com/stdlib-js/streams-node/actions/workflows/test.yml/badge.svg?branch=v0.2.3
[test-url]: https://github.com/stdlib-js/streams-node/actions/workflows/test.yml?query=branch:v0.2.3

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/streams-node/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/streams-node?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/streams-node.svg
[dependencies-url]: https://david-dm.org/stdlib-js/streams-node/main

-->

[chat-image]: https://img.shields.io/badge/zulip-join_chat-brightgreen.svg
[chat-url]: https://stdlib.zulipchat.com

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/streams-node/tree/deno
[deno-readme]: https://github.com/stdlib-js/streams-node/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/streams-node/tree/umd
[umd-readme]: https://github.com/stdlib-js/streams-node/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/streams-node/tree/esm
[esm-readme]: https://github.com/stdlib-js/streams-node/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/streams-node/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/streams-node/main/LICENSE

<!-- <toc-links> -->

[@stdlib/streams/node/debug-sink]: https://github.com/stdlib-js/streams-node-debug-sink/tree/umd

[@stdlib/streams/node/debug]: https://github.com/stdlib-js/streams-node-debug/tree/umd

[@stdlib/streams/node/empty]: https://github.com/stdlib-js/streams-node-empty/tree/umd

[@stdlib/streams/node/from-array]: https://github.com/stdlib-js/streams-node-from-array/tree/umd

[@stdlib/streams/node/from-circular-array]: https://github.com/stdlib-js/streams-node-from-circular-array/tree/umd

[@stdlib/streams/node/from-constant]: https://github.com/stdlib-js/streams-node-from-constant/tree/umd

[@stdlib/streams/node/from-iterator]: https://github.com/stdlib-js/streams-node-from-iterator/tree/umd

[@stdlib/streams/node/from-strided-array]: https://github.com/stdlib-js/streams-node-from-strided-array/tree/umd

[@stdlib/streams/node/inspect-sink]: https://github.com/stdlib-js/streams-node-inspect-sink/tree/umd

[@stdlib/streams/node/inspect]: https://github.com/stdlib-js/streams-node-inspect/tree/umd

[@stdlib/streams/node/join]: https://github.com/stdlib-js/streams-node-join/tree/umd

[@stdlib/streams/node/split]: https://github.com/stdlib-js/streams-node-split/tree/umd

[@stdlib/streams/node/stderr]: https://github.com/stdlib-js/streams-node-stderr/tree/umd

[@stdlib/streams/node/stdin]: https://github.com/stdlib-js/streams-node-stdin/tree/umd

[@stdlib/streams/node/stdout]: https://github.com/stdlib-js/streams-node-stdout/tree/umd

[@stdlib/streams/node/transform]: https://github.com/stdlib-js/streams-node-transform/tree/umd

<!-- </toc-links> -->

</section>

<!-- /.links -->
