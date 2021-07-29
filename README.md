# CSS Parser

## CSS Object Model

See [https://sazumivicky.github.io/sazumi-parser-tools).

## Commands

### Benchmark

```shell
npm run benchmark
```

```
> node run/benchmark.tokenize.js


Collecting PostCSS Tokenizer Benchmarks...

PostCSS Tokenizer (7.0.32):      49872 tokens in  9 ms
PostCSS Tokenizer (Development): 58823 tokens in 11 ms (1.2 times slower)


> node run/benchmark.parse.js


Collecting PostCSS Parser Benchmarks...

PostCSS Parser (7.0.32):         6240 values in 12 ms
PostCSS Parser (Development):   58823 values in 34 ms (2.9 times slower)
PostCSS/Selector/Value Parsers: 28491 values in 74 ms (6.3 times slower)
```

### Build

```shell
npm run build
```

### Test

```shell
npm run test
```
©copyright 2008-2021 sazumi vicky all right reserved.
