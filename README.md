# Fruits Plotter - PoC2 plotter in Rust

### Features
- windows, linux, unix & macOS
- x86 32&64bit 
- direct and async i/o
- SIMD support: sse2, avx, avx2, avx512f
- gpu support
- fastest plotter there is

### Requirements
- new version of rust [stable toolchain]

### Compile, test, ...

Binaries are in **target/debug** or **target/release** depending on optimization.

``` shell
# build debug und run directly
cargo run [--features=opencl]

# build debug (unoptimized)
cargo build [--features=opencl]

# build release (optimized)
cargo build --release [--features=opencl]
```

### Run

```shell
fruits-plotter --help
```



