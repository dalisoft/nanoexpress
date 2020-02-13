# Benchmarks

Note: _Multi-threading/Clustering is available in Linux-only env_

Note #2: _Docker may be a good place to get started with Clustering_

You can see live benchmark results at [here](https://github.com/the-benchmarker/web-frameworks#results)

## Response/second

![Benchmarks](https://github.com/dalisoft/nanoexpress/raw/master/.github/images/benchmark.png)

## Memory usage

![Memory Usage](https://github.com/dalisoft/nanoexpress/raw/master/.github/images/memory.png)

While performing tests on my macBook Pro 2012 13" (Core i5, 8Gb RAM) performance is shown.

**Note**: _Real-world app memory/rps may differs from these numbers and these numbers are in my macBook_

_You can install `wrk` via `Homebrew` in `macOS` or `Linux`_

**Benchmark command**: `wrk -t1 -d60 -c100`

[&laquo; Docker](./docker.md)

[Testing &raquo;](./testing.md)
