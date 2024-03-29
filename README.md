<!--

@license Apache-2.0

Copyright (c) 2019 The Stdlib Authors.

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

# Simulation Iterators

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Simulation iterators.

<section class="installation">

## Installation

```bash
npm install @stdlib/simulate-iter
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@stdlib/simulate-iter' );
```

#### ns

Namespace containing simulation iterators.

```javascript
var iterators = ns;
// returns {...}
```

The namespace contains the following functions for creating iterator protocol-compliant iterators:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`iterawgn( iterator, sigma[, options] )`][@stdlib/simulate/iter/awgn]</span><span class="delimiter">: </span><span class="description">create an iterator which introduces additive white Gaussian noise (AWGN).</span>
-   <span class="signature">[`iterawln( iterator, sigma[, options] )`][@stdlib/simulate/iter/awln]</span><span class="delimiter">: </span><span class="description">create an iterator which introduces additive white Laplacian noise (AWLN).</span>
-   <span class="signature">[`iterawun( iterator, sigma[, options] )`][@stdlib/simulate/iter/awun]</span><span class="delimiter">: </span><span class="description">create an iterator which introduces additive white uniform noise (AWUN).</span>
-   <span class="signature">[`iterBartlettHannPulse( [options] )`][@stdlib/simulate/iter/bartlett-hann-pulse]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a Bartlett-Hann pulse waveform.</span>
-   <span class="signature">[`iterBartlettPulse( [options] )`][@stdlib/simulate/iter/bartlett-pulse]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a Bartlett pulse waveform.</span>
-   <span class="signature">[`iterCosineWave( [options] )`][@stdlib/simulate/iter/cosine-wave]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a cosine wave.</span>
-   <span class="signature">[`iterDiracComb( [options] )`][@stdlib/simulate/iter/dirac-comb]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a Dirac comb.</span>
-   <span class="signature">[`iterFlatTopPulse( [options] )`][@stdlib/simulate/iter/flat-top-pulse]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a flat top pulse waveform.</span>
-   <span class="signature">[`iterHannPulse( [options] )`][@stdlib/simulate/iter/hann-pulse]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a Hann pulse waveform.</span>
-   <span class="signature">[`iterLanczosPulse( [options] )`][@stdlib/simulate/iter/lanczos-pulse]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a Lanczos pulse waveform.</span>
-   <span class="signature">[`iterPeriodicSinc( n[, options] )`][@stdlib/simulate/iter/periodic-sinc]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a periodic sinc waveform.</span>
-   <span class="signature">[`iterPulse( [options] )`][@stdlib/simulate/iter/pulse]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a pulse waveform.</span>
-   <span class="signature">[`iterSawtoothWave( [options] )`][@stdlib/simulate/iter/sawtooth-wave]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a sawtooth wave.</span>
-   <span class="signature">[`iterSineWave( [options] )`][@stdlib/simulate/iter/sine-wave]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a sine wave.</span>
-   <span class="signature">[`iterSquareWave( [options] )`][@stdlib/simulate/iter/square-wave]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a square wave.</span>
-   <span class="signature">[`iterTriangleWave( [options] )`][@stdlib/simulate/iter/triangle-wave]</span><span class="delimiter">: </span><span class="description">create an iterator which generates a triangle wave.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var ns = require( '@stdlib/simulate-iter' );

console.log( objectKeys( ns ) );
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

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/simulate-iter.svg
[npm-url]: https://npmjs.org/package/@stdlib/simulate-iter

[test-image]: https://github.com/stdlib-js/simulate-iter/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/simulate-iter/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/simulate-iter/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/simulate-iter?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/simulate-iter.svg
[dependencies-url]: https://david-dm.org/stdlib-js/simulate-iter/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/simulate-iter/tree/deno
[deno-readme]: https://github.com/stdlib-js/simulate-iter/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/simulate-iter/tree/umd
[umd-readme]: https://github.com/stdlib-js/simulate-iter/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/simulate-iter/tree/esm
[esm-readme]: https://github.com/stdlib-js/simulate-iter/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/simulate-iter/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/simulate-iter/main/LICENSE

<!-- <toc-links> -->

[@stdlib/simulate/iter/awgn]: https://github.com/stdlib-js/simulate-iter-awgn

[@stdlib/simulate/iter/awln]: https://github.com/stdlib-js/simulate-iter-awln

[@stdlib/simulate/iter/awun]: https://github.com/stdlib-js/simulate-iter-awun

[@stdlib/simulate/iter/bartlett-hann-pulse]: https://github.com/stdlib-js/simulate-iter-bartlett-hann-pulse

[@stdlib/simulate/iter/bartlett-pulse]: https://github.com/stdlib-js/simulate-iter-bartlett-pulse

[@stdlib/simulate/iter/cosine-wave]: https://github.com/stdlib-js/simulate-iter-cosine-wave

[@stdlib/simulate/iter/dirac-comb]: https://github.com/stdlib-js/simulate-iter-dirac-comb

[@stdlib/simulate/iter/flat-top-pulse]: https://github.com/stdlib-js/simulate-iter-flat-top-pulse

[@stdlib/simulate/iter/hann-pulse]: https://github.com/stdlib-js/simulate-iter-hann-pulse

[@stdlib/simulate/iter/lanczos-pulse]: https://github.com/stdlib-js/simulate-iter-lanczos-pulse

[@stdlib/simulate/iter/periodic-sinc]: https://github.com/stdlib-js/simulate-iter-periodic-sinc

[@stdlib/simulate/iter/pulse]: https://github.com/stdlib-js/simulate-iter-pulse

[@stdlib/simulate/iter/sawtooth-wave]: https://github.com/stdlib-js/simulate-iter-sawtooth-wave

[@stdlib/simulate/iter/sine-wave]: https://github.com/stdlib-js/simulate-iter-sine-wave

[@stdlib/simulate/iter/square-wave]: https://github.com/stdlib-js/simulate-iter-square-wave

[@stdlib/simulate/iter/triangle-wave]: https://github.com/stdlib-js/simulate-iter-triangle-wave

<!-- </toc-links> -->

</section>

<!-- /.links -->
