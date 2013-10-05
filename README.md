libssc
======
Superfast Symmetric Compression

Preamble
--------
<b>libssc</b> is a free C99, open-source, BSD licensed compression library.

It is focused on high-speed compression, at the best ratio possible.
The word "symmetric" indicates that compression and decompression speeds are expected to be similar (i.e. very fast).
<b>libssc</b> features two APIs to enable quick integration in any project.

Benchmark
---------

API
---
<b>libssc</b> features a *stream API* and a *buffer API* which are very simple to use, yet powerful enough to keep users' creativity unleashed. The stream API is described here, and the buffers API here.

Output
------
<b>libssc</b> outputs compressed data in a simple format, which enables file storage and parallelization for both compression and decompression.
![libssc output format](http://www.centaurean.com/images/ssc_output_format.png)
More <a href=https://github.com/gpnuma/libssc/wiki/Format>details here</a>.

Building libssc
---------------
<b>libssc</b> is fully C99 compliant and can therefore be built on a number of platforms. Build instructions are <a href=https://github.com/gpnuma/libssc/wiki/Building>detailed here</a>.

FAQ
---
The FAQ can be <a href=https://github.com/gpnuma/libssc/wiki/FAQ>found here</a>.