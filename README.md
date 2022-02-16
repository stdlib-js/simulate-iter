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

# Simulation Iterators

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Simulation iterators.



<section class="usage">

## Usage

```javascript
import ns from 'https://cdn.jsdelivr.net/gh/stdlib-js/simulate-iter@esm/index.mjs';
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

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import objectKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@esm/index.mjs';
import ns from 'https://cdn.jsdelivr.net/gh/stdlib-js/simulate-iter@esm/index.mjs';

console.log( objectKeys( ns ) );

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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/simulate-iter.svg
[npm-url]: https://npmjs.org/package/@stdlib/simulate-iter

[test-image]: https://github.com/stdlib-js/simulate-iter/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/simulate-iter/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/simulate-iter/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/simulate-iter?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/simulate-iter.svg
[dependencies-url]: https://david-dm.org/stdlib-js/simulate-iter/main

-->

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/simulate-iter/tree/deno
[umd-url]: https://github.com/stdlib-js/simulate-iter/tree/umd
[esm-url]: https://github.com/stdlib-js/simulate-iter/tree/esm

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/simulate-iter/main/LICENSE

<!-- <toc-links> -->

[@stdlib/simulate/iter/awgn]: https://github.com/stdlib-js/simulate-iter-awgn/tree/esm

[@stdlib/simulate/iter/awln]: https://github.com/stdlib-js/simulate-iter-awln/tree/esm

[@stdlib/simulate/iter/awun]: https://github.com/stdlib-js/simulate-iter-awun/tree/esm

[@stdlib/simulate/iter/bartlett-hann-pulse]: https://github.com/stdlib-js/simulate-iter-bartlett-hann-pulse/tree/esm

[@stdlib/simulate/iter/bartlett-pulse]: https://github.com/stdlib-js/simulate-iter-bartlett-pulse/tree/esm

[@stdlib/simulate/iter/cosine-wave]: https://github.com/stdlib-js/simulate-iter-cosine-wave/tree/esm

[@stdlib/simulate/iter/dirac-comb]: https://github.com/stdlib-js/simulate-iter-dirac-comb/tree/esm

[@stdlib/simulate/iter/flat-top-pulse]: https://github.com/stdlib-js/simulate-iter-flat-top-pulse/tree/esm

[@stdlib/simulate/iter/hann-pulse]: https://github.com/stdlib-js/simulate-iter-hann-pulse/tree/esm

[@stdlib/simulate/iter/lanczos-pulse]: https://github.com/stdlib-js/simulate-iter-lanczos-pulse/tree/esm

[@stdlib/simulate/iter/periodic-sinc]: https://github.com/stdlib-js/simulate-iter-periodic-sinc/tree/esm

[@stdlib/simulate/iter/pulse]: https://github.com/stdlib-js/simulate-iter-pulse/tree/esm

[@stdlib/simulate/iter/sawtooth-wave]: https://github.com/stdlib-js/simulate-iter-sawtooth-wave/tree/esm

[@stdlib/simulate/iter/sine-wave]: https://github.com/stdlib-js/simulate-iter-sine-wave/tree/esm

[@stdlib/simulate/iter/square-wave]: https://github.com/stdlib-js/simulate-iter-square-wave/tree/esm

[@stdlib/simulate/iter/triangle-wave]: https://github.com/stdlib-js/simulate-iter-triangle-wave/tree/esm

<!-- </toc-links> -->

</section>

<!-- /.links -->
